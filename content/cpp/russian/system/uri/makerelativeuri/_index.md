---
title: MakeRelativeUri()
second_title: Aspose.Slides для C++ — справочник API
description: Определяет различие между URI, представленными текущим объектом и указанными объектами Uri.
type: docs
weight: 352
url: /ru/system/uri/makerelativeuri/
---
## Uri::MakeRelativeUri(const SharedPtr\<Uri\>\&) метод


Определяет различие между URI, представленными текущим объектом и указанными объектами [Uri](../).

```cpp
SharedPtr<Uri> System::Uri::MakeRelativeUri(const SharedPtr<Uri> &uri)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| uri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | Сравниваемый |

### Возвращаемое значение

Если имя хоста и схема URI, представленных текущим объектом и **toUri**, одинаковы, то этот метод возвращает относительный [Uri](../), который, будучи присоединён к текущему экземпляру URI, дает **toUri**. Если имя хоста или схема различаются, то этот метод возвращает объект [Uri](../), представляющий параметр **uri**.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [Uri](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)