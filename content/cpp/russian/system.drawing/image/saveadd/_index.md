---
title: SaveAdd()
second_title: Справочник API Aspose.Slides для C++
description: Добавляет кадр в файл или поток, указанный в предыдущем вызове метода Save().
type: docs
weight: 14
url: /ru/system.drawing/image/saveadd/
---
## Image::SaveAdd(const Imaging::EncoderParametersPtr\&) метод

Добавляет кадр в файл или поток, указанный в предыдущем вызове метода [Save()](../save/).

```cpp
void System::Drawing::Image::SaveAdd(const Imaging::EncoderParametersPtr &encoder_params)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Параметры используемого кодировщика |

## Image::SaveAdd(const SharedPtr\<Image\>\&, const Imaging::EncoderParametersPtr\&) метод

Добавляет кадр в файл или поток, указанный в предыдущем вызове метода [Save()](../save/).

```cpp
void System::Drawing::Image::SaveAdd(const SharedPtr<Image> &image, const Imaging::EncoderParametersPtr &encoder_params)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| image | const [SharedPtr](../../../system/sharedptr/)\<[Image](../)\>\& | Объект [Image](../), содержащий добавляемый кадр |
| encoder_params | const [Imaging::EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)\& | Параметры используемого кодировщика |

## См. также

* Typedef [EncoderParametersPtr](../../../system.drawing.imaging/encoderparametersptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [Image](../)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)