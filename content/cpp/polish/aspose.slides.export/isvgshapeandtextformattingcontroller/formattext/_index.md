---
title: FormatText()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Ta funkcja jest wywoływana przed renderowaniem fragmentu tekstu do SVG, aby umożliwić użytkownikowi kontrolowanie wynikowego SVG.
type: docs
weight: 1
url: /pl/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) metoda

Ta funkcja jest wywoływana przed renderowaniem fragmentu tekstu do SVG, aby umożliwić użytkownikowi kontrolowanie wynikowego SVG.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | Obiekt służący do kontrolowania generowania elementu SVG tspan. |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | Fragment źródłowy. |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | Ramka tekstowa fragmentu źródłowego. |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [ISvgTSpan](../../isvgtspan/)
* Klasa [IPortion](../../../aspose.slides/iportion/)
* Klasa [ITextFrame](../../../aspose.slides/itextframe/)
* Klasa [ISvgShapeAndTextFormattingController](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)