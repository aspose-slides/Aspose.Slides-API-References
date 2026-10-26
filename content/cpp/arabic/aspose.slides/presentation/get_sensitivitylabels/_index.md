---
title: get_SensitivityLabels()
second_title: Aspose.Slides لمرجع API الخاص بـ C++
description: يرجع مجموعة علامات الحساسية المطبقة على مستند العرض. للقراءة فقط ISensitivityLabelCollection.
type: docs
weight: 378
url: /ar/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() طريقة

يرجع مجموعة العلامات الحساسة المطبقة على مستند العرض. للقراءة فقط [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## ملاحظات

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// طباعة العلامات المطبقة
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// إضافة العلامة الجديدة
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// الحصول على معرف العلامة الحساسة من السياسة
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// الحصول على معرف موقع Azure AD من السياسة
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* تعريف نوع [SharedPtr](../../../system/sharedptr/)
* فئة [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* فئة [Presentation](../)
* مساحة الاسم [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)