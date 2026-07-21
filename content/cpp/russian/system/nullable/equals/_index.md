---
title: Equals()
second_title: Справочник API Aspose.Slides для C++
description: Определяет, равно ли значение, представленное текущим объектом, значению, представленному указанным объектом Nullable.
type: docs
weight: 131
url: /ru/system/nullable/equals/
---
## Nullable::Equals(const T1\&) const method


Определяет, равно ли значение, представленное текущим объектом, значению, представленному указанным объектом [Nullable](../) объектом.

```cpp
template<typename T1> std::enable_if<IsNullable<T1>::value, bool>::type System::Nullable<T>::Equals(const T1 &other) const
```


### Template parameters

| Parameter | Description |
| --- | --- |
| T1 | Базовый тип объекта [Nullable](../), с которым сравнивают |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | const T1\& | Константная ссылка на объект [Nullable](../), с которым сравнивают |

### Return Value

true если значение, представленное текущим объектом, равно значению, представленному указанным объектом [Nullable](../), иначе - false

## See Also

* Class [Nullable](../)
* Struct [IsNullable](../../isnullable/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)