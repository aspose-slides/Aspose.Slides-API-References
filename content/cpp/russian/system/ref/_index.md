---
title: Ref()
second_title: Aspose.Slides для C++: справочник API
description: Создает ссылку на объект DynamicWeakPtr. Используется транслятором при передаче аргументов функции по ссылке.
type: docs
weight: 2419
url: /ru/system/ref/
---
## System::Ref(DynamicWeakPtr\<T, trunkMode, weakLeafs...\>\&) функция

Создает ссылку на объект [DynamicWeakPtr](../dynamicweakptr/). Используется транслятором при передаче аргументов функции по ссылке.

```cpp
template<typename T,SmartPtrMode,unsigned int ...> DynamicWeakPtr<T, trunkMode, weakLeafs...>::Reference System::Ref(DynamicWeakPtr<T, trunkMode, weakLeafs...> &ptr)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип указываемого объекта. |
| trunkMode | Режим самого умного указателя. |
| weakLeafs | Индексы аргументов шаблона, для которых необходимо вызвать метод SetTemplateWeakPtr. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| ptr | [DynamicWeakPtr](../dynamicweakptr/)\<T, trunkMode, weakLeafs...\>\& | Умный указатель, для которого создаётся ссылка. |

### Возвращаемое значение

Ссылка на умный указатель.

## System::Ref(T\&) функция

Вспомогательная функция для получения ссылок на объекты. Используется для обеспечения того, что [System::DynamicWeakPtr](../dynamicweakptr/) обновляет объект после присваиваний.

```cpp
template<typename T> T & System::Ref(T &value)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип, на который создаётся ссылка. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | T\& | Значение, на которое создаётся ссылка. |

### Возвращаемое значение

Ссылка на значение, переданное в эту функцию.

## См. также

* Класс [DynamicWeakPtr](../dynamicweakptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)