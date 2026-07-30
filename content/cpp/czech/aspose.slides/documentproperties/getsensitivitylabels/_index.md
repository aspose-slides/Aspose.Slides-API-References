---
title: GetSensitivityLabels()
second_title: Aspose.Slides pro C++ API Reference
description: Vrací pole citlivých štítků z vlastních vlastností dokumentu (Microsoft Information Protection SDK Metadata).
type: docs
weight: 859
url: /cs/aspose.slides/documentproperties/getsensitivitylabels/
---
## DocumentProperties::GetSensitivityLabels() metoda

Vrací pole sensitivity labels z vlastních vlastností dokumentu (Microsoft Information Protection SDK Metadata).

```cpp
System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::DocumentProperties::GetSensitivityLabels() override
```

## Poznámky

Následující kód ukazuje, jak přesunout informace o sensitivity labels z vlastních vlastností dokumentu do moderní kolekce SensitivityLabels:

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Získat citlivé štítky z vlastních vlastností dokumentu
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Přidat štítek do kolekce
    // Zde můžete přidat kontrolu platnosti informací o štítku (štítek je dostupný, atd.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISensitivityLabel](../../isensitivitylabel/)
* Třída [DocumentProperties](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)