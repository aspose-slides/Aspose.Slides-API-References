---
title: FormatText()
second_title: Riferimento API Aspose.Slides per C++
description: Questa funzione viene chiamata prima del rendering della porzione di testo in SVG per consentire all'utente di controllare l'SVG risultante.
type: docs
weight: 1
url: /it/aspose.slides.export/isvgshapeandtextformattingcontroller/formattext/
---
## ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr\<ISvgTSpan\>, System::SharedPtr\<IPortion\>, System::SharedPtr\<ITextFrame\>) metodo


Questa funzione viene chiamata prima del rendering della porzione di testo in SVG per consentire all'utente di controllare l'SVG risultante.

```cpp
virtual void Aspose::Slides::Export::ISvgShapeAndTextFormattingController::FormatText(System::SharedPtr<ISvgTSpan> svgTSpan, System::SharedPtr<IPortion> portion, System::SharedPtr<ITextFrame> textFrame)=0
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| svgTSpan | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgTSpan](../../isvgtspan/)\> | Oggetto per controllare la generazione del tspan SVG. |
| portion | [System::SharedPtr](../../../system/sharedptr/)\<[IPortion](../../../aspose.slides/iportion/)\> | Porzione sorgente. |
| textFrame | [System::SharedPtr](../../../system/sharedptr/)\<[ITextFrame](../../../aspose.slides/itextframe/)\> | Frame di testo della porzione sorgente. |

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISvgTSpan](../../isvgtspan/)
* Classe [IPortion](../../../aspose.slides/iportion/)
* Classe [ITextFrame](../../../aspose.slides/itextframe/)
* Classe [ISvgShapeAndTextFormattingController](../)
* Spazio dei nomi [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)