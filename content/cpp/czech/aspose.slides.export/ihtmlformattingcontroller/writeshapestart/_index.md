---
title: WriteShapeStart()
second_title: Aspose.Slides pro C++ - referenční dokumentace API
description: Volá se před vykreslením tvaru. Volá se jednou pro každý tvar. Pokud tato funkce zapíše něco do generátoru, generování aktuálního obrázku snímku bude dokončeno, přidaný HTML fragment bude vložen a nový obrázek bude zahájen nad předchozím.
type: docs
weight: 53
url: /cs/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metoda

Volá se před vykreslením tvaru. Volá se jednou pro každý tvar. Pokud tato funkce zapíše něco do generatoru, generování aktuálního obrázku snímku bude dokončeno, přidaný HTML fragment bude vložen a nový obrázek bude zahájen nad předchozím.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Arguments

| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Výstupní objekt. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) který se chystá vykreslit. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IHtmlGenerator](../../ihtmlgenerator/)
* Třída [IShape](../../../aspose.slides/ishape/)
* Třída [IHtmlFormattingController](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)