---
title: TextAnimation
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/textanimation/
---
## TextAnimation 类

表示文本动画。

### TextAnimation {#TextAnimation}

| 名称 | 说明 |
| --- | --- |
| TextAnimation() |  |

 **返回:**
TextAnimation


---


### addEffect {#addEffect}

| 名称 | 说明 |
| --- | --- |
| addEffect (int, int, int) | 将新效果添加到当前序列的末尾或组文本动画的末尾。仅当文本段落的计数大于或等于该组效果的计数时有效！ |

 **参数:**

| 名称 | 类型 | 说明 |
| --- | --- | --- |
| effectType | int | 动画效果的类型 EffectType |
| subtype | int | 动画效果的子类型 EffectSubtype |
| triggerType | int | 效果的触发类型 EffectTriggerType |

 **返回:**
[Effect](../effect)


---


### getBuildType {#getBuildType}

| 名称 | 说明 |
| --- | --- |
| getBuildType () | 文本动画的构建类型列表（例如 Paragraph 1,2,3, All at Once）。读/写 BuildType。 |

 **返回:**
int


---


### getEffectAnimateBackgroundShape {#getEffectAnimateBackgroundShape}

| 名称 | 说明 |
| --- | --- |
| getEffectAnimateBackgroundShape () | 与组关联的形状效果，或无 (null)。读/写 IEffect。 |

 **返回:**
[Effect](../effect)


---


### setBuildType {#setBuildType}

| 名称 | 说明 |
| --- | --- |
| setBuildType (int) | 文本动画的构建类型列表（例如 Paragraph 1,2,3, All at Once）。读/写 BuildType。 |

 **返回:**
void


---


### setEffectAnimateBackgroundShape {#setEffectAnimateBackgroundShape}

| 名称 | 说明 |
| --- | --- |
| setEffectAnimateBackgroundShape ([Effect](../effect)) | 与组关联的形状效果，或无 (null)。读/写 IEffect。 |

 **返回:**
void


---