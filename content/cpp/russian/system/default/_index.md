---
title: Default()
second_title: Справочник API Aspose.Slides для C++
description: Возвращает ссылку на единственный экземпляр типа исключения, созданный конструктором по умолчанию.
type: docs
weight: 2198
url: /ru/system/default/
---
## System::Default() функция

Возвращает ссылку на единственный экземпляр типа исключения, созданный конструктором по умолчанию.

```cpp
template<typename T> std::enable_if<IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип, экземпляр которого возвращается |

## System::Default() функция

Возвращает ссылку на единственный экземпляр типа, не являющегося исключением, созданный конструктором по умолчанию.

```cpp
template<typename T> std::enable_if<!IsExceptionWrapper<T>::value, constT &>::type System::Default()
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| T | Тип, экземпляр которого возвращается |

## См. также

* Структура [IsExceptionWrapper](../isexceptionwrapper/)
* Пространство имён [System](../)
* Библиотека [Aspose.Slides](../../)