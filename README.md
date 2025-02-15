# observable-demo

## Observable for OpenTelemetry

- 收集器：OpenTelemetry Collector

- Agent：OpenTelemetry Java Agent 、OpenTelemetry-Js

- SDK : OpenTelemetry Java SDK

- Metrics：Prometheus

- 可视化：Zipkin、Jaeger

- Exporter: JaegerExporter \ OtlpExporter \ ZipkinExporter

## 项目介绍
```shell
.
├── apm ----------------------------------------- 主要是常见apm 安装使用手册
├── images -------------------------------------- 主要是各个项目使用的image 集合
├── opentelemetry-collector --------------------- 为 otel 官方采集器用法
├── opentelemetry-javaagent --------------------- 为 opentelemetry-javaagent 各版本jar，方便下载使用
├── opentelemetry-js ---------------------------- 主要演示 opentelemetry 提供的前端RUM功能以及如何跟后端APM结合使用，完成全链路追踪
├── opentelemetry-python ------------------------ opentelemetry python 使用方式（手动、自动），后端采用了 grafana tempo（jaeger gRPC/thrift 协议）
├── otel-collector-demo 
├── springboot-client --------------------------- Springboot 客户端
├── springboot-ddtrace-server ------------------- 主要介绍datadog 的 apm 组件 ddtrace 的使用方法（基于 Springboot 应用）
├── springboot-opentelemetry-jaeger-client ------ 介绍 opentelemetry 的 jaegerExporter 用法（基于Springboot分布式应用客户端）
├── springboot-opentelemetry-jaeger-server ------ 介绍 opentelemetry 的 jaegerExporter 用法（基于Springboot分布式应用服务端）
├── springboot-opentelemetry-otlp-client -------- 介绍 opentelemetry 的 otlpExporter 用法（基于Springboot分布式应用客户端）
├── springboot-opentelemetry-otlp-server -------- 介绍 opentelemetry 的 otlpExporter 用法（基于Springboot分布式应用服务端）
├── springboot-opentracing-jaeger --------------- 介绍 jaeger 用法（基于springboot 应用）
└── springboot-server --------------------------- Springboot 服务端，结合客户端一起使用，方便查看分布式应用链路情况
```