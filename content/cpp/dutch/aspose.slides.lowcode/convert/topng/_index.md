---
title: ToPng()
second_title: Aspose.Slides voor C++ API-Referentie
description: Converteert de invoerpresentatie naar een set PNG-formaat afbeeldingen.  Als de uitvoerbestandsnaam wordt opgegeven als "myPath/myFilename.png", wordt het resultaat opgeslagen als een set van "myPath/myFilename_N.png" bestanden, waarbij N een slide-nummer is.
type: docs
weight: 53
url: /nl/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) method


Converteert de invoerpresentatie naar een set PNG-formaat afbeeldingen. 

 Als de uitvoerbestandsnaam wordt opgegeven als \"myPath/myFilename.png\", wordt het resultaat opgeslagen als een set van \"myPath/myFilename_N.png\" bestanden, waarbij N een slide-nummer is.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | De invoerpresentatie. |
| outputFileName | [System::String](../../../system/string/) | De uitvoerbestandsnaam. |
## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) method


Converteert de invoerpresentatie naar een set PNG-formaat afbeeldingen. 

 Als de uitvoerbestandsnaam wordt opgegeven als \"myPath/myFilename.png\", wordt het resultaat opgeslagen als een set van \"myPath/myFilename_N.png\" bestanden, waarbij N een slide-nummer is.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | De invoerpresentatie |
| outputFileName | [System::String](../../../system/string/) | De uitvoerbestandsnaam. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | De grootte van elke gegenereerde afbeelding. |
## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) method


Converteert de invoerpresentatie naar een set PNG-formaat afbeeldingen. 

 Als de uitvoerbestandsnaam wordt opgegeven als \"myPath/myFilename.png\", wordt het resultaat opgeslagen als een set van \"myPath/myFilename_N.png\" bestanden, waarbij N een slide-nummer is.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | De invoerpresentatie. |
| outputFileName | [System::String](../../../system/string/) | De uitvoerbestandsnaam. |
| scale | **float** | De schaalfactor die wordt toegepast op de uitvoerafbeeldingen ten opzichte van de oorspronkelijke slide-grootte. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | De renderopties. |
## Opmerkingen




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [Presentation](../../../aspose.slides/presentation/)
* Klasse [String](../../../system/string/)
* Klasse [Convert](../)
* Klasse [Size](../../../system.drawing/size/)
* Klasse [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Naamruimte [Aspose::Slides::LowCode](../../)
* Bibliotheek [Aspose.Slides](../../../)