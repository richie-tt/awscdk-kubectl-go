# This repository is fork for [https://github.com/cdklabs/awscdk-kubectl-go](https://github.com/cdklabs/awscdk-kubectl-go/tree/kubectl.33)

After upgrading `aws-cdk-go` to `>v2.223.0` there was change with `Env()` function which will complain now

```
/go/pkg/mod/github.com/cdklabs/awscdk-kubectl-go/kubectlv34/v2@v2.0.0/KubectlV34Layer.go:15:2: duplicate method Env
go/pkg/mod/github.com/cdklabs/awscdk-kubectl-go/kubectlv34/v2@v2.0.0/KubectlV34Layer.go:26:2: other declaration of method Env
```

is required to change the `awscdk.ResourceEnvironment` -> `interfaces.ResourceEnvironment`

## Go Bindings for awscdk-asset-kubectl

This repository included Go bindings for [awscdk-asset-kubectl](https://github.com/cdklabs/awscdk-asset-kubectl).

## Security

See [Security Issue Notifications](CONTRIBUTING.md#security-issue-notifications) for more information.

## License

This project is licensed under the Apache-2.0 License.
