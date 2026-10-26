---
title: ToJpeg()
second_title: Aspose.Slides voor C++ API-referentie
description: Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen.  Als de bestandsnaam voor de uitvoer wordt opgegeven als \"myPath/myFilename.jpeg\", wordt het resultaat opgeslagen als een reeks bestanden \"myPath/myFilename_N.jpeg\", waarbij N een slide-nummer is.
type: docs
weight: 40
url: /nl/aspose.slides.lowcode/convert/tojpeg/
---
## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String) methode


Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. 

 Als de bestandsnaam voor de uitvoer wordt opgegeven als \"myPath/myFilename.jpeg\", wordt het resultaat opgeslagen als een reeks bestanden \"myPath/myFilename_N.jpeg\", waarbij N een slide-nummer is.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | De invoerpresentatie. |
| outputFileName | [System::String](../../../system/string/) | De bestandsnaam voor de uitvoer. |
## Opmerkingen




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg");
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) methode


Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. 

 Als de bestandsnaam voor de uitvoer wordt opgegeven als \"myPath/myFilename.jpeg\", wordt het resultaat opgeslagen als een reeks bestanden \"myPath/myFilename_N.jpeg\", waarbij N een slide-nummer is.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | De invoerpresentatie |
| outputFileName | [System::String](../../../system/string/) | De bestandsnaam voor de uitvoer. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | De grootte van elke gegenereerde afbeelding. |
## Opmerkingen 




```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", System::Drawing::Size(720, 540));
```

## Convert::ToJpeg(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) methode


Converteert de invoerpresentatie naar een reeks JPEG-afbeeldingen. 

 Als de bestandsnaam voor de uitvoer wordt opgegeven als \"myPath/myFilename.jpeg\", wordt het resultaat opgeslagen als een reeks bestanden \"myPath/myFilename_N.jpeg\", waarbij N een slide-nummer is.

```cpp
static void Aspose::Slides::LowCode::Convert::ToJpeg(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | De invoerpresentatie. |
| outputFileName | [System::String](../../../system/string/) | De bestandsnaam voor de uitvoer. |
| scale | **float** | De schaalfactor die wordt toegepast op de uitvoerafbeeldingen ten opzichte van de oorspronkelijke slide-grootte. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | De renderopties. |
## Opmerkingen 




```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToJpeg(pres, u"presImage.jpeg", 2.0f, options);
```

## Zie ook

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Presentation](../../../aspose.slides/presentation/)
* Class [String](../../../system/string/)
* Class [Convert](../)
* Class [Size](../../../system.drawing/size/)
* Class [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namespace [Aspose::Slides::LowCode](../../)
* Library [Aspose.Slides](../../../)