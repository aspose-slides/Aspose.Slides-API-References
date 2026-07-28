---
title: GetSensitivityLabels()
second_title: Aspose.Slides C++ API Referencia
description: Visszaad egy tömböt a szenzitivitási címkékkel a saját dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /hu/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() metódus

Visszaad egy tömböt a szenzitivitási címkékkel a saját dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## Megjegyzés

Az alábbi kód bemutatja, hogyan lehet átmozgatni a szenzitivitási címke információkat a saját dokumentumtulajdonságokból a modern SensitivityLabels gyűjteménybe: 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Szerezze meg a szenzitivitási címkéket a saját dokumentumtulajdonságokból
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Címke hozzáadása a gyűjteményhez
    // Itt ellenőrizheti a címke információk érvényességét (a címke elérhető, stb.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISensitivityLabel](../../isensitivitylabel/)
* Osztály [IDocumentProperties](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)