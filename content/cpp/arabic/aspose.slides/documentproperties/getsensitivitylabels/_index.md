---
title: GetSensitivityLabels()
second_title: Aspose.Slides لمرجع API للغة C++
description: يحصل على مصفوفة من تسميات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata).
type: docs
weight: 859
url: /ar/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() طريقة

يحصل على مصفوفة من تسميات الحساسية من خصائص المستند المخصصة (Microsoft Information Protection SDK Metadata).

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```
## ملاحظات

يعرض الكود التالي كيفية نقل معلومات تسميات الحساسية من خصائص المستند المخصصة إلى مجموعة SensitivityLabels الحديثة:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// احصل على تسميات الحساسية من خصائص المستند المخصصة
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // أضف التسمية إلى المجموعة
    // هنا يمكنك إضافة فحص لصحة معلومات التسمية (التسمية متاحة، إلخ)
    sensitivityLabels->Add(sensitivityLabel);
}
```
## انظر أيضًا

* تعريف [ArrayPtr](../../../system/arrayptr/)
* تعريف [SharedPtr](../../../system/sharedptr/)
* فئة [ISensitivityLabel](../../isensitivitylabel/)
* فئة [DocumentProperties](../)
* نطاق [Aspose::Slides](../../)
* مكتبة [Aspose.Slides](../../../)