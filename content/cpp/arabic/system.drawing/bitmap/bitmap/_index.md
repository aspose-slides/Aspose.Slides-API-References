---
title: Bitmap()
second_title: مرجع API Aspose.Slides للغة C++
description: يقوم بإنشاء كائن Bitmap جديد من الصورة الموجودة المحددة.
type: docs
weight: 1
url: /ar/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) المنشئ

إنشاء كائن [Bitmap](../) جديد من الصورة الموجودة المحددة.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة الموجودة لإنشاء صورة bitmap منها |

## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) المنشئ

إنشاء كائن [Bitmap](../) جديد من التدفق المحدد.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | تدفق يحتوي على بيانات الصورة |
| useIcm | **bool** | متجاهل |

## Bitmap::Bitmap(const String\&) المنشئ

إنشاء كائن [Bitmap](../) جديد من الملف المحدد.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | اسم الملف الذي يحتوي على بيانات الصورة |

## Bitmap::Bitmap(const String\&, bool) المنشئ

إنشاء كائن [Bitmap](../) جديد من الملف المحدد.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | اسم الملف الذي يحتوي على بيانات الصورة |
| useIcm | **bool** | متجاهل |

## Bitmap::Bitmap(int, int, Imaging::PixelFormat) المنشئ

إنشاء كائن [Bitmap](../) جديد يمثل صورة bitmap بالعرض والارتفاع وتنسيق البكسل والبيانات المحددة.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| width | int | عرض الصورة |
| height | int | ارتفاع الصورة |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | تنسيق بكسل الصورة |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) المنشئ

إنشاء كائن [Bitmap](../) جديد من الصورة الموجودة المحددة، مُعاد تحجيمه إلى الحجم المحدد.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة الموجودة لإنشاء صورة bitmap منها |
| size | const [Size](../../size/)\& | حجم الصورة الجديدة |

## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) المنشئ

إنشاء كائن [Bitmap](../) جديد من الصورة الموجودة المحددة، مع تعديل العرض والارتفاع إلى القيم المحددة.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### الوسائط

| المعامل | النوع | الوصف |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | الصورة الموجودة لإنشاء صورة bitmap منها |
| width | int | عرض الصورة الجديدة |
| height | int | ارتفاع الصورة الجديدة |

## أنظر أيضًا

* تعداد [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [Image](../../image/)
* فئة [Bitmap](../)
* فئة [Stream](../../../system.io/stream/)
* فئة [String](../../../system/string/)
* فئة [Size](../../size/)
* مساحة الاسم [System::Drawing](../../)
* مكتبة [Aspose.Slides](../../../)