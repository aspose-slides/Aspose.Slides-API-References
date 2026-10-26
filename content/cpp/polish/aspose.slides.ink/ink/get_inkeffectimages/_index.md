---
title: get_InkEffectImages()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Pobiera kolekcję niestandardowych obrazów używanych do symulacji efektów wizualnych pędzli atramentu. Te obrazy są wykorzystywane podczas renderowania atramentu z określonymi wartościami InkEffectType, takimi jak Galaxy, Rainbow itp. Dostarczając własne obrazy, możesz kontrolować, jak każdy efekt atramentu się prezentuje.
type: docs
weight: 14
url: /pl/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() metoda

Pobiera kolekcję niestandardowych obrazów używanych do symulacji efektów wizualnych pędzli atramentu. Te obrazy są wykorzystywane podczas renderowania atramentu z określonymi wartościami [InkEffectType](../../inkeffecttype/), takimi jak Galaxy, Rainbow itp. Dostarczając własne obrazy, możesz kontrolować, jak każdy efekt atramentu się prezentuje.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```
## Uwagi

Ta własność umożliwia zastąpienie domyślnych tekstur efektów atramentu własnymi, co jest szczególnie przydatne, gdy domyślne zasoby są ograniczone licencją lub niedostępne w czasie wykonywania.

Każdy wpis w słowniku musi powiązać wartość [InkEffectType](../../inkeffecttype/) z odpowiadającym obiektem [IImage](../../../aspose.slides/iimage/) (np. Bitmap lub interfejsem obrazu **Aspose**).

```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```
## Zobacz także

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasa [IDictionary](../../../system.collections.generic/idictionary/)
* Klasa [IImage](../../../aspose.slides/iimage/)
* Klasa [Ink](../)
* Przestrzeń nazw [Aspose::Slides::Ink](../../)
* Biblioteka [Aspose.Slides](../../../)