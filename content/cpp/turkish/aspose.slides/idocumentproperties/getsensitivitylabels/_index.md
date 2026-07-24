---
title: GetSensitivityLabels()
second_title: Aspose.Slides için C++ API Referansı
description: Özel belge özelliklerinden (Microsoft Information Protection SDK Metadata) duyarlılık etiketlerinin bir dizisini alır.
type: docs
weight: 872
url: /tr/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() yöntemi

Özel belge özelliklerinden (Microsoft Information Protection SDK Metadata) duyarlılık etiketlerinin bir dizisini alır.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```
## Açıklamalar

Aşağıdaki kod, duyarlılık etiketleri bilgisini özel belge özelliklerinden modern SensitivityLabels koleksiyonuna nasıl taşıyacağını gösterir:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Özel belge özelliklerinden duyarlılık etiketlerini al
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Etiketi koleksiyona ekle
    // Burada etiket bilgisinin geçerliliğini kontrol edebilirsiniz (etiket mevcut, vb.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```
## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISensitivityLabel](../../isensitivitylabel/)
* Sınıf [IDocumentProperties](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)