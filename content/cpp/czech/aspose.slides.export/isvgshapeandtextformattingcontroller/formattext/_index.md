---
title: FormatText()
second_title: Aspose.Slides pro C++ - referenční příručka API
description: Tato funkce je volána před vykreslením textové části do SVG, aby uživatel mohl řídit výsledné SVG.
type: docs
weight: 1
url: /cs/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) metoda

Tato funkce se volá před vykreslením textové části do SVG, aby uživatel mohl ovládat výsledné SVG.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | Objekt pro řízení generování SVG tspan. |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | Zdrojová část. |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | Textový rámec zdrojové části. |

## Viz také

* Definice typu [SharedPtr](../../../system/sharedptr/)
* Třída [ISvgTSpan](../../isvgtspan/)
* Třída [IPortion](../../../aspose.slides/iportion/)
* Třída [ITextFrame](../../../aspose.slides/itextframe/)
* Třída [ISvgShapeAndTextFormattingController](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)