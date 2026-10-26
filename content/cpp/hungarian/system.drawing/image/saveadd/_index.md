---
title: SaveAdd()
second_title: Aspose.Slides C++ API referencia
description: Keretet ad a fájlhoz vagy adatfolyamhoz, amelyet egy korábbi Save() metódushívás határozott meg.
type: docs
weight: 14
url: /hu/system.drawing/image/saveadd/
---
## Image::SaveAdd(const Imaging::EncoderParametersPtr\&) metódus


Keretet ad a fájlhoz vagy adatfolyamhoz, amelyet egy korábbi hívásban a [Save()](../save/) metódus határozott meg.

```cpp
void System::Drawing::Image::SaveAdd(const Imaging::EncoderParametersPtr &encoder_params)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | A használandó enkóder paraméterei |

## Image::SaveAdd(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) metódus


Keretet ad a fájlhoz vagy adatfolyamhoz, amelyet egy korábbi hívásban a [Save()](../save/) metódus határozott meg.

```cpp
void System::Drawing::Image::SaveAdd(const SharedPtr<Image> &image, const Imaging::EncoderParametersPtr &encoder_params)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../)\>\& | Egy [Image](../) objektum, amely a hozzáadandó keretet tartalmazza |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | A használandó enkóder paraméterei |

## Lásd még

* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Image](../)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)