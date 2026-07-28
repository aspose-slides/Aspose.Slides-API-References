---
title: get_SensitivityLabels()
second_title: Aspose.Slides C++ API referenciája
description: Visszaadja a prezentációs dokumentumra alkalmazott érzékenységi címkék gyűjteményét. Csak olvasás ISensitivityLabelCollection.
type: docs
weight: 378
url: /hu/aspose.slides/presentation/get_sensitivitylabels/
---
## Presentation::get_SensitivityLabels() metódus


Visszaadja a prezentációs dokumentumra alkalmazott érzékenységi címkék gyűjteményét. Csak olvasás [ISensitivityLabelCollection](../../isensitivitylabelcollection/).

```cpp
System::SharedPtr<ISensitivityLabelCollection> Aspose::Slides::Presentation::get_SensitivityLabels() override
```

## Megjegyzések



```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

System::SharedPtr<ISensitivityLabelCollection> sensitivityLabels = pres->get_SensitivityLabels();

// Kiírja a alkalmazott címkéket
for (auto&& sensitivityLabel : sensitivityLabels)
{
    System::Console::WriteLine(System::String(u"Label Id ") + sensitivityLabel->get_Id() + u" from Azure AD site " + sensitivityLabel->get_SiteId());
}

// Új címke hozzáadása
System::String labelIdString = u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}";
// Lekéri az érzékenységi címke azonosítóját a policy-ból
System::Guid siteIdGuid = System::Guid::Parse(u"{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}");
// Lekéri az Azure AD webhelyazonosítót a policy-ból
auto label = sensitivityLabels->Add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType::Privileged);
label->get_ContentMarkTypes()->Add(SensitivityLabelContentType::Footer);

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISensitivityLabelCollection](../../isensitivitylabelcollection/)
* Osztály [Presentation](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)