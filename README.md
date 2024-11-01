```
docker run --rm -v $(pwd)/keys:/keys -v $(pwd)/test:/test -e GOOGLE_APPLICATION_CREDENTIALS=/keys/service-account.json quay.io/gannett/faas-artillery:latest run --dir /test --config /test/election-speed-test-config.yaml
```
