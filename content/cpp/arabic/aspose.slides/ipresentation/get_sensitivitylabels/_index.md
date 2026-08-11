---
title: get_SensitivityLabels()
second_title: مرجع API Aspose.Slides للغة C++
description: يعيد مجموعة تسميات الحساسية المطبقة على مستند العرض التقديمي. للقراءة فقط ISensitivityLabelCollection.
type: docs
weight: 391
url: /ar/aspose.slides/ipresentation/get_sensitivitylabels/
---
## IPresentation::get_SensitivityLabels() طريقة


يعيد مجموعة تسميات الحساسية المطبقة على مستند العرض التقديمي. للقراءة فقط [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
virtual System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::IPresentation::get_SensitivityLabels()=0
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// طباعة التسميات المطبقة
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// إضافة التسيمة الجديدة
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// الحصول على معرف تسيمة الحساسية من السياسة
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// الحصول على معرف موقع Azure AD من السياسة
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* فئة [IPresentation](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)