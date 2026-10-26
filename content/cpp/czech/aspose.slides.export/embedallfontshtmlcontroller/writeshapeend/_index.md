---
title: WriteShapeEnd()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Voláno před vykreslením tvaru. Voláno jednou pro každý tvar. Pokud tato funkce zapíše něco do generátoru, generování obrázku aktuálního snímku bude dokončeno, přidaný HTML fragment bude vložen a nový obrázek bude zahájen nad předchozím.
type: docs
weight: 79
url: /cs/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metoda

Voláno před vykreslením tvaru. Voláno jednou pro každý tvar. Pokud tato funkce zapíše něco do generatoru, generování obrazu aktuálního snímku bude dokončeno, přidaný fragment HTML bude vložen a nový obraz bude zahájen nad předchozím.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Výstupní objekt. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) který je vykreslen poslední. |

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHtmlGenerator](../../ihtmlgenerator/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [EmbedAllFontsHtmlController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)