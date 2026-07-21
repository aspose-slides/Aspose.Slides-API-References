---
title: MakeConstRef
second_title: Aspose.Slides для C++ справочник API
description: Трейт для создания обобщённого типа \"const reference\", если он является String или типом SmartPtr<>.
type: docs
weight: 1743
url: /ru/system/makeconstref/
---
## MakeConstRef структура

Трейт для создания обобщённого типа «константная ссылка», если он является [String](../string/) или типом SmartPtr<>.

```cpp
template<typename T>class MakeConstRef : public std::conditional<System::detail::is_a<T, System::SmartPtr>::value||std::is_same<System::String, T>::value, const T &, T>
```

## См. также

* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)