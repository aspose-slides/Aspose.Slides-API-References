---
title: GetSensitivityLabels()
second_title: Aspose.Slides برای C++ مرجع API
description: یک آرایه از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند (Microsoft Information Protection SDK Metadata) دریافت می‌کند.
type: docs
weight: 859
url: /fa/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() متد

یک آرایه از برچسب‌های حساسیت را از ویژگی‌های سفارشی سند (Microsoft Information Protection SDK Metadata) دریافت می‌کند.

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## ملاحظات

کد زیر نشان می‌دهد چگونه اطلاعات برچسب‌های حساسیت را از ویژگی‌های سفارشی سند به مجموعه SensitivityLabels مدرن منتقل کنیم: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// دریافت برچسب‌های حساسیت از ویژگی‌های سفارشی سند
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // اضافه کردن برچسب به مجموعه
    // در اینجا می‌توانید بررسی‌ای برای اعتبار اطلاعات برچسب (در دسترس بودن برچسب و غیره) اضافه کنید
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* تعریف نوع [ArrayPtr](../../../system/arrayptr/)
* تعریف نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISensitivityLabel](../../isensitivitylabel/)
* کلاس [DocumentProperties](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)