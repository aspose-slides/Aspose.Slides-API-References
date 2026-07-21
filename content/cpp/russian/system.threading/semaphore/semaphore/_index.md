---
title: Semaphore()
second_title: Aspose.Slides для C++ справочник API
description: Создаёт безымянный семафор.
type: docs
weight: 1
url: /ru/system.threading/semaphore/semaphore/
---
## Semaphore::Semaphore(int, int) конструктор


Создаёт безымянный семафор.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| initialCount | int | Начальное количество активных записей. |
| maximumCount | int | Максимальное допустимое количество записей. |

## Semaphore::Semaphore(int, int, const String\&) конструктор


Создаёт именованный семафор.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| initialCount | int | Начальное количество активных записей. |
| maximumCount | int | Максимальное допустимое количество записей. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) имя. |

## Semaphore::Semaphore(int, int, const String\&, bool\&) конструктор


Создаёт именованный семафор.

```cpp
System::Threading::Semaphore::Semaphore(int initialCount, int maximumCount, const String &name, bool &createdNew)
```


### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| initialCount | int | Начальное количество активных записей. |
| maximumCount | int | Максимальное допустимое количество записей. |
| name | const [String](../../../system/string/)\& | [Semaphore](../) имя. |
| createdNew | **bool**\& | Ссылка на переменную, которая устанавливается в true, если семафор был создан, и в false, если был использован существующий семафор с тем же именем. |

## Смотрите также

* Класс [Semaphore](../)
* Класс [String](../../../system/string/)
* Пространство имён [System::Threading](../../)
* Библиотека [Aspose.Slides](../../../)