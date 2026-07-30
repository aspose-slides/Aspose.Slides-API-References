---
title: get_SensitivityLabels()
second_title: Aspose.Slides pro C++ – reference API
description: Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace. Pouze pro čtení ISensitivityLabelCollection.
type: docs
weight: 378
url: /cs/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() metoda

Vrací kolekci štítků citlivosti aplikovaných na dokument prezentace. Pouze pro čtení [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Poznámky

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Vytiskne aplikované štítky
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Přidá nový štítek
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Získá ID štítku citlivosti ze zásady
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Získá identifikátor Azure AD site ze zásady
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* třída [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* třída [Presentation](../)
* jmenný prostor [Aspose::Slides](../../)
* knihovna [Aspose.Slides](../../../)