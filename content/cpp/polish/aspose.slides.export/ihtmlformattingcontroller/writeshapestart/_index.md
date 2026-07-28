---
title: WriteShapeStart()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, bieżące generowanie obrazu slajdu zostanie zakończone, dodany fragment HTML zostanie wstawiony i nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.
type: docs
weight: 53
url: /pl/aspose.slides.export/ihtmlformattingcontroller/writeshapestart/
---
## IHtmlFormattingController::WriteShapeStart(System::SharedPtr\<IHtmlGenerator\>, System::SharedPtr\<IShape\>) method

Wywoływana przed renderowaniem kształtu. Wywoływana raz dla każdego kształtu. Jeśli ta funkcja zapisze cokolwiek do generatora, bieżące generowanie obrazu slajdu zostanie zakończone, dodany fragment HTML zostanie wstawiony i nowy obraz zostanie rozpoczęty na wierzchu poprzedniego.

```cpp
virtual void Aspose::Slides::Export::IHtmlFormattingController::WriteShapeStart(System::SharedPtr<IHtmlGenerator> generator, System::SharedPtr<IShape> shape)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| generator | [System::SharedPtr](../../../system/sharedptr/)\<[IHtmlGenerator](../../ihtmlgenerator/)\> | Obiekt wyjściowy. |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../../aspose.slides/ishape/)\> | [Shape](../../../aspose.slides/shape/) który ma zostać wyrenderowany. |

## Zobacz także

* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [IHtmlGenerator](../../ihtmlgenerator/)
* Klasa [IShape](../../../aspose.slides/ishape/)
* Klasa [IHtmlFormattingController](../)
* Przestrzeń nazw [Aspose::Slides::Export](../../)
* Biblioteka [Aspose.Slides](../../../)