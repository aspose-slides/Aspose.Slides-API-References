---
title: operator==()
second_title: Справочник API Aspose.Slides для C++
description: Оператор равенства для ResultValueTask.
type: docs
weight: 131
url: /ru/system.threading.tasks/resultvaluetask/operator_equal_equal/
---
## ResultValueTask::operator==(const ResultValueTask\&) const метод

Оператор равенства для [ResultValueTask](../).

```cpp
bool System::Threading::Tasks::ResultValueTask<T>::operator==(const ResultValueTask &other) const
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| other | const [ResultValueTask](../)\& | Другой [ResultValueTask](../) для сравнения с этим экземпляром. |

### Возвращаемое значение

bool True если обе задачи имеют одинаковое значение результата или ссылаются на одну и ту же базовую задачу; в противном случае — false.

## Замечания

Если любой из экземпляров содержит прямое значение результата, сравнивает результаты напрямую. В противном случае сравнивает указатели на базовые задачи. 

## См. также

* Класс [ResultValueTask](../)
* Пространство имён [System::Threading::Tasks](../../)
* Библиотека [Aspose.Slides](../../../)