---
title: AddContentPlaceholder()
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: Dodaje nowy kształt zastępczy do slajdu układu, aby przechowywać zawartość, taką jak obraz, tabela, media lub tekst.
type: docs
weight: 1
url: /pl/aspose.slides/ilayoutplaceholdermanager/addcontentplaceholder/
---
## ILayoutPlaceholderManager::AddContentPlaceholder(float, float, float, float) metoda

Dodaje nowy kształt zastępczy do slajdu układu, aby przechowywać zawartość, taką jak obraz, tabela, media lub tekst.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::ILayoutPlaceholderManager::AddContentPlaceholder(float x, float y, float width, float height)=0
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| x | **float** | Współrzędna X nowego kształtu zastępczego. |
| y | **float** | Współrzędna Y nowego kształtu zastępczego. |
| width | **float** | Szerokość nowego kształtu zastępczego. |
| height | **float** | Wysokość nowego kształtu zastępczego. |

### Wartość zwracana

Utworzono [IAutoShape](../../iautoshape/) z zastępcą Content.

## Uwagi

Poniższy przykład pokazuje, jak dodać kształt zastępczy Content do slajdu układu. 
```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>();

System::SharedPtr<ILayoutSlide> layout = pres->get_LayoutSlides()->GetByType(SlideLayoutType::Blank);
System::SharedPtr<IAutoShape> placeholder = layout->get_PlaceholderManager()->AddContentPlaceholder(20.0f, 20.0f, 500.0f, 300.0f);
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IAutoShape](../../iautoshape/)
* Klasa [ILayoutPlaceholderManager](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)