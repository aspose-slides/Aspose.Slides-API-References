---
title: ToPng()
second_title: Aspose.Slides for C++ API-referencia
description: Átalakítja a bemeneti prezentációt PNG formátumú képek halmazává.  Ha a kimeneti fájlnév \"myPath/myFilename.png\", az eredmény \"myPath/myFilename_N.png\" fájlok halmazaként lesz mentve, ahol N a dia száma.
type: docs
weight: 53
url: /hu/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) metódus


Átalakítja a bemeneti prezentációt PNG formátumú képek halmazává. 

Ha a kimeneti fájlnév „myPath/myFilename.png” formában van megadva, az eredmény „myPath/myFilename_N.png” fájlok halmazaként lesz mentve, ahol N a dia száma.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A bemeneti prezentáció. |
| outputFileName | [System::String](../../../system/string/) | A kimeneti fájlnév. |
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) metódus


Átalakítja a bemeneti prezentációt PNG formátumú képek halmazává. 

Ha a kimeneti fájlnév „myPath/myFilename.png” formában van megadva, az eredmény „myPath/myFilename_N.png” fájlok halmazaként lesz mentve, ahol N a dia száma.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A bemeneti prezentáció |
| outputFileName | [System::String](../../../system/string/) | A kimeneti fájlnév. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Az egyes generált képek mérete. |
## Megjegyzések




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) metódus


Átalakítja a bemeneti prezentációt PNG formátumú képek halmazává. 

Ha a kimeneti fájlnév „myPath/myFilename.png” formában van megadva, az eredmény „myPath/myFilename_N.png” fájlok halmazaként lesz mentve, ahol N a dia száma.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A bemeneti prezentáció. |
| outputFileName | [System::String](../../../system/string/) | A kimeneti fájlnév. |
| scale | **float** | A kimeneti képekre alkalmazott méretezési tényező az eredeti dia méretéhez képest. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | A renderelési beállítások. |
## Megjegyzések




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [Presentation](../../../aspose.slides/presentation/)
* Osztály [String](../../../system/string/)
* Osztály [Convert](../)
* Osztály [Size](../../../system.drawing/size/)
* Osztály [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Névtere [Aspose::Slides::LowCode](../../)
* Könyvtár [Aspose.Slides](../../../)