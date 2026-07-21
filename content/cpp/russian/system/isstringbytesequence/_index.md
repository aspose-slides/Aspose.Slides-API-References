---
title: IsStringByteSequence
second_title: Aspose.Slides для C++ справочник API
description: Магия шаблона для проверки, является ли тип последовательностью строковых символов.
type: docs
weight: 1691
url: /ru/system/isstringbytesequence/
---
## IsStringByteSequence структура

Магия шаблона для проверки, является ли тип последовательностью строковых символов.

```cpp
template<typename T,typename CharT>class IsStringByteSequence : public std::integral_constant<bool, std::is_same<std::remove_const<std::remove_pointer<std::decay<T>::type>::type>::type, CharT>::value>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | проверяемый тип. |
| CharT | тип символа, с которым проверяется. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)