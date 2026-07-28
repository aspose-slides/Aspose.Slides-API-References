---
title: AddContentPlaceholder()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Dodaje nowy kształt placeholder do slajdu układu, aby pomieścić zawartość, taką jak obraz, tabela, media lub tekst.
type: docs
weight: 1
url: /pl/aspose.slides/layoutplaceholdermanager/addcontentplaceholder/
---
## LayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) metoda

Dodaje nowy kształt placeholder do slajdu układu, aby pomieścić zawartość, taką jak obraz, tabela, media lub tekst.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::LayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height) override
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X nowego kształtu placeholder. |
| y | **float** | Współrzędna Y nowego kształtu placeholder. |
| width | **float** | Szerokość nowego kształtu placeholder. |
| height | **float** | Wysokość nowego kształtu placeholder. |

### Wartość zwracana

Utworzono [IAutoShape](../../iautoshape/) z placeholderem zawartości.

## Uwagi

Poniższy przykład pokazuje, jak dodać kształt placeholdera Content do slajdu układu. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [LayoutPlaceholderManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)