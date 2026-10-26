---
title: NormalViewRestoredProperties
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/normalviewrestoredproperties/
---
## NormalViewRestoredProperties 类

 指定普通视图中幻灯片区域的大小（当其为 restoredTop 的子项时为宽度， 当其为 restoredLeft 的子项时为高度），当该区域具有可变的恢复大小（既未最小化也未最大化）时。

### getAutoAdjust {#getAutoAdjust}

| 名称 | 描述 |
| --- | --- |
| getAutoAdjust () | 指定在重新调整包含视图的窗口大小时，侧内容区域的大小是否应补偿新的尺寸。读/写 boolean。 |

 **返回值:**
boolean


---


### getDimensionSize {#getDimensionSize}

| 名称 | 描述 |
| --- | --- |
| getDimensionSize () | 指定幻灯片区域的大小（当其为 RestoredTop 的子项时为宽度， 当其为 RestoredLeft 的子项时为高度）。读/写 float。 |

 **返回值:**
float

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentOutOfRangeException | 当值小于 0 或大于 100 时抛出。 |


---


### setAutoAdjust {#setAutoAdjust}

| 名称 | 描述 |
| --- | --- |
| setAutoAdjust (boolean) | 指定在重新调整包含视图的窗口大小时，侧内容区域的大小是否应补偿新的尺寸。读/写 boolean。 |

 **返回值:**
void


---


### setDimensionSize {#setDimensionSize}

| 名称 | 描述 |
| --- | --- |
| setDimensionSize (float) | 指定幻灯片区域的大小（当其为 RestoredTop 的子项时为宽度， 当其为 RestoredLeft 的子项时为高度）。读/写 float。 |

 **返回值:**
void

 **异常**

| 错误 | 条件 |
| --- | --- |
 | ArgumentOutOfRangeException | 当值小于 0 或大于 100 时抛出。 |


---