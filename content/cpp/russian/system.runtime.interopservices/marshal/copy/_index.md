---
title: Copy()
second_title: Aspose.Slides для C++ справочник API
description: Реализует семантику public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).
type: docs
weight: 1
url: /ru/system.runtime.interopservices/marshal/copy/
---
## Marshal::Copy(const IntPtr, container\&&, int, int) метод

Реализует семантику public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const IntPtr source, container &&destination, int startIndex, int length)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| container | Тип контейнера назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | const IntPtr | Указатель на исходные данные. |
| destination | container\&& | Контейнер, в который копируются данные. |
| startIndex | int | Исходный начальный индекс. |
| length | int | Количество элементов для копирования. |

## Marshal::Copy(const void *, container\&&, int, int) метод

Реализует семантику public static void Copy(IntPtr source, byte[] destination, int startIndex, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const void *source, container &&destination, int startIndex, int length)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| container | Тип контейнера назначения. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | const void * | Указатель на исходные данные. |
| destination | container\&& | Контейнер, в который копируются данные. |
| startIndex | int | Исходный начальный индекс. |
| length | int | Количество элементов для копирования. |

## Marshal::Copy(const container\&, int, void *, int) метод

Реализует семантику public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, void *destination, int length)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| container | Тип исходного контейнера. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | const container\& | Указатель на исходные данные. |
| startIndex | int | Исходный начальный индекс. |
| destination | void * | Указатель на данные назначения. |
| length | int | Количество элементов для копирования. |

## Marshal::Copy(const container\&, int, IntPtr, int) метод

Реализует семантику public static void Copy(char[] source, int startIndex, IntPtr destination, int length).

```cpp
template<typename container> static void System::Runtime::InteropServices::Marshal::Copy(const container &source, int startIndex, IntPtr destination, int length)
```

### Параметры шаблона

| Параметр | Описание |
| --- | --- |
| container | Тип исходного контейнера. |

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| source | const container\& | Указатель на исходные данные. |
| startIndex | int | Исходный начальный индекс. |
| destination | IntPtr | Указатель на данные назначения. |
| length | int | Количество элементов для копирования. |

## См. также

* Класс [Marshal](../)
* Пространство имён [System::Runtime::InteropServices](../../)
* Библиотека [Aspose.Slides](../../../)