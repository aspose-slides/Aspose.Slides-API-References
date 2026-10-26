---
title: get_RotationAngle()
second_title: Aspose.Slides dla C++ - dokumentacja API
description: Określa niestandardowy obrót stosowany do tekstu wewnątrz pola ograniczającego. Jeśli nie zostanie określony, używany jest obrót towarzyszącego kształtu. Jeśli zostanie określony, jest on stosowany niezależnie od kształtu. Oznacza to, że kształt może mieć zastosowany obrót oprócz obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej własności i wstępnie zdefiniowanego typu pionowego w własności TextVerticalType. Odczytaj float.
type: docs
weight: 235
url: /pl/aspose.slides.charts/icharttextblockformat/get_rotationangle/
---
## IChartTextBlockFormat::get_RotationAngle() metoda

Określa niestandardowy obrót stosowany do tekstu wewnątrz pola ograniczającego. Jeśli nie zostanie określony, używany jest obrót towarzyszącego kształtu. Jeśli zostanie określony, jest on stosowany niezależnie od kształtu. Oznacza to, że kształt może mieć zastosowany obrót oprócz obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu podsumowana z tej własności i wstępnie zdefiniowanego typu pionowego w własności TextVerticalType. Odczytaj **float**.

```cpp
virtual float Aspose::Slides::Charts::IChartTextBlockFormat::get_RotationAngle()=0
```

## Uwagi

Rozważmy przypadek, w którym kształt ma zastosowany obrót o 90 stopni w kierunku zgodnym z ruchem wskazówek zegara. Dodatkowo ciało tekstu ma zastosowany obrót o -90 stopni w kierunku przeciwnym do ruchu wskazówek zegara. Wtedy wynikowy kształt wydaje się obrócony, ale tekst w nim zawarty wydaje się, jakby w ogóle nie został obrócony.

## Zobacz także

* Klasa [IChartTextBlockFormat](../)
* Przestrzeń nazw [Aspose::Slides::Charts](../../)
* Biblioteka [Aspose.Slides](../../../)