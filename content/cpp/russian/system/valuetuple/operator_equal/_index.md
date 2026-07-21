---
title: operator=()
second_title: Справочник API Aspose.Slides для C++
description: 
type: docs
weight: 92
url: /ru/system/valuetuple/operator_equal/
---
## ValueTuple::operator=(const ValueTuple\<OtherArgs...\>\&) метод




```cpp
template<typename ...> ValueTuple & System::ValueTuple<Args>::operator=(const ValueTuple<OtherArgs...> &otherTuple)
```

## ValueTuple::operator=(const SharedPtr\<T\>\&) метод


Разбирает объект в этот кортеж значений.

```cpp
template<typename T> ValueTuple & System::ValueTuple<Args>::operator=(const SharedPtr<T> &deconstructiblePtr)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| deconstructiblePtr | const [SharedPtr](../../sharedptr/)\<T\>\& | Объект для разбора |

## См. также

* Типedef [SharedPtr](../../sharedptr/)
* Класс [ValueTuple](../)
* Пространство имён [System](../../)
* Библиотека [Aspose.Slides](../../../)