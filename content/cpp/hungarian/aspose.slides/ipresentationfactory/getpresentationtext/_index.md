---
title: GetPresentationText()
second_title: Aspose.Slides for C++ API Referencia
description: Lekéri a nyers szöveget a diákról
type: docs
weight: 40
url: /hu/aspose.slides/ipresentationfactory/getpresentationtext/
---
## IPresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) metódus


Lekéri a nyers szöveget a diákról

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Bemeneti fájl |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Kivonási mód |

### Visszatérési érték

A [PresentationText](../../presentationtext/) példány, amely a SlideText tömböt tartalmazza, és a nyers diák szövegét képviseli

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) metódus


Lekéri a nyers szöveget a diákról

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Bemeneti adatfolyam |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Kivonási mód |

### Visszatérési érték

A [PresentationText](../../presentationtext/) példány, amely a SlideText tömböt tartalmazza, és a nyers diák szövegét képviseli

## IPresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) metódus


Lekéri a nyers szöveget a diákról

```cpp
virtual System::SharedPtr<IPresentationText> Aspose::Slides::IPresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Bemeneti adatfolyam |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Kivonási mód |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Betöltési beállítások |

### Visszatérési érték

A [PresentationText](../../presentationtext/) példány, amely a SlideText tömböt tartalmazza, és a nyers diák szövegét képviseli

## Lásd még

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IPresentationText](../../ipresentationtext/)
* Osztály [String](../../../system/string/)
* Osztály [IPresentationFactory](../)
* Osztály [Stream](../../../system.io/stream/)
* Osztály [ILoadOptions](../../iloadoptions/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)