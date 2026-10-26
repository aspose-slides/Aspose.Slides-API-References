---
title: HtmlExternalResolver
second_title: Aspose.Sildes 用于 PHP 的 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/htmlexternalresolver/
---
## HtmlExternalResolver 类

回调对象，用于 HTML 导入例程以获取诸如图像等引用对象。使用此解析器可能会在客户端提供的 HTML 文件使服务器软件获取本地或网络文件时产生安全漏洞。使用时请谨慎。建议根本不要指定 HtmlExternalResolver（仅会读取嵌入对象），或者创建一个子类来检查指定的 uri 是否有效。

### HtmlExternalResolver {#HtmlExternalResolver}

| 名称 | 描述 |
| --- | --- |
| HtmlExternalResolver() |  |

 **返回：**
HtmlExternalResolver

---


### getEntity {#getEntity}

| 名称 | 描述 |
| --- | --- |
| getEntity (String) | 将 URI 映射到包含实际资源的对象。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| absoluteUri | String | 对象的绝对 URI。 |

 **返回：**
InputStream

---


### resolveUri {#resolveUri}

| 名称 | 描述 |
| --- | --- |
| resolveUri (String, String) | 根据基准 URI 和相对 URI 解析出绝对 URI。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| baseUri | String | 链接对象的基准 URI |
| relativeUri | String | 链接对象的相对 URI。 |

 **返回：**
String

---