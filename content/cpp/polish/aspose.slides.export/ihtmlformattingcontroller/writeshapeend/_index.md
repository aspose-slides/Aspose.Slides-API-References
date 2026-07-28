---
title: WriteShapeEnd()
second_title: Odwołanie API Aspose.Slides dla C++
description: Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, dodany fragment html zostanie wstawiony, a nowy obraz zostanie rozpoczęty nad poprzednim.
type: docs
weight: 66
url: /pl/aspose.slides.export/ihtmlformattingcontroller/writeshapeend/
---
## IHtmlFormattingController::WriteShapeEnd(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) metoda


Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, generowanie obrazu bieżącego slajdu zostanie zakończone, dodany fragment html zostanie wstawiony, a nowy obraz zostanie rozpoczęty nad poprzednim.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeEnd(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
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
* Klasa [IHtmlFormattingController](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Library [Aspose.Slides](../../../)