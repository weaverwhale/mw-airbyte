# Mike Notes

## How to spin up Airbyte

```bash
cd mw-airbyte
./run-ab-platform.sh 
```

## How to run a specific connector 

(We're gonna use my test integration as an example)

```bash
cd mw-airbyte/integrations/source-exchange-rates-tutorial
python main.py read --config secrets/config.json --catalog integration_tests/configured_catalog.json
```