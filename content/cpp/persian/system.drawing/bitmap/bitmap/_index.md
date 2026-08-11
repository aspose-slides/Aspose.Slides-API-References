---
title: Bitmap()
second_title: مرجع API Aspose.Slides برای C++
description: یک شیء Bitmap جدید را از تصویر موجود مشخص‌شده می‌سازد.
type: docs
weight: 1
url: /fa/system.drawing/bitmap/bitmap/
---
## Bitmap::Bitmap(const SharedPtr\<Image\>\&) سازنده

یک شیء جدید [Bitmap](../) را از تصویر موجود مشخص‌شده می‌سازد.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویر موجود برای ایجاد تصویر بیت‌مپ |
 
## Bitmap::Bitmap(const SharedPtr\<System::IO::Stream\>\&, bool) سازنده

یک شیء جدید [Bitmap](../) را از جریان مشخص‌شده می‌سازد.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<System::IO::Stream> &stream, bool useIcm=false)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | جریان حاوی داده‌های تصویر |
| useIcm | **bool** | نادیده |
 
## Bitmap::Bitmap(const String\&) سازنده

یک شیء جدید [Bitmap](../) را از فایل مشخص‌شده می‌سازد.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | نام فایلی که حاوی داده‌های تصویر است |
 
## Bitmap::Bitmap(const String\&, bool) سازنده

یک شیء جدید [Bitmap](../) را از فایل مشخص‌شده می‌سازد.

```cpp
System::Drawing::Bitmap::Bitmap(const String &filename, bool useIcm)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| filename | const [String](../../../system/string/)\& | نام فایلی که حاوی داده‌های تصویر است |
| useIcm | **bool** | نادیده |
 
## Bitmap::Bitmap(int, int, Imaging::PixelFormat) سازنده

یک شیء جدید [Bitmap](../) می‌سازد که نمایانگر یک تصویر بیت‌مپ با عرض، ارتفاع، فرمت پیکسل و داده‌های پیکسل مشخص‌شده است.

```cpp
System::Drawing::Bitmap::Bitmap(int width, int height, Imaging::PixelFormat format=Imaging::PixelFormat::Format32bppArgb)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| width | int | عرض تصویر |
| height | int | ارتفاع تصویر |
| format | [Imaging::PixelFormat](../../../system.drawing.imaging/pixelformat/) | فرمت پیکسل تصویر |
 
## Bitmap::Bitmap(const SharedPtr\<Image\>\&, const Size\&) سازنده

یک شیء جدید [Bitmap](../) را از تصویر موجود مشخص‌شده می‌سازد که به اندازه مشخص مقیاس داده شده است.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, const Size &size)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویر موجود برای ایجاد تصویر بیت‌مپ |
| size | const [Size](../../size/)\& | اندازه تصویر جدید |
 
## Bitmap::Bitmap(const SharedPtr\<Image\>\&, int, int) سازنده

یک شیء جدید [Bitmap](../) را از تصویر موجود مشخص‌شده می‌سازد که عرض و ارتفاع آن به مقادیر مشخص مقیاس داده شده‌اند.

```cpp
System::Drawing::Bitmap::Bitmap(const SharedPtr<Image> &original, int width, int height)
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| original | const [SharedPtr](../../../system/sharedptr/)\<[Image](../../image/)\>\& | تصویر موجود برای ایجاد تصویر بیت‌مپ |
| width | int | عرض تصویر جدید |
| height | int | ارتفاع تصویر جدید |
 
## مراجع

* enum [PixelFormat](../../../system.drawing.imaging/pixelformat/)
* typedef [SharedPtr](../../../system/sharedptr/)
* class [Image](../../image/)
* class [Bitmap](../)
* class [Stream](../../../system.io/stream/)
* class [String](../../../system/string/)
* class [Size](../../size/)
* namespace [System::Drawing](../../)
* کتابخانه [Aspose.Slides](../../../)