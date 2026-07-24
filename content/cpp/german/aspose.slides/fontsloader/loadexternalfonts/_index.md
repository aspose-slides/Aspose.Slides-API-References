---
title: LoadExternalFonts()
second_title: Aspose.Slides für C++ API-Referenz
description: Fügt zusätzliche Ordner hinzu, um nach Schriftarten zu suchen.
type: docs
weight: 1
url: /de/aspose.slides/fontsloader/loadexternalfonts/
---
## FontsLoader::LoadExternalFonts(System::ArrayPtr\<System::String\>) Methode


Fügt zusätzliche Ordner hinzu, in denen nach Schriftarten gesucht wird.

```cpp
static void Aspose::Slides::FontsLoader::LoadExternalFonts(System::ArrayPtr<System::String> directories)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| directories | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | Verzeichnisse, aus denen zusätzliche Schriftarten gelesen werden. |
## Bemerkungen



Das folgende Beispiel zeigt, wie benutzerdefinierte Schriftarten aus einer .TTF-Datei geladen werden. 
```cpp
// Der Pfad zum Dokumentenverzeichnis.
System::String dataDir = u"C:\\";

// Ordner, in denen nach Schriftarten gesucht wird
System::ArrayPtr<System::String> folders = System::MakeArray<System::String>({dataDir});

// Lade die benutzerdefinierten Schriftarten aus dem Ordner
FontsLoader::LoadExternalFonts(folders);

// Führe einige Arbeiten aus und rendere die Präsentation/Slides
auto presentation = System::MakeObject<Presentation>(dataDir + u"DefaultFonts.pptx");
presentation->Save(dataDir + u"NewFonts_out.pptx", SaveFormat::Pptx);

// Lösche den Schriftarten-Cache
FontsLoader::ClearCache();
```

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Klasse [String](../../../system/string/)
* Klasse [FontsLoader](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)