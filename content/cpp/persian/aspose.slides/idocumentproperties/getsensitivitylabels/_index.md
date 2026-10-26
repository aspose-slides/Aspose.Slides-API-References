---
title: GetSensitivityLabels()
second_title: Aspose.Slides برای C++ مرجع API
description: یک آرایه از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند (Microsoft Information Protection SDK Metadata) دریافت می‌کند.
type: docs
weight: 872
url: /fa/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() متد

یک آرایه از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند (Microsoft Information Protection SDK Metadata) دریافت می‌کند.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## توضیحات

کد زیر نشان می‌دهد چگونه اطلاعات برچسب‌های حساسیت را از ویژگی‌های سفارشی سند به مجموعهٔ مدرن SensitivityLabels منتقل کنید:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// دریافت برچسب‌های حساسیت از ویژگی‌های سفارشی سند
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // برچسب را به مجموعه اضافه کنید
    // در اینجا می‌توانید بررسی برای صحت اطلاعات برچسب (در دسترس بودن برچسب و غیره) را اضافه کنید
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## مراجع

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISensitivityLabel](../../isensitivitylabel/)
* کلاس [IDocumentProperties](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)