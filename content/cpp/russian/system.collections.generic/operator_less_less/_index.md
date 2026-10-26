---
title: operator<<()
second_title: Aspose.Slides для C++ справочника API
description: Вставьте данные в поток, используя кодировку UTF-8.
type: docs
weight: 716
url: /ru/system.collections.generic/operator_less_less/
---
## System::Collections::Generic::operator<<(std::ostream&, const KeyValuePair<TKey, TValue>&) функция


Вставьте данные в поток, используя кодировку UTF-8.

```cpp
template<typename TKey,typename TValue> std::ostream & System::Collections::Generic::operator<<(std::ostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TKey | Тип ключа. |
| TValue | Тип значения. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::ostream& | Выходной поток для вставки данных. |
| pair | const [KeyValuePair](../keyvaluepair/)<TKey, TValue>& | [Data](../../system.data/) для вставки. |

### Возвращаемое значение

**stream**.

## System::Collections::Generic::operator<<(std::wostream&, const KeyValuePair<TKey, TValue>&) функция


Вставьте данные в поток.

```cpp
template<typename TKey,typename TValue> std::wostream & System::Collections::Generic::operator<<(std::wostream &stream, const KeyValuePair<TKey, TValue> &pair)
```


### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TKey | Тип ключа. |
| TValue | Тип значения. |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| stream | std::wostream& | Выходной поток для вставки данных. |
| pair | const [KeyValuePair](../keyvaluepair/)<TKey, TValue>& | [Data](../../system.data/) для вставки. |

### Возвращаемое значение

**stream**.

## См. также

* Класс [KeyValuePair](../keyvaluepair/)
* Пространство имён [System::Collections::Generic](../)
* Библиотека [Aspose.Slides](../../)