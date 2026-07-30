---
title: get_DocumentLevelFontSources()
second_title: Riferimento API di Aspose.Slides per C++
description: Specifica le sorgenti per i font esterni da utilizzare nella presentazione. Questi font sono disponibili per la presentazione per tutta la sua durata e non sono condivisi con altre presentazioni
type: docs
weight: 209
url: /it/aspose.slides/loadoptions/get_documentlevelfontsources/
---
## LoadOptions::get_DocumentLevelFontSources() metodo


Specifica le fonti per i caratteri esterni da utilizzare nella presentazione. Questi caratteri sono disponibili nella presentazione per tutta la sua durata e non sono condivisi con altre presentazioni

```cpp
System::SharedPtr<IFontSources> Aspose::Slides::LoadOptions::get_DocumentLevelFontSources() override
```

## Osservazioni


Il seguente esempio mostra come specificare i caratteri personalizzati utilizzati con PowerPoint [Presentation](../../presentation/). 
```cpp
System::ArrayPtr<uint8_t> memoryFont1 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont1.ttf");
System::ArrayPtr<uint8_t> memoryFont2 = System::IO::File::ReadAllBytes(u"customfonts\\CustomFont2.ttf");

System::SharedPtr<LoadOptions> loadOptions = System::MakeObject<LoadOptions>();
loadOptions->get_DocumentLevelFontSources()->set_FontFolders(System::MakeArray<System::String>({u"assets\\fonts", u"global\\fonts"}));
loadOptions->get_DocumentLevelFontSources()->set_MemoryFonts(System::MakeArray<System::ArrayPtr<uint8_t>>({memoryFont1, memoryFont2}));

auto presentation = System::MakeObject<Presentation>(u"MyPresentation.pptx", loadOptions);
// lavora con la presentazione
// CustomFont1, CustomFont2 così come i font dalle cartelle assets\fonts & global\fonts e le loro sottocartelle sono disponibili per la presentazione
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IFontSources](../../ifontsources/)
* Class [LoadOptions](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)