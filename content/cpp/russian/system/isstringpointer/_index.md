---
title: IsStringPointer
second_title: Aspose.Slides для C++ Справочник API
description: Магия шаблона для проверки, является ли тип указателем на строку символов.
type: docs
weight: 1717
url: /ru/system/isstringpointer/
---
## IsStringPointer структура


Магия шаблона для проверки, является ли тип указателем на строку символов.

```cpp
template<typename T,typename CharT>class IsStringPointer : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_pointer<T>::value>
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | проверяемый тип. |
| CharT | Тип символа, с которым сравнивается. |

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)