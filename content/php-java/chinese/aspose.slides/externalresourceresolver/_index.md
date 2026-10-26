---
title: ExternalResourceResolver
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/externalresourceresolver/
---
## ExternalResourceResolver 类

 用于在 Html、Svg 文档导入期间解析外部资源的回调类。使用此解析器可能会产生漏洞，当客户端提供的 HTML 或 SVG 文件导致服务器软件获取本地或网络文件时。请谨慎使用。建议完全不指定 ExternalResourceResolver（只会读取嵌入对象），或者创建一个子类来检查指定的 uri 是否有效。
### ExternalResourceResolver {#ExternalResourceResolver}

| 名称 | 描述 |
| --- | --- |
| ExternalResourceResolver() |  |

 **返回值：**
ExternalResourceResolver


---


### getEntity {#getEntity}

| 名称 | 描述 |
| --- | --- |
| getEntity (String) | 将 URI 映射到包含实际资源的对象。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | String | 指向对象的绝对 URI。 |

 **返回值：**
InputStream


---


### resolveUri {#resolveUri}

| 名称 | 描述 |
| --- | --- |
| resolveUri (String, String) | 从基准 URI 和相对 URI 解析出绝对 URI。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | String | 链接对象的基准 URI |
| relativeUri | String | 链接对象的相对 URI。 |

 **返回值：**
String


---



