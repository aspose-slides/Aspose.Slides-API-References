---
title: get_SensitivityLabels()
second_title: Aspose.Slides för C++ API-referens
description: Returnerar samlingen av känslighetsetiketter som tillämpas på presentationsdokumentet. Skrivskyddad ISensitivityLabelCollection.
type: docs
weight: 378
url: /sv/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() metod


Returnerar samlingen av känslighetsetiketter som tillämpas på presentationsdokumentet. Skrivskyddad [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Anmärkningar



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Skriv ut de tillämpade etiketterna
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Lägg till den nya etiketten
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Hämta känslighetsetikettens Id från policyn
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Hämta Azure AD-platsens identifierare från policyn
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Se också

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klass [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Klass [Presentation](../)
* Namnrymd [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)