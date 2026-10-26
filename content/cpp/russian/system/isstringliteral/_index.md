---
title: IsStringLiteral
second_title: Справочник API Aspose.Slides для C++
description: Волшебство шаблонов для проверки, является ли тип строковым литералом.
type: docs
weight: 1704
url: /ru/system/isstringliteral/
---
## IsStringLiteral struct

Волшебство шаблонов для проверки, является ли тип строковым литералом.

```cpp
template<typename T,typename CharT>class IsStringLiteral : public std::integral_constant<bool, IsStringByteSequence<T, CharT>::value &&std::is_array<T>::value>
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | проверяемый тип. |
| CharT | Тип символов для сравнения. |

## См. также

* Пространство имен [System](../)
* Библиотека [Aspose.Slides](../../)