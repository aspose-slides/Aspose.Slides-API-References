---
title: set_DocumentLevelFontSources()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica le origini dei font esterni da utilizzare nella presentazione. Questi font sono disponibili per la presentazione per tutta la sua durata e non sono condivisi con altre presentazioni
type: docs
weight: 222
url: /it/aspose.slides/loadoptions/set_documentlevelfontsources/
---
## LoadOptions::set_DocumentLevelFontSources(System::SharedPtr\<IFontSources\>) metodo

Specifica le origini dei font esterni da utilizzare nella presentazione. Questi font sono disponibili per la presentazione per tutta la sua durata e non sono condivisi con altre presentazioni

```cpp
void Aspose::Slides::LoadOptions::set_DocumentLevelFontSources(System::SharedPtr<IFontSources> value) override
```

## Osservazioni

Il seguente esempio mostra come specificare i font personalizzati utilizzati con PowerPoint [Presentation](../../presentation/).

```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// lavora con la presentazione
// CustomFont1, CustomFont2 così come i font dalle cartelle assets\fonts & global\fonts e dalle loro sottocartelle sono disponibili per la presentazione
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IFontSources](../../ifontsources/)
* Classe [LoadOptions](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)