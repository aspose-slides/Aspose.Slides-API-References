---
title: Handle()
second_title: Aspose.Slides для C++ справка API
description: Вызывает функцию-обработчик для каждого вложенного исключения и повторно генерирует любые необработанные исключения.
type: docs
weight: 66
url: /ru/system/details_aggregateexception/handle/
---
## Details_AggregateException::Handle(const Func\<Exception, bool\>\&) метод


Вызывает функцию-обработчик для каждого вложенного исключения и повторно генерирует любые необработанные исключения.

```cpp
void System::Details_AggregateException::Handle(const Func<Exception, bool> &predicate)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| predicate | const [Func](../../func/)\<[Exception](../../exception/), **bool**\>\& | Функция, принимающая объект Exception и возвращающая true, если он обработан. |
## Замечания



Если все исключения обработаны, метод возвращается нормально; в противном случае генерируется новое AggregateException, содержащее необработанные исключения. 

## См. также

* Типовое определение [Exception](../../exception/)
* Класс [Func](../../func/)
* Класс [Details_AggregateException](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)