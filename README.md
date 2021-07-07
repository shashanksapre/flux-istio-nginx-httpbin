# flux-istio-nginx-httpbin

export GITHUB_TOKEN=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
export GITHUB_USER=shanky53

flux bootstrap github \
  --owner=shanky53 \
  --repository=flux-istio-nginx-httpbin \
  --branch=develop \
  --path=./clusters/development


`flux bootstrap github --owner=shanky53 --repository=flux-istio-nginx-httpbin --branch=istio-addons --path=./clusters/development`