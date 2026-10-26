---
title: WriteAsEmf()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحفظ محتوى الشريحة كملف EMF.
type: docs
weight: 170
url: /ar/aspose.slides/slide/writeasemf/
---
## Slide::WriteAsEmf(System::SharedPtr\<System::IO::Stream\>) طريقة

يحفظ محتوى الشريحة كملف EMF.

```cpp
void Aspose::Slides::Slide::WriteAsEmf(System::SharedPtr<System::IO::Stream> stream) override
```

### المعلمات

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | تدفق الهدف |
## الملاحظات

يوضح المثال التالي كيفية تحويل الشريحة الأولى من عرض PowerPoint إلى ملف ميتا.
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");

System::SharedPtr<System::IO::Stream> fileStream = System::IO::File::Create(u"slide_1.emf");

// يحفظ الشريحة الأولى كملف ميتا
pres->get_Slide(0)->WriteAsEmf(fileStream);
```

## انظر أيضًا

* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [Stream](../../../system.io/stream/)
* فئة [Slide](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)