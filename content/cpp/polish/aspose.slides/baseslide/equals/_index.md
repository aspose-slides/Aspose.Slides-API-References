---
title: Equals()
second_title: Aspose.Slides dla referencji API w C++
description: Określa, czy dwie instancje IBaseSlide są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i zawartości statycznej. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia unikalnych wartości identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. bieżącej wartości daty w Symbolu zastępczym daty.
type: docs
weight: 170
url: /pl/aspose.slides/baseslide/equals/
---
## BaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) metoda


Określa, czy dwie instancje [IBaseSlide](../../ibaseslide/) są równe. Wartość zwracana jest obliczana na podstawie struktury slajdu i zawartości statycznej. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia unikalnych wartości identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. bieżącej wartości daty w Date [Placeholder](../../placeholder/).

```cpp
bool Aspose::Slides::BaseSlide::Equals(System::SharedPtr<IBaseSlide> slide) override
```


### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../../ibaseslide/)\> | [IBaseSlide](../../ibaseslide/) do porównania z bieżącym [IBaseSlide](../../ibaseslide/). |

### Wartość zwracana

**true** jeśli określony [IBaseSlide](../../ibaseslide/) jest równy bieżącemu [IBaseSlide](../../ibaseslide/); w przeciwnym razie **false**.

## Uwagi

Poniższy przykład pokazuje, jak porównać dwa slajdy. 
```cpp
auto presentation1 = System::MakeObject<Presentation>(u"AccessSlides.pptx");
auto presentation2 = System::MakeObject<Presentation>(u"HelloWorld.pptx");
for (int32_t i = 0; i < presentation1->get_Masters()->get_Count(); i++)
{
    auto master1 = presentation1->get_Masters()->idx_get(i);
    for (int32_t j = 0; j < presentation2->get_Masters()->get_Count(); j++)
    {
        auto master2 = presentation2->get_Masters()->idx_get(j);
        if (System::ObjectExt::Equals(master1, master2))
        {
            System::Console::WriteLine(System::String::Format(u"SomePresentation1 MasterSlide#{0} is equal to SomePresentation2 MasterSlide#{1}", i, j));
        }
    }
}
```

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IBaseSlide](../../ibaseslide/)
* Klasa [BaseSlide](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)