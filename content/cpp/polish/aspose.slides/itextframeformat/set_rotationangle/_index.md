---
title: set_RotationAngle()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa niestandardowy obrót stosowany do tekstu wewnątrz pola ograniczającego. Jeśli nie zostanie określony, używany jest obrót powiązanej figury. Jeśli zostanie określony, jest on stosowany niezależnie od figury. Oznacza to, że figura może mieć zastosowany obrót, oprócz obrotu samego tekstu. Powstała wartość wizualnego obrotu tekstu, podsumowana z tej własności oraz predefiniowanego typu pionowego w własności TextVerticalType. Zapisz float.
type: docs
weight: 352
url: /pl/aspose.slides/itextframeformat/set_rotationangle/
---
## ITextFrameFormat::set_RotationAngle(float) metoda

Określa niestandardowy obrót, który jest stosowany do tekstu wewnątrz pola ograniczającego. Jeśli nie zostanie określony, używany jest obrót powiązanej figury. Jeśli zostanie określony, to jest on stosowany niezależnie od figury. Oznacza to, że figura może mieć zastosowany obrót oprócz tekstu, który również ma zastosowany obrót. Powstała wartość wizualnego obrotu tekstu podsumowana z tej właściwości i predefiniowanego typu pionowego w właściwości TextVerticalType. Zapisz **float**.

```cpp
virtual void Aspose::Slides::ITextFrameFormat::set_RotationAngle(float value)=0
```

## Uwagi

Rozważmy przypadek, w którym figura ma zastosowany obrót o 90 stopni zgodnie z ruchem wskazówek zegara. Dodatkowo sam korpus tekstu ma zastosowany obrót o -90 stopni przeciwnie do ruchu wskazówek zegara. Wtedy wynikowa figura wydaje się obrócona, ale tekst w niej zawarty wygląda tak, jakby wcale nie był obrócony.

## Zobacz także

* Klasa [ITextFrameFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)