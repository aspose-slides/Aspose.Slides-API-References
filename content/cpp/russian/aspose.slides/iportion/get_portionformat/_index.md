---
title: get_PortionFormat()
second_title: Aspose.Slides для C++ справка API
description: Возвращает объект форматирования, который содержит явно заданные свойства форматирования текстового фрагмента без применения наследования. Только для чтения IPortionFormat.
type: docs
weight: 1
url: /ru/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() метод

Возвращает объект форматирования, который содержит явно заданные свойства форматирования текстового фрагмента без применения наследования. Только для чтения [IPortionFormat](../../iportionformat/).

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## Примечания

Объект форматирования содержит параметры форматирования, определённые только для текущего фрагмента, наследованные данные не применяются.

Чтобы получить эффективные значения, включая наследованные, используйте метод [IPortionFormat::GetEffective](../../iportionformat/geteffective/).

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPortionFormat](../../iportionformat/)
* Класс [IPortion](../)
* Пространство имён [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)