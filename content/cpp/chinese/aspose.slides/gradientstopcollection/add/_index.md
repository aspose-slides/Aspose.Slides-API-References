---
title: Add()
second_title: Aspose.Slides for C++ API 参考
description: 创建新的渐变停止点并将其添加到集合的末尾。
type: docs
weight: 53
url: /zh/aspose.slides/gradientstopcollection/add/
---
## GradientStopCollection::Add(float, System::Drawing::Color) 方法

创建新的渐变停止点并将其添加到集合的末尾。

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, System::Drawing::Color color) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | **float** | 新渐变停止点的位置。 |
| color | [System::Drawing::Color](../../../system.drawing/color/) | 新渐变停止点的颜色。 |

### 返回值

集合中新渐变停止点的索引。

## GradientStopCollection::Add(float, PresetColor) 方法

创建新的渐变停止点并将其添加到集合的末尾。

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, PresetColor presetColor) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | **float** | 新渐变停止点的位置。 |
| presetColor | [PresetColor](../../presetcolor/) | 新渐变停止点的颜色。 |

### 返回值

集合中新渐变停止点的索引。

## GradientStopCollection::Add(float, SchemeColor) 方法

创建新的渐变停止点并将其添加到集合的末尾。

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, SchemeColor schemeColor) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| position | **float** | 新渐变停止点的位置。 |
| schemeColor | [SchemeColor](../../schemecolor/) | 新渐变停止点的颜色。 |

### 返回值

集合中新渐变停止点的索引。

## 另请参阅

* 枚举 [PresetColor](../../presetcolor/)
* 枚举 [SchemeColor](../../schemecolor/)
* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IGradientStop](../../igradientstop/)
* 类 [Color](../../../system.drawing/color/)
* 类 [GradientStopCollection](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)