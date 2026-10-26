---
title: Output
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/output/
---
## Output 类

 表示 IWebDocument 的输出元素集合。

### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (String, String, TContextObject) | 为上下文对象添加一个输出元素。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 输出路径。 |
| templateKey | String | 在输出前用于上下文对象转换的模板键。 |
| contextObject | TContextObject | 上下文对象。 |

**返回值：**
[OutputFile](../outputfile)


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (String, [PPImage](../ppimage)) | 为图像添加一个输出元素。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 输出路径。 |
| image | [PPImage](../ppimage) | 要输出的图像。 |

**返回值：**
[OutputFile](../outputfile)


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (String, [IImage](../iimage)) | 为图像添加一个输出元素。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 输出路径。 |
| image | [IImage](../iimage) | 要输出的图像。 |

**返回值：**
[OutputFile](../outputfile)


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (String, [Video](../video)) | 为视频添加一个输出元素。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 输出路径。 |
| video | [Video](../video) | 要输出的视频。 |

**返回值：**
[OutputFile](../outputfile)


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (String, [FontData](../fontdata), int) | 创建并添加指定字体的输出文件元素。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 保存字体输出的文件路径。 |
| fontData | [FontData](../fontdata) | 要写入输出的字体数据。 |
| fontStyle | int | 字体的样式（例如 Regular、Bold、Italic）。 |

**返回值：**
[OutputFile](../outputfile)


---


### add {#add}

| 名称 | 描述 |
| --- | --- |
| add (String, String) | 为文本内容添加一个输出元素。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 输出路径。 |
| textContent | String | 要输出的内容。 |

**返回值：**
[OutputFile](../outputfile)


---


### bindResource {#bindResource}

| 名称 | 描述 |
| --- | --- |
| bindResource ([OutputFile](../outputfile), Object) | 将资源绑定到输出文件。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| outputFile | [OutputFile](../outputfile) | 输出文件。 |
| obj | Object | 资源对象。 |

**返回值：**
void


---


### getResourcePath {#getResourcePath}

| 名称 | 描述 |
| --- | --- |
| getResourcePath (Object) | 返回给定资源的路径。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| obj | Object | 资源对象。 |

**返回值：**
String


---