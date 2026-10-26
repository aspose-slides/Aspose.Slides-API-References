---
title: PresentationFactory
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs
url: /zh/aspose.slides/presentationfactory/
---
## PresentationFactory 类

 允许通过 COM 接口创建演示文稿

### PresentationFactory {#PresentationFactory}

| 名称 | 描述 |
| --- | --- |
| PresentationFactory() |  |

**返回：**
PresentationFactory


---


### createPresentation {#createPresentation}

| 名称 | 描述 |
| --- | --- |
| createPresentation () | 创建新的演示文稿。 |

**返回：**
[Presentation](../presentation)


---


### createPresentation {#createPresentation}

| 名称 | 描述 |
| --- | --- |
| createPresentation ([LoadOptions](../loadoptions)) | 使用附加加载选项创建新的演示文稿。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| options | [LoadOptions](../loadoptions) | 加载选项 |

**返回：**
[Presentation](../presentation)


---


### getInstance {#getInstance}

| 名称 | 描述 |
| --- | --- |
| getInstance () | 演示文稿工厂的静态实例。只读 PresentationFactory。 |

**返回：**
PresentationFactory


---


### getPresentationInfo {#getPresentationInfo}

| 名称 | 描述 |
| --- | --- |
| getPresentationInfo (String) | 从文件创建新的 PresentationInfo 对象并将演示文稿绑定到该对象。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| file | String | 演示文稿文件。 |

**返回：**
[PresentationInfo](../presentationinfo)


---


### getPresentationInfo {#getPresentationInfo}

| 名称 | 描述 |
| --- | --- |
| getPresentationInfo (InputStream) | 从流创建新的 PresentationInfo 对象并将演示文稿绑定到该对象。获取指定流中演示文稿的信息。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 演示文稿流。 |

**返回：**
[PresentationInfo](../presentationinfo)


---


### getPresentationText {#getPresentationText}

| 名称 | 描述 |
| --- | --- |
| getPresentationText (String, int) | 从幻灯片检索原始文本。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| file | String | 输入文件 |
| mode | int | 提取模式 |

**返回：**
[PresentationText](../presentationtext)


---


### getPresentationText {#getPresentationText}

| 名称 | 描述 |
| --- | --- |
| getPresentationText (InputStream, int) | 从幻灯片检索原始文本。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 输入流 |
| mode | int | 提取模式 |

**返回：**
[PresentationText](../presentationtext)


---


### getPresentationText {#getPresentationText}

| 名称 | 描述 |
| --- | --- |
| getPresentationText (InputStream, int, [LoadOptions](../loadoptions)) | 从幻灯片检索原始文本。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 输入流 |
| mode | int | 提取模式 |
| options | [LoadOptions](../loadoptions) | 加载选项 |

**返回：**
[PresentationText](../presentationtext)


---


### readPresentation {#readPresentation}

| 名称 | 描述 |
| --- | --- |
| readPresentation (byte[]) | 从数组读取现有演示文稿。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | 要读取的数组 |

**返回：**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| 名称 | 描述 |
| --- | --- |
| readPresentation (byte[], [LoadOptions](../loadoptions)) | 使用附加加载选项从数组读取现有演示文稿。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| data | byte[] | 要读取的数组 |
| options | [LoadOptions](../loadoptions) | 加载选项 |

**返回：**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| 名称 | 描述 |
| --- | --- |
| readPresentation (InputStream) | 从流读取现有演示文稿。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 要读取的输入流 |

**返回：**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| 名称 | 描述 |
| --- | --- |
| readPresentation (InputStream, [LoadOptions](../loadoptions)) | 使用附加加载选项从流读取现有演示文稿。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| stream | InputStream | 要读取的输入流 |
| options | [LoadOptions](../loadoptions) | 加载选项 |

**返回：**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| 名称 | 描述 |
| --- | --- |
| readPresentation (String) | 从文件读取现有演示文稿。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| file | String | 文件名 |

**返回：**
[Presentation](../presentation)


---


### readPresentation {#readPresentation}

| 名称 | 描述 |
| --- | --- |
| readPresentation (String, [LoadOptions](../loadoptions)) | 使用附加加载选项从流读取现有演示文稿。 |

**参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| file | String | 文件名 |
| options | [LoadOptions](../loadoptions) | 加载选项 |

**返回：**
[Presentation](../presentation)


---