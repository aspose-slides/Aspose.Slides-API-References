---
title: get_DocumentLevelFontSources()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt Quellen für externe Schriftarten an, die in der Präsentation verwendet werden sollen. Diese Schriftarten stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt.
type: docs
weight: 209
url: /de/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() Methode

Gibt Quellen für externe Schriftarten an, die in der Präsentation verwendet werden sollen. Diese Schriftarten stehen der Präsentation während ihrer gesamten Lebensdauer zur Verfügung und werden nicht mit anderen Präsentationen geteilt.

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## Hinweise

Das folgende Beispiel zeigt, wie benutzerdefinierte Schriftarten angegeben werden, die mit PowerPoint [Presentation](../../presentation/) verwendet werden.
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// Arbeiten mit der Präsentation
// CustomFont1, CustomFont2 sowie Schriftarten aus den Ordnern assets\fonts & global\fonts und deren Unterordnern stehen der Präsentation zur Verfügung
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IFontSources](../../ifontsources/)
* Klasse [LoadOptions](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)