---
title: Save()
second_title: مرجع API Aspose.Slides لـ C++
description: يحفظ الصورة إلى ملف.
type: docs
weight: 40
url: /ar/aspose.slides/iimage/save/
---
## IImage::Save(System::String) طريقة

يحفظ الصورة إلى ملف.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | المسار إلى الملف حيث سيتم حفظ الصورة. |

## IImage::Save(System::String, ImageFormat) طريقة

يحفظ الصورة إلى ملف بالصيغة المحددة.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | المسار إلى الملف حيث سيتم حفظ الصورة. |
| format | [ImageFormat](../../imageformat/) | صيغة الصورة. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat) طريقة

يحفظ الصورة إلى دفق بالصيغة المحددة.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | الدفق حيث سيتم حفظ الصورة. |
| format | [ImageFormat](../../imageformat/) | صيغة الصورة. |

## IImage::Save(System::String, ImageFormat, int32_t) طريقة

يحفظ الصورة إلى ملف بالصيغة والجودة المحددة.

```cpp
virtual void Aspose::Slides::IImage::Save(System::String filename, ImageFormat format, int32_t quality)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | [System::String](../../../system/string/) | المسار إلى الملف حيث سيتم حفظ الصورة. |
| format | [ImageFormat](../../imageformat/) | صيغة الصورة. |
| quality | **int32_t** | جودة الصورة المحفوظة (0 إلى 100).  

هذا المعامل يؤثر فقط على الحفظ في [ImageFormat::Jpeg](../../imageformat/)؛ بالنسبة لجميع الصيغ الأخرى، يتم تجاهله. |

## IImage::Save(System::SharedPtr\<System::IO::Stream\>, ImageFormat, int32_t) طريقة

يحفظ الصورة إلى دفق بالصيغة والجودة المحددة.

```cpp
virtual void Aspose::Slides::IImage::Save(System::SharedPtr<System::IO::Stream> stream, ImageFormat format, int32_t quality)=0
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | الدفق حيث سيتم حفظ الصورة. |
| format | [ImageFormat](../../imageformat/) | صيغة الصورة. |
| quality | **int32_t** | جودة الصورة المحفوظة (0 إلى 100).  

هذا المعامل يؤثر فقط على الحفظ في [ImageFormat::Jpeg](../../imageformat/)؛ بالنسبة لجميع الصيغ الأخرى، يتم تجاهله. |

## انظر أيضا

* عدد [ImageFormat](../../imageformat/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [String](../../../system/string/)
* فئة [IImage](../)
* فئة [Stream](../../../system.io/stream/)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)