---
title: SaveAdd()
second_title: Aspose.Slides dla C++ - odniesienie API
description: Dodaje klatkę do pliku lub strumienia określonego w poprzednim wywołaniu metody Save().
type: docs
weight: 14
url: /pl/system.drawing/image/saveadd/
---
## Image::SaveAdd(const Imaging::EncoderParametersPtr\&) metoda

Dodaje klatkę do pliku lub strumienia określonego w poprzednim wywołaniu metody [Save()](../save/).

```cpp
void System::Drawing::Image::SaveAdd(const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Parametry enkodera do użycia |

## Image::SaveAdd(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) metoda

Dodaje klatkę do pliku lub strumienia określonego w poprzednim wywołaniu [Save()](../save/) metody.

```cpp
void System::Drawing::Image::SaveAdd(const SharedPtr<Image> &image, const Imaging::EncoderParametersPtr &encoder_params)
```

### Argumenty

| Parametr | Typ | Opis |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../)\>\& | Obiekt [Image](../), który zawiera dodawaną klatkę |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Parametry enkodera do użycia |

## Zobacz także

* Definicja typu [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Definicja typu [SharedPtr](../../../system/sharedptr/)
* Klasa [Image](../)
* Przestrzeń nazw [System::Drawing](../../)
* Biblioteka [Aspose.Slides](../../../)