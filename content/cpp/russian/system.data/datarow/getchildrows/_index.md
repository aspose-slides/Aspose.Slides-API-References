---
title: GetChildRows()
second_title: Aspose.Slides для C++ справочник API
description: Получает строки, считающиеся дочерними через указанную связь.
type: docs
weight: 27
url: /ru/system.data/datarow/getchildrows/
---
## DataRow::GetChildRows(const System::SharedPtr\<System::Data::DataRelation\>\&) метод

Получает строки, считающиеся дочерними через указанную связь.

```cpp
System::ArrayPtr<System::SharedPtr<System::Data::DataRow>> System::Data::DataRow::GetChildRows(const System::SharedPtr<System::Data::DataRelation> &relation)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| relation | const [System::SharedPtr](../../../system/sharedptr/)\<[System::Data::DataRelation](../../datarelation/)\>\& | Объект связи, указывающий отношение родительской строки — дочерней строки. |

### Возвращаемое значение

[Array](../../../system/array/) дочерних строк получено.

## См. также

* Тип [ArrayPtr](../../../system/arrayptr/)
* Тип [SharedPtr](../../../system/sharedptr/)
* Класс [DataRow](../)
* Класс [DataRelation](../../datarelation/)
* Пространство имён [System::Data](../../)
* Библиотека [Aspose.Slides](../../../)