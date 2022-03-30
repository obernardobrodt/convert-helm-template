# convert-helm-template
esse projeto ensina a você converter um helm template em menisfestos de k8s


- add repo with helm

bash
    ` helm repo add nginx-stable https://helm.nginx.com/stable `


- repo update

bash
    `helm repo update`

- repo create manifets k8s

bash
    ` helm template nginx nginx-stable/nginx-ingress -f .\nginx-controller-value.yaml --output-dir=nginx`    