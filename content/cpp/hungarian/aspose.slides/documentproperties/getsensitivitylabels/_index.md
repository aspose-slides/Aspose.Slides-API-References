---
title: GetSensitivityLabels()
second_title: Aspose.Slides C++ API Referencia
description: Az egyéni dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata) egy tömböt kap az érzékenységi címkékkel.
type: docs
weight: 859
url: /hu/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() metódus


Az egyéni dokumentumtulajdonságokból (Microsoft Information Protection SDK Metadata) kap egy tömböt az érzékenységi címkékkel.

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## Megjegyzések


Az alábbi kód bemutatja, hogyan lehet az egyéni dokumentumtulajdonságokból az érzékenységi címke információkat áthelyezni a modern SensitivityLabels gyűjteménybe:
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Szerezze be az érzékenységi címkéket az egyéni dokumentumtulajdonságokból
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Címke hozzáadása a gyűjteményhez
    // Itt ellenőrizheti a címkeinformációk érvényességét (a címke elérhető stb.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISensitivityLabel](../../isensitivitylabel/)
* Osztály [DocumentProperties](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)