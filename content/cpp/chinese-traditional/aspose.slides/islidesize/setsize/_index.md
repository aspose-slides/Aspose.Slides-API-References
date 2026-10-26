---
title: SetSize()
second_title: Aspose.Slides for C++ API 參考文件
description: "根據類型設定投影片大小並縮放現有內容。將任何值設定為非 SlideSizeType::Custom 時，會根據選取的類型調整 ISlideSize::get_Size，同時保留 ISlideSize::get_Orientation。"
type: docs
weight: 53
url: /zh-hant/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) 方法

根據類型設定投影片大小並縮放現有內容。將任何值設為非 [SlideSizeType::Custom](../../slidesizetype/) 之外的值時，會根據所選類型調整 [ISlideSize::get_Size](../get_size/)，同時保留 [ISlideSize::get_Orientation](../get_orientation/)。

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | 要套用的預先定義投影片大小。 |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 要使用的內容縮放模式。 |
## 備註

將任何值設為非 [SlideSizeType::Custom](../../slidesizetype/) 之外的值時，會根據所選類型調整 [System::Drawing::Size](../../../system.drawing/size/)，同時保留 [Orientation](../../orientation/)。

## ISlideSize::SetSize(float, float, SlideSizeScaleType) 方法

明確設定投影片尺寸並縮放現有內容。此操作會將 [ISlideSize::get_Type](../get_type/) 值重設為 [SlideSizeType::Custom](../../slidesizetype/)，並設定 [ISlideSize::get_Orientation](../get_orientation/)。

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| width | **float** | 新的投影片寬度（單位為點）。 |
| height | **float** | 新的投影片高度（單位為點）。 |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 要使用的內容縮放模式。 |
## 備註

此操作會將 [ISlideSize::get_Type](../get_type/) 屬性重設為 [SlideSizeType::Custom](../../slidesizetype/)，並設定 [Orientation](../../orientation/)。

## 另請參閱

* Enum [SlideSizeType](../../slidesizetype/)
* Enum [SlideSizeScaleType](../../slidesizescaletype/)
* 類別 [ISlideSize](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)