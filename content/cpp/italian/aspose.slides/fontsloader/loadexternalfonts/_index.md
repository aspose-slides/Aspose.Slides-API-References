---
title: LoadExternalFonts()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge cartelle aggiuntive per cercare i caratteri.
type: docs
weight: 1
url: /it/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) method


Aggiunge cartelle aggiuntive per cercare i caratteri.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Directory da leggere per i caratteri aggiuntivi. |
## Osservazioni



L'esempio seguente mostra come caricare caratteri personalizzati da .TTF 
```cpp
// Il percorso della directory dei documenti.
System::String dataDir = u"C:\\";

// Cartelle per cercare i caratteri
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Carica i caratteri dalla directory dei caratteri personalizzati
FontsLoader::LoadExternalFonts(folders);

// Esegui alcune operazioni e rendi la presentazione/diapositive
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Pulisci la cache dei caratteri
FontsLoader::ClearCache();
```

## Vedi anche

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Classe [String](../../../system/string/)
* Classe [FontsLoader](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)