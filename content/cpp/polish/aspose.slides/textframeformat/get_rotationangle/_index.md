---
title: get_RotationAngle()
second_title: Aspose.Slides dla C++ – dokumentacja API
description: Określa niestandardowy obrót stosowany do tekstu wewnątrz ramki. Jeśli nie zostanie określony, używany jest obrót powiązanego kształtu. Jeśli zostanie określony, jest on stosowany niezależnie od kształtu. Oznacza to, że kształt może mieć zastosowany obrót oprócz obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana jest z tej właściwości oraz predefiniowanego typu pionowego w właściwości TextVerticalType. Zwraca float.
type: docs
weight: 300
url: /pl/aspose.slides/textframeformat/get_rotationangle/
---
## TextFrameFormat::get_RotationAngle() metoda


Określa niestandardowy obrót stosowany do tekstu wewnątrz ramki. Jeśli nie zostanie określony, używany jest obrót powiązanego kształtu. Jeśli zostanie określony, jest on stosowany niezależnie od kształtu. Oznacza to, że kształt może mieć zastosowany obrót oprócz obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana jest z tej właściwości oraz predefiniowanego typu pionowego w właściwości TextVerticalType. Zwraca **float**.

```cpp
float Aspose::Slides::TextFrameFormat::get_RotationAngle() override
```

## Uwagi


Rozważmy przypadek, w którym kształt ma zastosowany obrót o 90 stopni zgodnie z ruchem wskazówek zegara. Dodatkowo treść tekstu ma zastosowany obrót o -90 stopni przeciwnie do ruchu wskazówek zegara. Wtedy wynikowy kształt będzie wyglądał na obrócony, ale tekst w jego wnętrzu będzie wyglądał, jakby nie został obrócony.

## Zobacz także

* Klasa [TextFrameFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)