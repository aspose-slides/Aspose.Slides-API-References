---
title: ToPng()
second_title: Reference API Aspose.Slides pro C++
description: Převádí vstupní prezentaci na sadu obrázků ve formátu PNG.  Pokud je zadáno výstupní jméno souboru jako \"myPath/myFilename.png\", výsledek bude uložen jako sada souborů \"myPath/myFilename_N.png\", kde N je číslo snímku.
type: docs
weight: 53
url: /cs/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) metoda

Převádí vstupní prezentaci na sadu obrázků ve formátu PNG.

 Pokud je zadáno výstupní jméno souboru jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename_N.png", kde N je číslo snímku.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Vstupní prezentace. |
| outputFileName | [System::String](../../../system/string/) | Výstupní jméno souboru. |
## Poznámky




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) metoda

Převádí vstupní prezentaci na sadu obrázků ve formátu PNG.

 Pokud je zadáno výstupní jméno souboru jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename_N.png", kde N je číslo snímku.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
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
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) metoda

Převádí vstupní prezentaci na sadu obrázků ve formátu PNG.

 Pokud je zadáno výstupní jméno souboru jako "myPath/myFilename.png", výsledek bude uložen jako sada souborů "myPath/myFilename_N.png", kde N je číslo snímku.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Vstupní prezentace. |
| outputFileName | [System::String](../../../system/string/) | Výstupní jméno souboru. |
| scale | **float** | Škálovací faktor aplikovaný na výstupní obrázky vzhledem k původní velikosti snímku. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Možnosti vykreslování. |
## Poznámky




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [Presentation](../../../aspose.slides/presentation/)
* Třída [String](../../../system/string/)
* Třída [Convert](../)
* Třída [Size](../../../system.drawing/size/)
* Třída [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Jmenný prostor [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)