# Changelog

Changelog for the K8ssandra Operator, new PRs should update the `unreleased` section below with entries describing the changes like:

```markdown
* [CHANGE]
* [FEATURE]
* [ENHANCEMENT]
* [BUGFIX]
* [DOCS]
* [TESTING]
```

When cutting a new release, update the `unreleased` heading to the tag being generated and date, like `## vX.Y.Z - YYYY-MM-DD` and create a new placeholder section for  `unreleased` entries.

## unreleased

* [FEATURE] [#599](https://github.com/k8ssandra/k8ssandra-operator/issues/599) Introduce a secrets provider setting in the CRD
* [FEATURE] [#728](https://github.com/k8ssandra/k8ssandra-operator/issues/728) Add token generation utility
* [FEATURE] [#724](https://github.com/k8ssandra/k8ssandra-operator/issues/724) Ability to provide per-node configuration
  [FEATURE] [#718](https://github.com/k8ssandra/k8ssandra-operator/issues/718) Make keystore-password, keystore, truststore keys in secret configurable