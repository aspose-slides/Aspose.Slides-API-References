---
title: Equals()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa, czy dwie instancje IBaseSlide są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i jego statycznej zawartości. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. bieżącej wartości daty w Date Placeholder.
type: docs
weight: 183
url: /pl/aspose.slides/ibaseslide/equals/
---
## IBaseSlide::Equals(System::SharedPtr\<IBaseSlide\>) method


Określa, czy dwie instancje [IBaseSlide](../) są równe. Zwracana wartość jest obliczana na podstawie struktury slajdu i statycznej zawartości. Dwa slajdy są równe, jeśli wszystkie kształty, style, teksty, animacje i inne ustawienia itp. są równe. Porównanie nie uwzględnia wartości unikalnych identyfikatorów, np. SlideId oraz dynamicznej zawartości, np. bieżącej wartości daty w Date [Placeholder](../../placeholder/).

```cpp
virtual bool Aspose::Slides::IBaseSlide::Equals(System::SharedPtr<IBaseSlide> slide)=0
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| slide | [System::SharedPtr](../../../system/sharedptr/)\<[IBaseSlide](../)\> | [IBaseSlide](../) do porównania z bieżącym [IBaseSlide](../). |

### Return Value

**true** jeśli podany [IBaseSlide](../) jest równy bieżącemu [IBaseSlide](../); w przeciwnym razie **false**.

## Zobacz także

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IBaseSlide](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)