---
title: ToPng()
second_title: Aspose.Slides för C++ API-referens
description: Konverterar den inmatade presentationen till en uppsättning PNG-formatbilder.  Om utdatafilnamnet anges som \"myPath/myFilename.png\" sparas resultatet som en uppsättning av filerna \"myPath/myFilename_N.png\", där N är ett bildnummer.
type: docs
weight: 53
url: /sv/aspose.slides.lowcode/convert/topng/
---
## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String) metod

Konverterar den angivna presentationen till en uppsättning PNG-formatbilder.  

Om utdatafilnamnet anges som \"myPath/myFilename.png\" sparas resultatet som en uppsättning av filerna \"myPath/myFilename_N.png\", där N är ett bildnummer.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Den inmatade presentationen. |
| outputFileName | [System::String](../../../system/string/) | Utdatafilnamnet. |

## Anmärkningar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png");
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, System::Drawing::Size) metod

Konverterar den angivna presentationen till en uppsättning PNG-formatbilder.  

Om utdatafilnamnet anges som \"myPath/myFilename.png\" sparas resultatet som en uppsättning av filerna \"myPath/myFilename_N.png\", där N är ett bildnummer.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, System::Drawing::Size imageSize)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Den inmatade presentationen |
| outputFileName | [System::String](../../../system/string/) | Utdatafilnamnet. |
| imageSize | [System::Drawing::Size](../../../system.drawing/size/) | Storleken på varje genererad bild. |

## Anmärkningar

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", System::Drawing::Size(720, 540));
```

## Convert::ToPng(System::SharedPtr\<Presentation\>, System::String, float, System::SharedPtr\<Aspose::Slides::Export::IRenderingOptions\>) metod

Konverterar den angivna presentationen till en uppsättning PNG-formatbilder.  

Om utdatafilnamnet anges som \"myPath/myFilename.png\" sparas resultatet som en uppsättning av filerna \"myPath/myFilename_N.png\", där N är ett bildnummer.

```cpp
static void Aspose::Slides::LowCode::Convert::ToPng(System::SharedPtr<Presentation> pres, System::String outputFileName, float scale, System::SharedPtr<Aspose::Slides::Export::IRenderingOptions> options)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pres | [System::SharedPtr](../../../system/sharedptr/)\<[Presentation](../../../aspose.slides/presentation/)\> | Den inmatade presentationen. |
| outputFileName | [System::String](../../../system/string/) | Utdatafilnamnet. |
| scale | **float** | Skalfaktorn som tillämpas på utdatabilderna i förhållande till originalbildens storlek. |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)\> | Renderingsalternativen. |

## Anmärkningar

```cpp
System::SharedPtr<IRenderingOptions> options = System::MakeObject<RenderingOptions>();
System::SharedPtr<NotesCommentsLayoutingOptions> slidesLayoutOptions = System::MakeObject<NotesCommentsLayoutingOptions>();
slidesLayoutOptions->set_NotesPosition(NotesPositions::BottomTruncated);
options->set_SlidesLayoutOptions(slidesLayoutOptions);

auto pres = System::MakeObject<Presentation>(u"pres.pptx");
Convert::ToPng(pres, u"presImage.png", 2.0f, options);
```

## Se även

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [Presentation](../../../aspose.slides/presentation/)
* Klass [String](../../../system/string/)
* Klass [Convert](../)
* Klass [Size](../../../system.drawing/size/)
* Klass [IRenderingOptions](../../../aspose.slides.export/irenderingoptions/)
* Namnrymd [Aspose::Slides::LowCode](../../)
* Bibliotek [Aspose.Slides](../../../)