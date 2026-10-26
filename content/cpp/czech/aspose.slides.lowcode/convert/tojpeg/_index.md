---
title: ToJpeg()
second_title: Aspose.Slides pro C++ API Reference
description: Převádí vstupní prezentaci na sadu obrázků ve formátu JPEG.  Pokud je zadáno výstupní jméno souboru jako \"myPath/myFilename.jpeg\", výsledek bude uložen jako sada souborů \"myPath/myFilename_N.jpeg\", kde N je číslo snímku.
type: docs
weight: 40
url: /cs/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) metoda

Převede vstupní prezentaci na sadu obrázků ve formátu JPEG. 

Pokud je zadáno výstupní jméno souboru jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename_N.jpeg", kde N je číslo snímku.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Vstupní prezentace. |
| outputFileName | [System::String](../../../system/string/) | Výstupní jméno souboru. |
## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) metoda

Převede vstupní prezentaci na sadu obrázků ve formátu JPEG. 

Pokud je zadáno výstupní jméno souboru jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename_N.jpeg", kde N je číslo snímku.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Vstupní prezentace |
| outputFileName | [System::String](../../../system/string/) | Výstupní jméno souboru. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Velikost každého vygenerovaného obrázku. |
## Poznámky

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) metoda

Převede vstupní prezentaci na sadu obrázků ve formátu JPEG. 

Pokud je zadáno výstupní jméno souboru jako "myPath/myFilename.jpeg", výsledek bude uložen jako sada souborů "myPath/myFilename_N.jpeg", kde N je číslo snímku.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Vstupní prezentace. |
| outputFileName | [System::String](../../../system/string/) | Výstupní jméno souboru. |
| scale | **float** | Měřítko aplikované na výstupní obrázky vzhledem k původní velikosti snímku. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
## Poznámky

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)