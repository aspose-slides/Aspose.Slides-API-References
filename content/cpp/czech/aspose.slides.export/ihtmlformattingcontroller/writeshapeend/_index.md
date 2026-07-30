---
title: WriteShapeEnd()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Voláno před vykreslením tvaru. Voláno jednou pro každý tvar. Pokud tato funkce zapíše něco do generátoru, generování aktuálního obrázku snímku bude dokončeno, přidán HTML fragment bude vložen a nový obrázek bude zahájen nad předchozím.
type: docs
weight: 66
url: /cs/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metoda

Voláno před vykreslením tvaru. Voláno jednou pro každý tvar. Pokud tato funkce zapíše něco do generátoru, generování aktuálního obrázku snímku bude ukončeno, vložen fragment HTML a nový obrázek bude zahájen nad předchozím.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Parametry

| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Výstupní objekt. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) který je vykreslen poslední. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [IHtmlGenerator](../../ihtmlgenerator/)
* Třída [IShape](../../../aspose.slides/ishape/)
* Třída [IHtmlFormattingController](../)
* Jmenný prostor [Aspose::Slides::Export](../../)
* Knihovna [Aspose.Slides](../../../)