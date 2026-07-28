---
title: Convert
second_title: Aspose.Slides dla C++ referencja API
description: Reprezentuje grupę metod przeznaczonych do konwertowania Presentation.
type: docs
weight: 27
url: /pl/aspose.slides.lowcode/convert/
---
## Convert klasa

Represents a group of methods intended to convert [Presentation](../../aspose.slides/presentation/).

```cpp
class Convert
```

## Metody

| Metoda | Opis |
| --- | --- |
| static void [AutoByExtension](./autobyextension/)([System::String](../../system/string/), [System::String](../../system/string/)) | Konwertuje [Presentation](../../aspose.slides/presentation/) przy użyciu przekazanego rozszerzenia ścieżki wyjściowej, aby określić wymaganą format eksportu. |
|  [Convert](./convert/)() |  |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Konwertuje wejściową prezentację na zestaw obrazów w formacie JPEG.  

 Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Konwertuje wejściową prezentację na zestaw obrazów w formacie JPEG.  

 Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu. |
| static void [ToJpeg](./tojpeg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Konwertuje wejściową prezentację na zestaw obrazów w formacie JPEG.  

 Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.jpeg", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.jpeg", gdzie N jest numerem slajdu. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/)) | Konwertuje [Presentation](../../aspose.slides/presentation/) do formatu PDF. |
| static void [ToPdf](./topdf/)([System::String](../../system/string/), [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Konwertuje [Presentation](../../aspose.slides/presentation/) do formatu PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Konwertuje [Presentation](../../aspose.slides/presentation/) do formatu PDF. |
| static void [ToPdf](./topdf/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IPdfOptions](../../aspose.slides.export/ipdfoptions/)\>) | Konwertuje [Presentation](../../aspose.slides/presentation/) do formatu PDF. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Konwertuje wejściową prezentację na zestaw obrazów w formacie PNG.  

 Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.png", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.png", gdzie N jest numerem slajdu. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::Drawing::Size](../../system.drawing/size/)) | Konwertuje wejściową prezentację na zestaw obrazów w formacie PNG.  

 Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.png", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.png", gdzie N jest numerem slajdu. |
| static void [ToPng](./topng/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), **float**, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::IRenderingOptions](../../aspose.slides.export/irenderingoptions/)\>) | Konwertuje wejściową prezentację na zestaw obrazów w formacie PNG.  

 Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.png", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.png", gdzie N jest numerem slajdu. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/)) | Konwertuje [Presentation](../../aspose.slides/presentation/) do formatu SVG. |
| static void [ToSvg](./tosvg/)([System::String](../../system/string/), [Convert::GetOutPathCallback](./getoutpathcallback/)) | Konwertuje [Presentation](../../aspose.slides/presentation/) do formatu SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/)) | Konwertuje [Presentation](../../aspose.slides/presentation/) do formatu SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Konwertuje [Presentation](../../aspose.slides/presentation/) do formatu SVG. |
| static void [ToSvg](./tosvg/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [Convert::GetOutPathCallback](./getoutpathcallback/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ISVGOptions](../../aspose.slides.export/isvgoptions/)\>) | Konwertuje [Presentation](../../aspose.slides/presentation/) do formatu SVG. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/)) | Konwertuje wejściową prezentację na zestaw obrazów w formacie TIFF.  

 Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.tiff", wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.tiff", gdzie N jest numerem slajdu. |
| static void [ToTiff](./totiff/)([System::SharedPtr](../../system/sharedptr/)\<[Presentation](../../aspose.slides/presentation/)\>, [System::String](../../system/string/), [System::SharedPtr](../../system/sharedptr/)\<[Aspose::Slides::Export::ITiffOptions](../../aspose.slides.export/itiffoptions/)\>, **bool**) | Konwertuje wejściową prezentację do formatu TIFF z niestandardowymi opcjami. Jeśli nazwa pliku wyjściowego zostanie podana jako "myPath/myFilename.tiff" i *multipage* jest **false**, wynik zostanie zapisany jako zestaw plików "myPath/myFilename_N.tiff", gdzie N jest numerem slajdu. W przeciwnym razie, jeśli *multipage* jest **true**, wynik będzie wielostronicowym dokumentem "myPath/myFilename.tiff". |

## Definicja typu | Opis |
| --- | --- |
| [GetOutPathCallback](./getoutpathcallback/) | Wywołanie zwrotne, które zostanie wywołane dla każdego [Slide](../../aspose.slides/slide/), oczekując zwrotu ścieżki wyjściowej. |

## Uwagi

```cpp
Convert::AutoByExtension(u"pres.pptx", u"pres.pdf");
```

## Zobacz także

* Przestrzeń nazw [Aspose::Slides::LowCode](../)
* Biblioteka [Aspose.Slides](../../)