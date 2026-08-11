---
title: get_AllCustomXmlParts()
second_title: مرجع API Aspose.Slides برای C++
description: تمام بخش‌های داده سفارشی را در ارائه برمی‌گرداند. فقط-خواندنی ICustomXmlPart[].
type: docs
weight: 287
url: /fa/aspose.slides/presentation/get_allcustomxmlparts/
---
## Presentation::get_AllCustomXmlParts() متد


تمام بخش‌های داده سفارشی را در presentaion برمی‌گرداند. فقط خواندنی [ICustomXmlPart](../../icustomxmlpart/)[].

```cpp
System::ArrayPtr<System::SharedPtr<ICustomXmlPart>> Aspose::Slides::Presentation::get_AllCustomXmlParts() override
```

## توضیحات


مثال‌های زیر نشان می‌دهند چگونه تمام بخش‌های xml سفارشی را از PowerPoint [Presentation](../) پاک کنید. 
```cpp
auto pres = System::MakeObject<Presentation>(u"PresentationWithCustomXml.pptx");

// تمام بخش‌های XML سفارشی را پیمایش کنید
for (System::SharedPtr<ICustomXmlPart> item : pres->get_AllCustomXmlParts())
{
    item->Remove();
}

pres->Save(u"out.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف‌نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ICustomXmlPart](../../icustomxmlpart/)
* کلاس [Presentation](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)