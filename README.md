# gpt2-train-MUw50V3-NsOUI5Wswo7

[![Run on Ainize](https://ainize.ai/static/images/run_on_ainize_button.svg)](https://ainize.web.app/redirect?git_repo=https://github.com/ainize-bot/gpt2-train-MUw50V3-NsOUI5Wswo7)

Auto-generated github repository by [Ainize Teachable NLP](https://ainize.ai/teachable-nlp)

## Health Check
Using `curl` in the terminal:
```
$ curl --request GET 'https://main-gpt2-train-m-uw50v3-ns-oui5wswo7-teachable-ainize.endpoint.ainize.ai/ping'
{
  "status": "Healthy"
}
```

## Prediction Test
Using `curl` in the terminal:
```
$ curl --request POST 'https://main-gpt2-train-m-uw50v3-ns-oui5wswo7-teachable-ainize.endpoint.ainize.ai/predictions/gpt-2-en-small-finetune.mar' \
  --header 'Content-Type: application/json' \
  --data-raw '{
    "text": [3666, 1438, 318, 14200, 11, 314, 16486, 1850, 287, 13851, 3783],
    "num_samples": 5,
    "length": 8
  }'
[
  [
    3666, 1438, 318, 14200, 11, 314, 16486, 1850, 287, 13851, 3783, 11, 314, 1101, 422, 262, 1294, 11, 523
  ],
  ...,
  [
    3666, 1438, 318, 14200, 11, 314, 16486, 1850, 287, 13851, 3783, 379, 262, 2059, 286, 520, 26414, 11, 543
  ]
]
``` 