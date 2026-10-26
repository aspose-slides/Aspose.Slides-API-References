---
title: GetSensitivityLabels()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Získá pole citlivostních štítků z vlastních vlastností dokumentu (Microsoft Information Protection SDK Metadata).
type: docs
weight: 872
url: /cs/aspose.slides/idocumentproperties/getsensitivitylabels/
---
## IDocumentProperties::GetSensitivityLabels() metoda

Získá pole citlivostních štítků z vlastních vlastností dokumentu (Microsoft Information Protection SDK Metadata).

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISensitivityLabel>> Aspose::Slides::IDocumentProperties::GetSensitivityLabels()=0
```

## Poznámky

Následující kód ukazuje, jak přesunout informace o citlivostních štítcích z vlastních vlastností dokumentu do moderní kolekce SensitivityLabels:

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"SomePresentation.pptx");

// Získat citlivostní štítky z vlastních vlastností dokumentu
auto mipSensitivityLabels = pres->get_DocumentProperties()->GetSensitivityLabels();

auto sensitivityLabels = pres->get_SensitivityLabels();
for (auto&& sensitivityLabel : mipSensitivityLabels)
{
    // Přidat štítek do kolekce
    // Zde můžete přidat kontrolu platnosti informací o štítku (štítek je k dispozici, atd.)
    sensitivityLabels->Add(sensitivityLabel);
}

pres->Save(u"SensitivityLabel.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISensitivityLabel](../../isensitivitylabel/)
* Třída [IDocumentProperties](../)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)