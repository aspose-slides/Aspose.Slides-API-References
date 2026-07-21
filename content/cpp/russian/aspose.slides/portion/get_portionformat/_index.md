---
title: get_PortionFormat()
second_title: Aspose.Slides для C++ справочник API
description: Возвращает объект форматирования, содержащий явно установленные свойства форматирования текстовой части без применения наследования. Только для чтения IPortionFormat.
type: docs
weight: 1
url: /ru/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() метод

Возвращает объект форматирования, содержащий явно заданные свойства форматирования текстовой части без применения наследования. Только для чтения [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Примечания

Объект форматирования содержит параметры форматирования, определённые только для текущей части, наследованные данные не применяются.

Для получения эффективных значений, включая наследованные, используйте метод [PortionFormat::GetEffective](../../portionformat/geteffective/).

## См. также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Класс [IPortionFormat](../../iportionformat/)
* Класс [Portion](../)
* Пространство имён [Aspose::Slides](../../)
* Библиотека [Aspose.Slides](../../../)