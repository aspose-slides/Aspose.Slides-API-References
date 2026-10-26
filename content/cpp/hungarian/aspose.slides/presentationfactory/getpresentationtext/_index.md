---
title: GetPresentationText()
second_title: Aspose.Slides C++ API referencia
description: Lekéri a diákról a nyers szöveget
type: docs
weight: 53
url: /hu/aspose.slides/presentationfactory/getpresentationtext/
---
## PresentationFactory::GetPresentationText(System::String, TextExtractionArrangingMode) metódus

Lekéri a nyers szöveget a diákról

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::String file, TextExtractionArrangingMode mode) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | [System::String](../../../system/string/) | Bemeneti fájl |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Kivonási mód |

### Visszatérési érték

A [PresentationText](../../presentationtext/) példány, amely a nyers diák szövegét reprezentáló SlideText tömböt tartalmaz

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode) metódus

Lekéri a nyers szöveget a diákról

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Bemeneti adatfolyam |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Kivonási mód |

### Visszatérési érték

A [PresentationText](../../presentationtext/) példány, amely a nyers diák szövegét reprezentáló SlideText tömböt tartalmaz

## PresentationFactory::GetPresentationText(System::SharedPtr\<System::IO::Stream\>, TextExtractionArrangingMode, System::SharedPtr\<ILoadOptions\>) metódus

Lekéri a nyers szöveget a diákról

```cpp
System::SharedPtr<IPresentationText> Aspose::Slides::PresentationFactory::GetPresentationText(System::SharedPtr<System::IO::Stream> stream, TextExtractionArrangingMode mode, System::SharedPtr<ILoadOptions> options) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | [System::SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\> | Bemeneti adatfolyam |
| mode | [TextExtractionArrangingMode](../../textextractionarrangingmode/) | Kivonási mód |
| options | [System::SharedPtr](../../../system/sharedptr/)\<[ILoadOptions](../../iloadoptions/)\> | Betöltési beállítások |

### Visszatérési érték

A [PresentationText](../../presentationtext/) példány, amely a nyers diák szövegét reprezentáló SlideText tömböt tartalmaz

## Lásd még

* Enum [TextExtractionArrangingMode](../../textextractionarrangingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IPresentationText](../../ipresentationtext/)
* Class [String](../../../system/string/)
* Class [PresentationFactory](../)
* Class [Stream](../../../system.io/stream/)
* Class [ILoadOptions](../../iloadoptions/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)