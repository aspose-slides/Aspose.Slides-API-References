---
title: WriteShapeStart()
second_title: Aspose.Slides dla C++ Referencja API
description: Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, dodany fragment HTML zostanie wstawiony, a nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.
type: docs
weight: 66
url: /pl/aspose.slides.export/embedallfontshtmlcontroller/writeshapestart/
---
## EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metoda

Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, generowanie bieżącego obrazu slajdu zostanie zakończone, dodany fragment html zostanie wstawiony i nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Obiekt wyjściowy. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) który ma być renderowany. |

## Zobacz również

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IHtmlGenerator](../../ihtmlgenerator/)
* Class [IShape](../../../aspose.slides/ishape/)
* Class [EmbedAllFontsHtmlController](../)
* Namespace [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)