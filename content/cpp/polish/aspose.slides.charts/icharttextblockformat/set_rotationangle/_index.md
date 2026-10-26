---
title: set_RotationAngle()
second_title: Aspose.Slides dla C++ - Dokumentacja API
description: Określa niestandardowy obrót stosowany do tekstu wewnątrz ramki ograniczającej. Jeśli nie zostanie określony, używany jest obrót powiązanej figury. Jeśli zostanie określony, jest stosowany niezależnie od figury. Oznacza to, że figura może mieć zastosowany obrót dodatkowo do obrotu samego tekstu. Uzyskana wartość wizualnego obrotu tekstu jest podsumowana z tej właściwości oraz predefiniowanego typu pionowego w właściwości TextVerticalType. Zapisz float.
type: docs
weight: 248
url: /pl/aspose.slides.charts/icharttextblockformat/set_rotationangle/
---
## IChartTextBlockFormat::set_RotationAngle(float) metoda


Określa niestandardowy obrót stosowany do tekstu wewnątrz ramki ograniczającej. Jeśli nie zostanie określony, używany jest obrót powiązanej figury. Jeśli zostanie określony, to jest stosowany niezależnie od figury. Oznacza to, że figura może mieć zastosowany obrót dodatkowo do obrotu samego tekstu. Powstała wartość wizualnego obrotu tekstu jest podsumowana z tej właściwości i predefiniowanego typu pionowego w właściwości TextVerticalType. Zapisz **float**.

```cpp
virtual void Aspose::Slides::Charts::IChartTextBlockFormat::set_RotationAngle(float value)=0
```

## Uwagi


Rozważmy przypadek, w którym figura ma zastosowany obrót o 90 stopni zgodnie z ruchem wskazówek zegara. Dodatkowo ciało tekstu ma zastosowany obrót o -90 stopni przeciwnie do ruchu wskazówek zegara. W rezultacie figura będzie wyglądać na obróconą, ale tekst w niej zawarty będzie wyglądał, jakby wcale nie został obrócony.

## Zobacz także

* Klasa [IChartTextBlockFormat](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)