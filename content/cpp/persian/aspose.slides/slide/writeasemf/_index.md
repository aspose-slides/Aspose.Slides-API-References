---
title: WriteAsEmf()
second_title: مرجع API Aspose.Slides برای C++
description: محتوای اسلاید را به عنوان یک فایل EMF ذخیره می‌کند.
type: docs
weight: 170
url: /fa/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) متد

محتوای اسلاید را به صورت یک فایل EMF ذخیره می‌کند.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### آرگومان‌ها

| پارامتر | نوع | توضیح |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | جریان هدف |
## ملاحظات

مثال کد زیر نشان می‌دهد چگونه می‌توان اولین اسلاید یک ارائه PowerPoint را به یک متافایل تبدیل کرد.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// اسلاید اول را به عنوان یک متافایل ذخیره می‌کند
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## موارد مرتبط

* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [Stream](../../../system.io/stream/)
* کلاس [Slide](../)
* فضای نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)