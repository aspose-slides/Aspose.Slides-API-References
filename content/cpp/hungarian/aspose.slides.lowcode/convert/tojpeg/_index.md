---
title: ToJpeg()
second_title: Aspose.Slides C++ API Referencia
description: Átalakítja a bemeneti bemutatót JPEG formátumú képek sorozatává. Ha a kimeneti fájlnév "myPath/myFilename.jpeg"-ként van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol N a dia száma.
type: docs
weight: 40
url: /hu/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) metódus

Átalakítja a bemeneti bemutatót JPEG formátumú képekké.

Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formátumban van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol N a dia száma.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A bemeneti bemutató. |
| outputFileName | [System::String](../../../system/string/) | A kimeneti fájlnév. |
## Megjegyzések

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) metódus

Átalakítja a bemeneti bemutatót JPEG formátumú képekké.

Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formátumban van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol N a dia száma.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A bemeneti bemutató |
| outputFileName | [System::String](../../../system/string/) | A kimeneti fájlnév. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Az egyes generált képek mérete. |
## Megjegyzések

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) metódus

Átalakítja a bemeneti bemutatót JPEG formátumú képekké.

Ha a kimeneti fájlnév "myPath/myFilename.jpeg" formátumban van megadva, az eredmény "myPath/myFilename_N.jpeg" fájlok sorozataként lesz mentve, ahol N a dia száma.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | A bemeneti bemutató. |
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
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [Presentation](../../../aspose.slides/presentation/)
* Osztály [String](../../../system/string/)
* Osztály [Convert](../)
* Osztály [Size](../../../system.drawing/size/)
* Osztály [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Névtér [Aspose::Slides::LowCode](../../)
* Könyvtár [Aspose.Slides](../../../)