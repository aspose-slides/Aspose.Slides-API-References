---
title: Add()
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 建立新的漸層色止點並將其加入集合的末端。
type: docs
weight: 14
url: /zh-hant/aspose.slides/igradientstopcollection/add/
---
## IGradientStopCollection::Add(float, System::Drawing::Color) 方法

建立新的漸層色止點並將其加入集合的末端。

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, System::Drawing::Color color)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | **float** | 新的漸層色止點位置。 |
| color | [System::Drawing::Color](../../../system.drawing/color/) | 新的漸層色止點的顏色。 |

### 回傳值

新漸層色止點在集合中的索引。

## IGradientStopCollection::Add(float, PresetColor) 方法

建立新的漸層色止點並將其加入集合的末端。

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, PresetColor presetColor)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | **float** | 新的漸層色止點位置。 |
| presetColor | [PresetColor](../../presetcolor/) | 新的漸層色止點的顏色。 |

### 回傳值

新漸層色止點在集合中的索引。

## IGradientStopCollection::Add(float, SchemeColor) 方法

建立新的漸層色止點並將其加入集合的末端。

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, SchemeColor schemeColor)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | **float** | 新的漸層色止點位置。 |
| schemeColor | [SchemeColor](../../schemecolor/) | 新的漸層色止點的顏色。 |

### 回傳值

新漸層色止點在集合中的索引。

## 另請參閱

* 列舉 [PresetColor](../../presetcolor/)
* 列舉 [SchemeColor](../../schemecolor/)
* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IGradientStop](../../igradientstop/)
* 類別 [Color](../../../system.drawing/color/)
* 類別 [IGradientStopCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)