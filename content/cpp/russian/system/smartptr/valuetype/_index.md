---
title: ValueType
second_title: Справочник API Aspose.Slides для C++
description: "Тип хранилища указательного массива. Имеет смысл только если T является специализацией System::Array."
type: docs
weight: 508
url: /ru/system/smartptr/valuetype/
---
## ValueType typedef


Тип хранилища указательного массива. Имеет смысл только если T является специализацией [System::Array](../../array/).

```cpp
using System::SmartPtr< T >::ValueType =  typename System::Details::SelectType<typename System::Details::ArrayTypeResolver<T>::value_type>::type
```

## Смотрите также

* Класс [SmartPtr](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)