---
title: get_SensitivityLabels()
second_title: C++ API Referansı için Aspose.Slides
description: Sunum belgesine uygulanan hassasiyet etiketlerinin koleksiyonunu döndürür. Yalnızca okunabilir ISensitivityLabelCollection.
type: docs
weight: 378
url: /tr/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() metodu

Sunum belgesine uygulanan hassasiyet etiketlerinin koleksiyonunu döndürür. Yalnızca okunabilir [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Açıklamalar

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Uygulanan etiketleri yazdır
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Yeni etiketi ekle
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Politikadan hassasiyet etiketi kimliğini al
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Politikadan Azure AD site tanımlayıcısını al
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Diğer Bağlantılar

* Typedef [SharedPtr](../../../system/sharedptr/)
* Sınıf [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Sınıf [Presentation](../)
* Ad Uzayı [Aspose::Slides](../../)
* Kütüphane [Aspose.Slides](../../../)