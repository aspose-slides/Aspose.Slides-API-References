---
title: SetSize()
second_title: Aspose.Slides for C++ API 參考
description: 依類型設定投影片大小，並縮放現有內容。
type: docs
weight: 53
url: /zh-hant/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) 方法


根據類型設定投影片大小，並縮放現有內容。

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | 要套用的預先定義投影片大小。 |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 要使用的內容縮放模式。 |
## 備註


指派除 [SlideSizeType::Custom](../../slidesizetype/) 之外的任何值，會根據所選類型調整 [SlideSize::get_Size](../get_size/)，同時保留 [SlideSize::get_Orientation](../get_orientation/)。 

## SlideSize::SetSize(float, float, SlideSizeScaleType) 方法


明確設定投影片尺寸，並縮放現有內容。

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| width | **float** | 新的投影片寬度（以點為單位）。 |
| height | **float** | 新的投影片高度（以點為單位）。 |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 要使用的內容縮放模式。 |
## 備註


這會將 [SlideSize::get_Type](../get_type/) 屬性重設為 [SlideSizeType::Custom](../../slidesizetype/)，並設定 [Orientation](../../orientation/)。 

## 另請參閱

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* 類別 [SlideSize](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)