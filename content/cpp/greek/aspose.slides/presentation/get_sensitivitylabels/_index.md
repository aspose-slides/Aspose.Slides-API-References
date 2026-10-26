---
title: get_SensitivityLabels()
second_title: Aspose.Slides για C++ API Αναφορά
description: Επιστρέφει τη συλλογή των ετικετών ευαισθησίας που εφαρμόζονται στο έγγραφο παρουσίασης. Μόνο για ανάγνωση ISensitivityLabelCollection.
type: docs
weight: 378
url: /el/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() μέθοδος

Επιστρέφει τη συλλογή των ετικετών ευαισθησίας που εφαρμόζονται στο έγγραφο παρουσίασης. Μόνο για ανάγνωση [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Σχόλια

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Εκτύπωση των εφαρμοσμένων ετικετών
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Προσθήκη της νέας ετικέτας
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Λήψη του αναγνωριστικού ετικέτας ευαισθησίας από την πολιτική
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Λήψη του αναγνωριστικού τοποθεσίας Azure AD από την πολιτική
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Δείτε επίσης

* Typedef [SharedPtr](../../../system/sharedptr/)
* Κλάση [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Κλάση [Presentation](../)
* Χώρος ονομάτων [Aspose::Slides](../../)
* Βιβλιοθήκη [Aspose.Slides](../../../)