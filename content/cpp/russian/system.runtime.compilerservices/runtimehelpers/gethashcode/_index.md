---
title: GetHashCode()
second_title: Aspose.Slides для C++ API Справка
description: "Получает хеш-код произвольного типа. Вызывает Object::GetHashCode() для этого."
type: docs
weight: 1
url: /ru/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) метод


Получает хеш-код произвольного типа. Вызывает [Object::GetHashCode()](../../../system/object/gethashcode/) для этого.

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```


### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип, для которого требуется получить хеш-код. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | [Object](../../../system/object/) для получения информации. |

### Возвращаемое значение

Значение хеш-кода, вычисленное целевой реализацией.

## См. также

* Class [SmartPtr](../../../system/smartptr/)
* Class [RuntimeHelpers](../)
* Namespace [System::Runtime::CompilerServices](../../)
* Library [Aspose.Slides](../../../)