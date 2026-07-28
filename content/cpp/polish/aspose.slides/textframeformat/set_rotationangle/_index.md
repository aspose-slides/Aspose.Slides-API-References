---
title: set_RotationAngle()
second_title: Aspose.Slides dla C++ – odniesienie API
description: Określa niestandardowy obrót, który jest stosowany do tekstu wewnątrz ramki ograniczającej. Jeśli nie zostanie określony, używany jest obrót powiązanego kształtu. Jeśli zostanie określony, jest on stosowany niezależnie od kształtu. Oznacza to, że kształt może mieć zastosowany obrót dodatkowo do obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu jest podsumowana z tej właściwości oraz z predefiniowanego typu pionowego w właściwości TextVerticalType. Zapisz float.
type: docs
weight: 313
url: /pl/aspose.slides/textframeformat/set_rotationangle/
---
## TextFrameFormat::set_RotationAngle(float) metoda

Określa niestandardowy obrót, który jest stosowany do tekstu wewnątrz ramki ograniczającej. Jeśli nie zostanie określony, używany jest obrót powiązanego kształtu. Jeśli zostanie określony, jest on stosowany niezależnie od kształtu. To oznacza, że kształt może mieć zastosowany obrót oprócz obrotu samego tekstu. Wynikowa wartość wizualnego obrotu tekstu jest podsumowana z tej właściwości oraz z predefiniowanego typu pionowego w właściwości TextVerticalType. Zapisz **float**.

```cpp
void Aspose::Slides::TextFrameFormat::set_RotationAngle(float value) override
```
## Uwagi

Rozważmy sytuację, w której kształt ma zastosowany obrót o 90 stopni zgodnie z ruchem wskazówek zegara. Dodatkowo sam korpus tekstu ma zastosowany obrót o -90 stopni przeciwnie do ruchu wskazówek zegara. W rezultacie kształt będzie wydawał się obrócony, ale tekst w jego wnętrzu będzie wyglądał tak, jakby wcale nie został obrócony.

## Zobacz także

* Klasa [TextFrameFormat](../)
* Przestrzeń nazw [Aspose::Slides](../../)
* Biblioteka [Aspose.Slides](../../../)