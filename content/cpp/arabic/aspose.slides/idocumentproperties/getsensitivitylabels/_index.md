---
title: GetSensitivityLabels()
second_title: مرجع API لـ Aspose.Slides للغة C++
description: يحصل على مصفوفة من علامات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /ar/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() طريقة

يحصل على مصفوفة من علامات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## ملاحظات

يعرض الشيفرة التالية كيفية نقل معلومات علامات الحساسية من خصائص المستند المخصصة إلى مجموعة SensitivityLabels الحديثة:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// الحصول على علامات الحساسية من خصائص المستند المخصصة
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // إضافة علامة إلى المجموعة
    // هنا يمكنك إضافة فحص لصحة معلومات العلامة (العلامة متاحة، إلخ)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## انظر أيضًا

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* فئة [ISensitivityLabel](../../isensitivitylabel/)
* فئة [IDocumentProperties](../)
* مساحة الاسم [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)