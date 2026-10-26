---
title: get_RotationAngle()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa niestandardowy obrót stosowany do tekstu wewnątrz ramki ograniczającej. Jeśli nie zostanie określony, używany jest obrót powiązanego kształtu. Jeśli zostanie określony, jest on stosowany niezależnie od kształtu. Oznacza to, że kształt może mieć zastosowany obrót dodatkowy w stosunku do tekstu, który również ma zastosowany własny obrót. Wartość wizualnego obrotu tekstu uzyskana z tej właściwości oraz predefiniowanego typu pionowego w właściwości TextVerticalType. Odczyt float.
type: docs
weight: 339
url: /pl/aspose.slides/itextframeformat/get_rotationangle/
---
## ITextFrameFormat::get_RotationAngle() metoda


Określa niestandardowy obrót stosowany do tekstu wewnątrz ramki ograniczającej. Jeśli nie zostanie określony, używany jest obrót powiązanego kształtu. Jeśli zostanie określony, jest on stosowany niezależnie od kształtu. Oznacza to, że kształt może mieć zastosowany obrót dodatkowy w stosunku do tekstu, który również ma zastosowany własny obrót. Wartość wizualnego obrotu tekstu uzyskana z tej właściwości oraz predefiniowanego typu pionowego w właściwości TextVerticalType. Odczyt **float**.

```cpp
virtual float Aspose::Slides::ITextFrameFormat::get_RotationAngle()=0
```

## Uwagi


Rozważmy przypadek, w którym kształt ma zastosowany obrót o 90 stopni zgodnie z ruchem wskazówek zegara. Dodatkowo treść tekstu ma zastosowany obrót o -90 stopni przeciwnie do ruchu wskazówek zegara. W rezultacie kształt będzie wydawał się obrócony, ale tekst w jego wnętrzu będzie wyglądał tak, jakby w ogóle nie został obrócony.

## Zobacz także

* Klasa [ITextFrameFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)