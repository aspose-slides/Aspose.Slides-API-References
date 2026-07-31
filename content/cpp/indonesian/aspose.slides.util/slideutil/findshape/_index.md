---
title: FindShape()
second_title: Referensi API Aspose.Slides untuk C++
description: Temukan shape berdasarkan teks alternatif dalam presentasi PPTX.
type: docs
weight: 1
url: /id/aspose.slides.util/slideutil/findshape/
---
## SlideUtil::FindShape(System::SharedPtr\<IPresentation\>, System::String) metode

Temukan shape berdasarkan teks alternatif dalam presentasi PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IPresentation> pres, System::String altText)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[IPresentation](../../../aspose.slides/ipresentation/)\> | Presentasi yang dipindai. |
| altText | [System::String](../../../system/string/) | Teks alternatif dari shape. |

### Nilai Kembali

[Shape](../../../aspose.slides/shape/) atau null.

## SlideUtil::FindShape(System::SharedPtr\<IBaseSlide\>, System::String) metode

Temukan shape berdasarkan teks alternatif pada slide dalam presentasi PPTX.

```cpp
static System::SharedPtr<IShape> Aspose::Slides::Util::SlideUtil::FindShape(System::SharedPtr<IBaseSlide> slide, System::String altText)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../../aspose.slides/ibaseslide/)\> | Slide yang dipindai. |
| altText | [System::String](../../../system/string/) | Teks alternatif dari shape. |

### Nilai Kembali

[Shape](../../../aspose.slides/shape/) atau null.

## Lihat Juga

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [IPresentation](../../../aspose.slides/ipresentation/)
* Class [String](../../../system/string/)
* Class [SlideUtil](../)
* Class [IBaseSlide](../../../aspose.slides/ibaseslide/)
* Namespace [Aspose::Slides::Util](../../)
* Library [Aspose.Slides](../../../)