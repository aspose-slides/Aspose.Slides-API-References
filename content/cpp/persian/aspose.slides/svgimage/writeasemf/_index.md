---
title: WriteAsEmf()
second_title: Aspose.Slides برای C++ مرجع API
description: تصویر SVG را به صورت فایل EMF ذخیره می‌کند.
type: docs
weight: 66
url: /fa/aspose.slides/svgimage/writeasemf/
---
## SvgImage::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) متد

تصویر SVG را به صورت فایل EMF ذخیره می‌کند.

```cpp
void Aspose::Slides::SvgImage::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان هدف |
## توضیحات

مثال زیر نشان می‌دهد چگونه تصویر SVG را به یک متافایل ذخیره کنید.
```cpp
// تصویر SVG جدید را ایجاد می‌کند
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));

// تصویر SVG را به صورت یک متافایل ذخیره می‌کند
auto fileStream = System::IO::File::OpenWrite(u"SvgAsEmf.emf");
svgImage->WriteAsEmf(fileStream);
```
 این نمونه نشان می‌دهد چگونه تصویر SVG را به عنوان یک متافایل به مجموعهٔ تصاویر ارائه اضافه کنید.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

// تصویر SVG جدید را ایجاد می‌کند
System::SharedPtr<ISvgImage> svgImage = System::MakeObject<SvgImage>(System::IO::File::ReadAllText(u"content.svg"));
auto memStream = System::MakeObject<System::IO::MemoryStream>();

// تصویر SVG را به عنوان یک متافایل ذخیره می‌کند
svgImage->WriteAsEmf(memStream);
// متافایل را به مجموعهٔ تصاویر اضافه می‌کند
pres->get_Images()->AddImage(memStream->ToArray());
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [SvgImage](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)