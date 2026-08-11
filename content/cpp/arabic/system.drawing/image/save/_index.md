---
title: Save()
second_title: Aspose.Slides لـ C++ مرجع API
description: يحفظ الصورة التي يمثلها الكائن الحالي إلى الملف المحدد بتنسيق PNG.
type: docs
weight: 1
url: /ar/system.drawing/image/save/
---
## Image::Save(const String\&) طريقة

يحفظ الصورة التي يمثلها الكائن الحالي في الملف المحدد بتنسيق PNG.

```cpp
void System::Drawing::Image::Save(const String &filename)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | اسم الملف لحفظ الصورة إليه |

## Image::Save(const String\&, const Imaging::ImageFormatPtr\&) طريقة

يحفظ الصورة التي يمثلها الكائن الحالي في الملف المحدد بالتنسيق المحدد.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageFormatPtr &format)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | اسم الملف لحفظ الصورة إليه |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | صيغة لحفظ الصورة |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageFormatPtr\&) طريقة

يحفظ الصورة التي يمثلها الكائن الحالي في الدفق المحدد بالتنسيق المحدد.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageFormatPtr &format)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | دفق لحفظ الصورة إليه |
| format | const [Imaging::ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)\& | صيغة لحفظ الصورة |

## Image::Save(const String\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) طريقة

يحفظ الصورة التي يمثلها الكائن الحالي في الملف المحدد باستخدام المشفّر والمعلمات المحددة للمشفّر.

```cpp
void System::Drawing::Image::Save(const String &filename, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | اسم الملف لحفظ الصورة إليه |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | المشفّر للاستخدام |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | معلمات المشفّر للاستخدام |

## Image::Save(const SharedPtr\<System::IO::Stream\>\&, const Imaging::ImageCodecInfoPtr\&, const Imaging::EncoderParametersPtr\&) طريقة

يحفظ الصورة التي يمثلها الكائن الحالي في الدفق المحدد باستخدام المشفّر والمعلمات المحددة للمشفّر.

```cpp
void System::Drawing::Image::Save(const SharedPtr<System::IO::Stream> &stream, const Imaging::ImageCodecInfoPtr &encoder, const Imaging::EncoderParametersPtr &encoder_params)
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | دفق لحفظ الصورة إليه |
| encoder | const [Imaging::ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)\& | المشفّر للاستخدام |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | معلمات المشفّر المستخدمة |

## انظر أيضا

* Typedef [ImageFormatPtr](../../../system.drawing.imaging/imageformatptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ImageCodecInfoPtr](../../../system.drawing.imaging/imagecodecinfoptr/)
* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* فئة [String](../../../system/string/)
* فئة [Image](../)
* فئة [Stream](../../../system.io/stream/)
* نطاق [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)