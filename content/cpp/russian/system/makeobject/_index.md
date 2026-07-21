---
title: MakeObject()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт объект в куче и возвращает shared pointer на него.
type: docs
weight: 2848
url: /ru/system/makeobject/
---
## System::MakeObject(Args\&&...) функция

Создаёт объект в куче и возвращает shared pointer на него.

```cpp
template<class T,class ...> std::enable_if<!IsSmartPtr<T>::value, SmartPtr<T>>::type System::MakeObject(Args &&... args)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Класс для создания. |
| Args | Типы аргументов конструктора. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| args | Args\&&... | Аргументы конструктора. |

### Возвращаемое значение

[SmartPtr](../smartptr/) к новому созданному объекту, всегда в режиме shared.

## System::MakeObject(Args\&&...) функция

Создаёт объект в куче и возвращает shared pointer на него.

```cpp
template<class T,class ...> std::enable_if<IsSmartPtr<T>::value, T>::type System::MakeObject(Args &&... args)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | [SmartPtr](../smartptr/) к классу для создания. |
| Args | Типы аргументов конструктора. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| args | Args\&&... | Аргументы конструктора. |

### Возвращаемое значение

[SmartPtr](../smartptr/) к новому созданному объекту, всегда в режиме shared.

## См. также

* Класс [SmartPtr](../smartptr/)
* Структура [IsSmartPtr](../issmartptr/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)