---
title: ToJpeg()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertiert die Eingabepäsentation in eine Menge von JPEG-Format-Bildern. Wenn der Ausgabedateiname als \"myPath/myFilename.jpeg\" angegeben wird, wird das Ergebnis als Menge von \"myPath/myFilename_N.jpeg\"-Dateien gespeichert, wobei N die Foliennummer ist.
type: docs
weight: 40
url: /de/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) Methode

Konvertiert die Eingabepäsentation in eine Menge von JPEG-Format-Bildern.  

Wenn der Ausgabedateiname als \"myPath/myFilename.jpeg\" angegeben wird, wird das Ergebnis als Menge von \"myPath/myFilename_N.jpeg\"-Dateien gespeichert, wobei N die Foliennummer ist.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Die Eingabepäsentation. |
| outputFileName | [System::String](../../../system/string/) | Der Ausgabedateiname. |
## Hinweise

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) Methode

Konvertiert die Eingabepäsentation in eine Menge von JPEG-Format-Bildern.  

Wenn der Ausgabedateiname als \"myPath/myFilename.jpeg\" angegeben wird, wird das Ergebnis als Menge von \"myPath/myFilename_N.jpeg\"-Dateien gespeichert, wobei N die Foliennummer ist.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Die Eingabepäsentation |
| outputFileName | [System::String](../../../system/string/) | Der Ausgabedateiname. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Die Größe jedes erzeugten Bildes. |
## Hinweise

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) Methode

Konvertiert die Eingabepäsentation in eine Menge von JPEG-Format-Bildern.  

Wenn der Ausgabedateiname als \"myPath/myFilename.jpeg\" angegeben wird, wird das Ergebnis als Menge von \"myPath/myFilename_N.jpeg\"-Dateien gespeichert, wobei N die Foliennummer ist.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Die Eingabepäsentation. |
| outputFileName | [System::String](../../../system/string/) | Der Ausgabedateiname. |
| scale | **float** | Der Skalierungsfaktor, der auf die Ausgabebilder im Vergleich zur Originalfoliengröße angewendet wird. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Die Rendering-Optionen. |
## Hinweise

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
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