---
title: get_SensitivityLabels()
second_title: Aspose.Slides برای C++ مرجع API
description: مجموعه برچسب‌های حساسیتی که به سند ارائه اعمال شده‌اند را برمی‌گرداند. فقط خواندنی ISensitivityLabelCollection.
type: docs
weight: 391
url: /fa/aspose.slides/ipresentation/get_sensitivitylabels/
---
## IPresentation::get_SensitivityLabels() متد


مجموعه برچسب‌های حساسیتی که به سند ارائه اعمال شده‌اند را بر می‌گرداند. فقط خواندنی [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
virtual System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::IPresentation::get_SensitivityLabels()=0
```

## ملاحظات



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
// دریافت شناسه برچسب حساسیتی از سیاست
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// دریافت شناسه سایت Azure AD از سیاست
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## موارد دیگر

* تعریف‌نوع [SharedPtr](../../../system/sharedptr/)
* کلاس [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* کلاس [IPresentation](../)
* فضای‌نام [Aspose::Slides](../../)
* کتابخانه [Aspose.Slides](../../../)