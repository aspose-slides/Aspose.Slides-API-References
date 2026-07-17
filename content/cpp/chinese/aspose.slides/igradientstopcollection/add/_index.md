---
title: Add()
second_title: Aspose.Slides C++ API 参考
description: 创建新的渐变点并将其添加到集合的末尾。
type: docs
weight: 14
url: /zh/aspose.slides/igradientstopcollection/add/
---
## IGradientStopCollection::Add(float, System::Drawing::Color) 方法

创建新的渐变点并将其添加到集合的末尾。

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, System::Drawing::Color color)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | **float** | 新渐变点的位置。 |
| color | [System::Drawing::Color](../../../system.drawing/color/) | 新渐变点的颜色。 |

### 返回值

集合中新渐变点的索引。

## IGradientStopCollection::Add(float, PresetColor) 方法

创建新的渐变点并将其添加到集合的末尾。

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, PresetColor presetColor)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | **float** | 新渐变点的位置。 |
| presetColor | [PresetColor](../../presetcolor/) | 新渐变点的颜色。 |

### 返回值

集合中新渐变点的索引。

## IGradientStopCollection::Add(float, SchemeColor) 方法

创建新的渐变点并将其添加到集合的末尾。

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, SchemeColor schemeColor)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | **float** | 新渐变点的位置。 |
| schemeColor | [SchemeColor](../../schemecolor/) | 新渐变点的颜色。 |

### 返回值

集合中新渐变点的索引。

## 另请参见

* 枚举 [PresetColor](../../presetcolor/)
* 枚举 [SchemeColor](../../schemecolor/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IGradientStop](../../igradientstop/)
* 类 [Color](../../../system.drawing/color/)
* 类 [IGradientStopCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)