---
title: Status
menu: { main: { weight: 30 } }
aliases: [/project-status, /releases]
description: Maturity-level of the main OpenTelemetry components
---

{{% blocks/section color="white" %}}

## {{% param title %}}

OpenTelemetry is made up of [several components](/docs/concepts/components/),
some language-specific and others language-agnostic. When looking for a
[status](/docs/specs/otel/versioning-and-stability/), make sure to look for the
status from the right component page. For example, the status of a signal in the
specification may not be the same as the signal status in a particular language
SDK.

## Language SDKs

For the development status, or maturity level, of a
[language SDK](/docs/languages/), see the following table:

{{% telemetry-support-table " " %}}

For more details on the specification compliance per implementation, see the
[Spec Compliance Matrix](https://github.com/open-telemetry/opentelemetry-specification/blob/main/spec-compliance-matrix.md).

## Collector

The collector status is:
[mixed](http://localhost:1313/docs/specs/otel/document-status/#mixed), since
core collector components currently have mixed
[stability levels](https://github.com/open-telemetry/opentelemetry-collector#stability-levels).

**Collector components** differ in their maturity levels. Each component has its
stability documented in its `README.md`. You can find a list of all available
collector components in the
[registry](http://localhost:1313/ecosystem/registry/?language=collector).

## Specifications

For the development status, or maturity level, of the
[specification](/docs/specs/otel/), see the following:
[Specification Status Summary](/docs/specs/status/).

{{% /blocks/section %}}
