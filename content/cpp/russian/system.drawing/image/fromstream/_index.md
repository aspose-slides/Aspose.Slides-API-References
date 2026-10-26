---
title: FromStream()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт объект Image из указанного потока.
type: docs
weight: 339
url: /ru/system.drawing/image/fromstream/
---
## Image::FromStream(const SharedPtr\<System::IO::Stream\>\&, bool, bool) метод

Создаёт объект [Image](../) из указанного потока.

```cpp
static SharedPtr<Image> System::Drawing::Image::FromStream(const SharedPtr<System::IO::Stream> &stream, bool use_embedded_color_management=false, bool validate_image_data=1)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | const [SharedPtr](../../../system/sharedptr/)\<[System::IO::Stream](../../../system.io/stream/)\>\& | Поток, содержащий данные изображения |
| use_embedded_color_management | **bool** | ИГНОРИРОВАНО |
| validate_image_data | **bool** | ИГНОРИРОВАНО |

### Возвращаемое значение

Разделяемый указатель на созданный объект [Image](../).

## См. также

* Типовое определение [SharedPtr](../../../system/sharedptr/)
* Класс [Image](../)
* Класс [Stream](../../../system.io/stream/)
* Пространство имён [System::Drawing](../../)
* Библиотека [Aspose.Slides](../../../)