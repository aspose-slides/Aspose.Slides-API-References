---
title: get_SensitivityLabels()
second_title: مرجع API Aspose.Slides برای C++
description: مجموعه برچسب‌های حساسیتی که بر روی سند ارائه اعمال شده‌اند را برمی‌گرداند. فقط خواندنی ISensitivityLabelCollection.
type: docs
weight: 378
url: /fa/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() متد

مجموعه برچسب‌های حساسیت اعمال شده بر روی سند ارائه را برمی‌گرداند. فقط خواندنی [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## توضیحات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// چاپ برچسب‌های اعمال شده
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// افزودن برچسب جدید
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// دریافت شناسه برچسب حساسیت از سیاست
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// دریافت شناسه سایت Azure AD از سیاست
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## موارد مرتبط

* Typedef [SharedPtr](../../../system/sharedptr/)
* کلاس [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* کلاس [Presentation](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)