---
title: WriteShapeEnd()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, zostanie wstawiony dodany fragment HTML i nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.
type: docs
weight: 79
url: /pl/aspose.slides.export/embedallfontshtmlcontroller/writeshapeend/
---
## EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metoda


Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, dodany fragment HTML zostanie wstawiony, a nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.

```cpp
void Aspose::Slides::Export::EmbedAllFontsHtmlController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Obiekt wyjściowy. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) który jest renderowany jako ostatni. |

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IHtmlGenerator](../../ihtmlgenerator/)
* Klasa [IShape](../../../aspose.slides/ishape/)
* Klasa [EmbedAllFontsHtmlController](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)