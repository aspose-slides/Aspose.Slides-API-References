---
title: WriteAsSvg()
second_title: Aspose.Slides برای مرجع API C++
description: محتوای اسلاید را به‌عنوان یک فایل SVG ذخیره می‌کند.
type: docs
weight: 157
url: /fa/aspose.slides/slide/writeassvg/
---
## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>) متد

محتوای اسلاید را به‌عنوان یک فایل SVG ذخیره می‌کند.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان هدف |

## یادداشت‌ها

مثال کد زیر نشان می‌دهد چگونه اولین اسلاید یک ارائه PowerPoint را به یک فایل SVG تبدیل کنید. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

// اولین اسلاید را به عنوان یک فایل SVG ذخیره می‌کند
pres->get_Slide(0)->WriteAsSvg(fileStream);
```

## Slide::WriteAsSvg(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<Export::ISVGOptions\>) متد

محتوای اسلاید را به‌عنوان یک فایل SVG ذخیره می‌کند.

```cpp
void Aspose::Slides::Slide::WriteAsSvg(System::SharedPtr<System::IO::Stream> stream, System::SharedPtr<Export::ISVGOptions> svgOptions) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان هدف |
| svgOptions | [System::SharedPtr](../../../system/sharedptr/)\<[Export::ISVGOptions](../../../aspose.slides.export/isvgoptions/)\> | گزینه‌های تولید SVG |

## یادداشت‌ها

مثال کد زیر نشان می‌دهد چگونه اولین اسلاید یک ارائه PowerPoint را به یک فایل SVG با گزینه‌ها تبدیل کنید. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.svg");

auto options = System::MakeObject<SVGOptions>();
options->set_VectorizeText(true);

// اولین اسلاید را به عنوان یک فایل SVG ذخیره می‌کند
pres->get_Slide(0)->WriteAsSvg(fileStream, options);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [Slide](../)
* کلاس [ISVGOptions](../../../aspose.slides.export/isvgoptions/)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)