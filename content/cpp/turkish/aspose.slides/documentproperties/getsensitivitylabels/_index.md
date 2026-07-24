---
title: GetSensitivityLabels()
second_title: Aspose.Slides for C++ API Referansı
description: Özel belge özelliklerinden (Microsoft Information Protection SDK Metadata) duyarlılık etiketlerinin bir dizisini alır.
type: docs
weight: 859
url: /tr/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() metodu


Özel belge özelliklerinden duyarlılık etiketlerinin bir dizisini alır (Microsoft Information Protection SDK Metadata).

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
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
    // Burada etiket bilgilerinin geçerliliğini kontrol edebilirsiniz (etiket mevcut, vb.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Ayrıca Bakınız

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISensitivityLabel](../../isensitivitylabel/)
* Sınıf [DocumentProperties](../)
* Ad alanı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)