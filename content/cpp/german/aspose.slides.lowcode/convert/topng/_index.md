---
title: ToPng()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die Eingabepräsentation in einen Satz von PNG-Bildern.  Wenn der Ausgabedateiname als \"myPath/myFilename.png\" angegeben wird, wird das Ergebnis als eine Menge von Dateien \"myPath/myFilename_N.png\" gespeichert, wobei N die Foliennummer ist.
type: docs
weight: 53
url: /de/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) Methode


Konvertiert die Eingabepräsentation in einen Satz von PNG-Bildern. 

 Wenn der Ausgabedateiname als \"myPath/myFilename.png\" angegeben wird, wird das Ergebnis als eine Menge von Dateien \"myPath/myFilename_N.png\" gespeichert, wobei N die Foliennummer ist.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Die Eingabepräsentation. |
| outputFileName | [System::String](../../../system/string/) | Der Ausgabedateiname. |
## Bemerkungen




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) Methode


Konvertiert die Eingabepräsentation in einen Satz von PNG-Bildern. 

 Wenn der Ausgabedateiname als \"myPath/myFilename.png\" angegeben wird, wird das Ergebnis als eine Menge von Dateien \"myPath/myFilename_N.png\" gespeichert, wobei N die Foliennummer ist.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Die Eingabepräsentation |
| outputFileName | [System::String](../../../system/string/) | Der Ausgabedateiname. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Die Größe jedes erzeugten Bildes. |
## Bemerkungen




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) Methode


Konvertiert die Eingabepräsentation in einen Satz von PNG-Bildern. 

 Wenn der Ausgabedateiname als \"myPath/myFilename.png\" angegeben wird, wird das Ergebnis als eine Menge von Dateien \"myPath/myFilename_N.png\" gespeichert, wobei N die Foliennummer ist.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Die Eingabepräsentation. |
| outputFileName | [System::String](../../../system/string/) | Der Ausgabedateiname. |
| scale | **float** | Der Skalierungsfaktor, der auf die Ausgabebilder im Verhältnis zur Originalfoliengröße angewendet wird. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Die Rendering-Optionen. |
## Bemerkungen




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [String](../../../system/string/)
* Klasse [Convert](../)
* Klasse [Size](../../../system.drawing/size/)
* Klasse [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namensraum [Aspose::Slides::LowCode](../../)
* Bibliothek [Aspose.Slides](../../../)