---
title: SvgImage
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/svgimage/
---
## SvgImage 类

表示一个 SVG 图像。

### SvgImage {#SvgImage}

| 名称 | 描述 |
| --- | --- |
| SvgImage(byte[]) | 创建新的 SvgImage 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | Svg 数据。 |

**返回值：**
SvgImage


---


### SvgImage {#SvgImage}

| 名称 | 描述 |
| --- | --- |
| SvgImage(String) | 创建新的 SvgImage 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| svgContent | String | Svg 内容。 |

**返回值：**
SvgImage


---


### SvgImage {#SvgImage}

| 名称 | 描述 |
| --- | --- |
| SvgImage(InputStream) | 创建新的 SvgImage 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | Svg 流。 |

**返回值：**
SvgImage


---


### SvgImage {#SvgImage}

| 名称 | 描述 |
| --- | --- |
| SvgImage(byte[], [HtmlExternalResolver](../htmlexternalresolver), String) | 创建新的 SvgImage 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | Svg 数据。 |
| externalResResolver | [HtmlExternalResolver](../htmlexternalresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| baseUri | String | 指定 Svg 的基本 URI。用于解析相对链接。 |

**返回值：**
SvgImage


---


### SvgImage {#SvgImage}

| 名称 | 描述 |
| --- | --- |
| SvgImage(byte[], [ExternalResourceResolver](../externalresourceresolver), String) | 创建新的 SvgImage 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | Svg 数据。 |
| externalResResolver | [ExternalResourceResolver](../externalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| baseUri | String | 指定 Svg 的基本 URI。用于解析相对链接。 |

**返回值：**
SvgImage


---


### SvgImage {#SvgImage}

| 名称 | 描述 |
| --- | --- |
| SvgImage(String, [HtmlExternalResolver](../htmlexternalresolver), String) | 创建新的 SvgImage 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| svgContent | String | Svg 内容。 |
| externalResResolver | [HtmlExternalResolver](../htmlexternalresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| baseUri | String | 指定 Svg 的基本 URI。用于解析相对链接。 |

**返回值：**
SvgImage


---


### SvgImage {#SvgImage}

| 名称 | 描述 |
| --- | --- |
| SvgImage(String, [ExternalResourceResolver](../externalresourceresolver), String) | 创建新的 SvgImage 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| svgContent | String | Svg 内容。 |
| externalResResolver | [ExternalResourceResolver](../externalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| baseUri | String | 指定 Svg 的基本 URI。用于解析相对链接。 |

**返回值：**
SvgImage


---


### SvgImage {#SvgImage}

| 名称 | 描述 |
| --- | --- |
| SvgImage(InputStream, [HtmlExternalResolver](../htmlexternalresolver), String) | 创建新的 SvgImage 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | Svg 流。 |
| externalResResolver | [HtmlExternalResolver](../htmlexternalresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| baseUri | String | 指定 Svg 的基本 URI。用于解析相对链接。 |

**返回值：**
SvgImage


---


### SvgImage {#SvgImage}

| 名称 | 描述 |
| --- | --- |
| SvgImage(InputStream, [ExternalResourceResolver](../externalresourceresolver), String) | 创建新的 SvgImage 对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | Svg 流。 |
| externalResResolver | [ExternalResourceResolver](../externalresourceresolver) | 用于获取外部对象的回调对象。如果此参数为 null，则所有外部对象将被忽略。 |
| baseUri | String | 指定 Svg 的基本 URI。用于解析相对链接。 |

**返回值：**
SvgImage


---


### getBaseUri {#getBaseUri}

| 名称 | 描述 |
| --- | --- |
| getBaseUri () | 返回指定 Svg 的基本 URI。用于解析相对链接。只读 String。 |

**返回值：**
String


---


### getExternalResourceResolver {#getExternalResourceResolver}

| 名称 | 描述 |
| --- | --- |
| getExternalResourceResolver () | 返回在 Svg 文档导入期间用于解析外部资源的回调接口。只读 IExternalResourceResolver。 |

**返回值：**
[HtmlExternalResolver](../htmlexternalresolver), [ExternalResourceResolver](../externalresourceresolver)


---


### getSvgContent {#getSvgContent}

| 名称 | 描述 |
| --- | --- |
| getSvgContent () | 返回 SVG 内容。只读 String。 |

**返回值：**
String


---


### getSvgData {#getSvgData}

| 名称 | 描述 |
| --- | --- |
| getSvgData () | 返回 SVG 数据。只读 byte[]。 |

**返回值：**
byte


---


### writeAsEmf {#writeAsEmf}

| 名称 | 描述 |
| --- | --- |
| writeAsEmf (OutputStream) | 将 SVG 图像保存为 EMF 文件。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | OutputStream | 目标流 |

**返回值：**
void

**异常**

| 错误 | 条件 |
| --- | --- |
| ArgumentNullException | 目标流为 null |