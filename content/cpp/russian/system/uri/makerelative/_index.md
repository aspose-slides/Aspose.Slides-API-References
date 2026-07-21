---
title: MakeRelative()
second_title: Справочник API Aspose.Slides для C++
description: Определяет разницу между двумя экземплярами Uri.
type: docs
weight: 365
url: /ru/system/uri/makerelative/
---
## Uri::MakeRelative(const SharedPtr\<Uri\>\&) метод

Определяет разницу между двумя экземплярами [Uri](../).

```cpp
String System::Uri::MakeRelative(const SharedPtr<Uri> &toUri)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| toUri | const [SharedPtr](../../sharedptr/)\<[Uri](../)\>\& | URI, с которым сравнивается текущий URI |

### Возвращаемое значение

Если имя хоста и схема URI, представленных текущим объектом и **toUri**, одинаковы, то этот метод возвращает [String](../../string/), представляющий относительный [Uri](../), который при добавлении к текущему экземпляру URI даёт **toUri**. Если имя хоста или схема различаются, то метод возвращает [String](../../string/), представляющий параметр **uri**.

## См. также

* Typedef [SharedPtr](../../sharedptr/)
* Класс [String](../../string/)
* Класс [Uri](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)