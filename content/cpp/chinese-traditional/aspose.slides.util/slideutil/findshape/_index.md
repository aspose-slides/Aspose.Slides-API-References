---
title: FindShape()
second_title: Aspose.Slides for C++ API 參考
description: 在 PPTX 簡報中依替代文字尋找形狀。
type: docs
weight: 1
url: /zh-hant/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) 方法

在 PPTX 投影片中透過替代文字尋找形狀。

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | 已掃描的簡報。 |
| altText | [System::String](../../../system/string/) | 形狀的替代文字。 |

### 返回值

[Shape](../../../aspose.slides/shape/) 或 null。

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) 方法

在 PPTX 簡報的投影片上依替代文字尋找形狀。

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | 已掃描的投影片。 |
| altText | [System::String](../../../system/string/) | 形狀的替代文字。 |

### 返回值

[Shape](../../../aspose.slides/shape/) 或 null。

## 另見

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../../../aspose.slides/ishape/)
* 類別 [IPresentation](../../../aspose.slides/ipresentation/)
* 類別 [String](../../../system/string/)
* 類別 [SlideUtil](../)
* 類別 [IBaseSlide](../../../aspose.slides/ibaseslide/)
* 命名空間 [Aspose::Slides::Util](../../)
* 函式庫 [Aspose.Slides](../../../)