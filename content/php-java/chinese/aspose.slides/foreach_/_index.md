---
title: ForEach_
second_title: Aspose.Sildes for PHP 通过 Java API 参考
description: 
type: docs

url: /zh/aspose.slides/foreach_/
---
## ForEach_ 类

 表示一组用于遍历不同 Presentation 模型对象的方法。
 如果需要遍历并更改某些 Presentation 元素的格式或内容，例如更改每个 portion 的格式，这些方法会非常有用。

### ForEach_ {#ForEach_}

| 名称 | 描述 |
| --- | --- |
| ForEach_() |  |

 **返回值：**
ForEach_

---


### layoutSlide {#layoutSlide}

| 名称 | 描述 |
| --- | --- |
| layoutSlide ([Presentation](../presentation), [ForEach_.ForEachLayoutSlideCallback](../foreach_.foreachlayoutslidecallback)) | 遍历每个 #layoutSlide(Presentation,ForEachLayoutSlideCallback) 在演示文稿中。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 要遍历布局幻灯片的 Presentation |
| forEachLayoutSlide | [ForEach_.ForEachLayoutSlideCallback](../foreach_.foreachlayoutslidecallback) | 将为每个布局幻灯片调用的回调 |

 **返回值：**
void

---


### masterSlide {#masterSlide}

| 名称 | 描述 |
| --- | --- |
| masterSlide ([Presentation](../presentation), [ForEach_.ForEachMasterSlideCallback](../foreach_.foreachmasterslidecallback)) | 遍历每个 #masterSlide(Presentation,ForEachMasterSlideCallback) 在演示文稿中。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 要遍历母版幻灯片的 Presentation |
| forEachMasterSlide | [ForEach_.ForEachMasterSlideCallback](../foreach_.foreachmasterslidecallback) | 将为每个母版幻灯片调用的回调 |

 **返回值：**
void

---


### paragraph {#paragraph}

| 名称 | 描述 |
| --- | --- |
| paragraph ([Presentation](../presentation), [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback)) | 遍历每个 Paragraph 在演示文稿中。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 要遍历段落的 Presentation |
| forEachParagraph | [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback) | 将为每个段落调用的回调；形状将在所有类型的幻灯片中遍历 - #slide(Presentation,ForEachSlideCallback)、#masterSlide(Presentation,ForEachMasterSlideCallback) 和 #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

 **返回值：**
void

---


### paragraph {#paragraph}

| 名称 | 描述 |
| --- | --- |
| paragraph ([Presentation](../presentation), boolean, [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback)) | 遍历每个 Paragraph 在演示文稿中。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 要遍历段落的 Presentation |
| includeNotes | boolean | 指示是否应在处理时包含 NotesSlides 的标志。 |
| forEachParagraph | [ForEach_.ForEachParagraphCallback](../foreach_.foreachparagraphcallback) | 将为每个段落调用的回调；形状将在所有类型的幻灯片中遍历 - #slide(Presentation,ForEachSlideCallback)、#masterSlide(Presentation,ForEachMasterSlideCallback)、#layoutSlide(Presentation,ForEachLayoutSlideCallback) 和 NotesSlide |

 **返回值：**
void

---


### portion {#portion}

| 名称 | 描述 |
| --- | --- |
| portion ([Presentation](../presentation), [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback)) | 遍历每个 Portion 在演示文稿中。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 要遍历部分的 Presentation |
| forEachPortion | [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback) | 将为每个部分调用的回调；部分将在所有类型的幻灯片中遍历 - #slide(Presentation,ForEachSlideCallback)、#masterSlide(Presentation,ForEachMasterSlideCallback) 和 #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

 **返回值：**
void

---


### portion {#portion}

| 名称 | 描述 |
| --- | --- |
| portion ([Presentation](../presentation), boolean, [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback)) | 遍历每个 Portion 在演示文稿中。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 要遍历部分的 Presentation |
| includeNotes | boolean | 指示是否应在处理时包含 NotesSlides 的标志。 |
| forEachPortion | [ForEach_.ForEachPortionCallback](../foreach_.foreachportioncallback) | 将为每个部分调用的回调；部分将在所有类型的幻灯片中遍历 - #slide(Presentation,ForEachSlideCallback)、#masterSlide(Presentation,ForEachMasterSlideCallback)、#layoutSlide(Presentation,ForEachLayoutSlideCallback) 和 NotesSlide |

 **返回值：**
void

---


### shape {#shape}

| 名称 | 描述 |
| --- | --- |
| shape ([Presentation](../presentation), [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | 遍历每个 Shape 在演示文稿中。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 要遍历布局形状的 Presentation |
| forEachShape | [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback) | 将为每个形状调用的回调；形状将在所有类型的幻灯片中遍历 - #slide(Presentation,ForEachSlideCallback)、#masterSlide(Presentation,ForEachMasterSlideCallback) 和 #layoutSlide(Presentation,ForEachLayoutSlideCallback) |

 **返回值：**
void

---


### shape {#shape}

| 名称 | 描述 |
| --- | --- |
| shape ([Presentation](../presentation), boolean, [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | 遍历每个 Shape 在演示文稿中。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 要遍历布局形状的 Presentation |
| includeNotes | boolean | 指示是否应在处理时包含 NotesSlides 的标志。 |
| forEachShape | [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback) | 将为每个形状调用的回调；形状将在所有类型的幻灯片中遍历 - #slide(Presentation,ForEachSlideCallback)、#masterSlide(Presentation,ForEachMasterSlideCallback)、#layoutSlide(Presentation,ForEachLayoutSlideCallback) 和 NotesSlide（如果需要） |

 **返回值：**
void

---


### shape {#shape}

| 名称 | 描述 |
| --- | --- |
| shape ([BaseSlide](../baseslide), [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback)) | 遍历每个 Shape 在 BaseSlide 中。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| baseSlide | [BaseSlide](../baseslide) | 要遍历布局形状的 Slide |
| forEachShape | [ForEach_.ForEachShapeCallback](../foreach_.foreachshapecallback) | 将为每个形状调用的回调；BaseSlide 是 #slide(Presentation,ForEachSlideCallback)、#masterSlide(Presentation,ForEachMasterSlideCallback) 和 #layoutSlide(Presentation,ForEachLayoutSlideCallback) 的基类型 |

 **返回值：**
void

---


### slide {#slide}

| 名称 | 描述 |
| --- | --- |
| slide ([Presentation](../presentation), [ForEach_.ForEachSlideCallback](../foreach_.foreachslidecallback)) | 遍历每个 #slide(Presentation,ForEachSlideCallback) 在演示文稿中。 |

 **参数：**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| pres | [Presentation](../presentation) | 要遍历幻灯片的 Presentation |
| forEachSlide | [ForEach_.ForEachSlideCallback](../foreach_.foreachslidecallback) | 将为每个幻灯片调用的回调 |

 **返回值：**
void

---