---
title: Add()
second_title: Aspose.Slides for C++ API 參考
description: 建立新的漸層停止點並將其加入集合的末端。
type: docs
weight: 53
url: /zh-hant/aspose.slides/gradientstopcollection/add/
---
## GradientStopCollection::Add(float, System::Drawing::Color) 方法


建立新的漸層停止點並將其加入集合的末端。

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, System::Drawing::Color color) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | **float** | 新漸層停止點的位置。 |
| color | [System::Drawing::Color](../../../system.drawing/color/) | 新漸層停止點的顏色。 |

### 回傳值

新漸層停止點在集合中的索引。

## GradientStopCollection::Add(float, PresetColor) 方法


建立新的漸層停止點並將其加入集合的末端。

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, PresetColor presetColor) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | **float** | 新漸層停止點的位置。 |
| presetColor | [PresetColor](../../presetcolor/) | 新漸層停止點的顏色。 |

### 回傳值

新漸層停止點在集合中的索引。

## GradientStopCollection::Add(float, SchemeColor) 方法


建立新的漸層停止點並將其加入集合的末端。

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, SchemeColor schemeColor) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| position | **float** | 新漸層停止點的位置。 |
| schemeColor | [SchemeColor](../../schemecolor/) | 新漸層停止點的顏色。 |

### 回傳值

新漸層停止點在集合中的索引。

## 另請參閱

* 列舉 [PresetColor](../../presetcolor/)
* 列舉 [SchemeColor](../../schemecolor/)
* 類型定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IGradientStop](../../igradientstop/)
* 類別 [Color](../../../system.drawing/color/)
* 類別 [GradientStopCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 程式庫 [Aspose.Slides](../../../)