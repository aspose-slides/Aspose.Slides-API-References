---
title: PresentationAnimationsGenerator
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/presentationanimationsgenerator/
---
## PresentationAnimationsGenerator 类

 表示 Presentation 中动画的生成器。
 
### PresentationAnimationsGenerator {#PresentationAnimationsGenerator}

| 名称 | 描述 |
| --- | --- |
| PresentationAnimationsGenerator([Presentation](../presentation)) | 创建一个新的 PresentationAnimationsGenerator 实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| presentation | [Presentation](../presentation) | 将根据 Presentation#getSlideSize 设置帧大小。 |

 **返回值:**
PresentationAnimationsGenerator


---


### PresentationAnimationsGenerator {#PresentationAnimationsGenerator}

| 名称 | 描述 |
| --- | --- |
| PresentationAnimationsGenerator(Dimension) | 创建一个新的 PresentationAnimationsGenerator 实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| frameSize | Dimension | 帧大小。 |

 **返回值:**
PresentationAnimationsGenerator


---


### PresentationAnimationsGenerator {#PresentationAnimationsGenerator}

| 名称 | 描述 |
| --- | --- |
| PresentationAnimationsGenerator(Dimension2D) | 创建一个新的 PresentationAnimationsGenerator 实例。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| frameSize | Dimension2D | 帧大小。 |

 **返回值:**
PresentationAnimationsGenerator


---


### dispose {#dispose}

| 名称 | 描述 |
| --- | --- |
| dispose () | 释放 PresentationAnimationsGenerator 实例。 |

 **返回值:**
void


---


### getDefaultDelay {#getDefaultDelay}

| 名称 | 描述 |
| --- | --- |
| getDefaultDelay () | 获取或设置默认延迟时间 [ms]。 |

 **返回值:**
int


---


### getExportedSlides {#getExportedSlides}

| 名称 | 描述 |
| --- | --- |
| getExportedSlides () | 获取导出幻灯片的数量。 |

 **返回值:**
int


---


### getFrameSize {#getFrameSize}

| 名称 | 描述 |
| --- | --- |
| getFrameSize () | 获取帧大小。 |

 **返回值:**
Dimension


---


### getIncludeHiddenSlides {#getIncludeHiddenSlides}

| 名称 | 描述 |
| --- | --- |
| getIncludeHiddenSlides () | 获取或设置是否应包含隐藏的幻灯片。 |

 **返回值:**
boolean


---


### run {#run}

| 名称 | 描述 |
| --- | --- |
| run (com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides. ISlide>) | 为每个幻灯片运行动画事件生成。 |

 **返回值:**
void


---


### run {#run}

| 名称 | 描述 |
| --- | --- |
| run (com.aspose.ms.System.Collections.Generic.IGenericEnumerable<com.aspose.slides. ISlide>, int, [PresentationPlayer.FrameTick](../presentationplayer.frametick)) | 为每个幻灯片运行动画事件生成。 |

 **返回值:**
void


---


### setDefaultDelay {#setDefaultDelay}

| 名称 | 描述 |
| --- | --- |
| setDefaultDelay (int) | 获取或设置默认延迟时间 [ms]。 |

 **返回值:**
void


---


### setIncludeHiddenSlides {#setIncludeHiddenSlides}

| 名称 | 描述 |
| --- | --- |
| setIncludeHiddenSlides (boolean) | 获取或设置是否应包含隐藏的幻灯片。 |

 **返回值:**
void


---


### setNewAnimation {#setNewAnimation}

| 名称 | 描述 |
| --- | --- |
| setNewAnimation ([PresentationAnimationsGenerator.NewAnimation](../presentationanimationsgenerator.newanimation)) | 设置一个新的动画事件。 |

 **参数:**

| 名称 | 类型 | 描述 |
| --- | --- | --- |
| anim | [PresentationAnimationsGenerator.NewAnimation](../presentationanimationsgenerator.newanimation) | 动画事件。 |

 **返回值:**
void


---