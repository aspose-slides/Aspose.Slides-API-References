---
title: Guid()
second_title: Справочник API Aspose.Slides для C++
description: Создаёт объект, представляющий GUID, состоящий только из нулей.
type: docs
weight: 1
url: /ru/system/guid/guid/
---
## Guid::Guid() конструктор

Создаёт объект, представляющий GUID, состоящий только из нулей.

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) конструктор

Создаёт объект, представляющий GUID, указанный как массив беззнаковых 8-битных целочисленных значений.

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Массив байтов, содержащий отдельные байты GUID |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) конструктор

Создаёт объект, представляющий GUID, указанный как представление массива беззнаковых 8-битных целочисленных значений.

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | Массив байтов, содержащий отдельные байты GUID |

## Guid::Guid(const String\&) конструктор

Создаёт объект, представляющий GUID, указанный в виде строки.

```cpp
System::Guid::Guid(const String &g)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| g | const [String](../../string/)\& | Строковое представление GUID, которое будет представлено создаваемым объектом |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) конструктор

Создаёт экземпляр [Guid](../) класса из указанных компонентов GUID.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | **int32_t** | Биты 0-31 GUID |
| b | **int16_t** | Биты 32-47 GUID |
| c | **int16_t** | Биты 48-63 GUID |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | Массив байтов, содержащий биты 64-127 GUID |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) конструктор

Создаёт экземпляр [Guid](../) класса из указанных компонентов GUID.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | **int32_t** | Биты 0-31 GUID |
| b | **int16_t** | Биты 32-47 GUID |
| c | **int16_t** | Биты 48-63 GUID |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | Представление массива байтов, содержащего биты 64-127 GUID |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) конструктор

Создаёт экземпляр [Guid](../) класса из указанных беззнаковых целых чисел и байтов.

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | **int32_t** | Биты 0-31 GUID |
| b | **int16_t** | Биты 32-47 GUID |
| c | **int16_t** | Биты 48-63 GUID |
| d | **uint8_t** | Биты 64-71 GUID |
| e | **uint8_t** | Биты 72-79 GUID |
| f | **uint8_t** | Биты 80-87 GUID |
| g | **uint8_t** | Биты 88-95 GUID |
| h | **uint8_t** | Биты 96-103 GUID |
| i | **uint8_t** | Биты 104-111 GUID |
| j | **uint8_t** | Биты 112-119 GUID |
| k | **uint8_t** | Биты 120-127 GUID |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) конструктор

Создаёт экземпляр [Guid](../) класса из указанных беззнаковых целых чисел и байтов.

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| a | **uint32_t** | Биты 0-31 GUID |
| b | **uint16_t** | Биты 32-47 GUID |
| c | **uint16_t** | Биты 48-63 GUID |
| d | **uint8_t** | Биты 64-71 GUID |
| e | **uint8_t** | Биты 72-79 GUID |
| f | **uint8_t** | Биты 80-87 GUID |
| g | **uint8_t** | Биты 88-95 GUID |
| h | **uint8_t** | Биты 96-103 GUID |
| i | **uint8_t** | Биты 104-111 GUID |
| j | **uint8_t** | Биты 112-119 GUID |
| k | **uint8_t** | Биты 120-127 GUID |

## Guid::Guid(const Guid\&) конструктор

Создаёт объект, представляющий тот же GUID, что и указанный объект.

```cpp
System::Guid::Guid(const Guid &guid)
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| guid | const [Guid](../)\& | Объект [Guid](../), из которого копируется значение GUID |

## См. также

* Typedef [ArrayPtr](../../arrayptr/)
* Class [Guid](../)
* Class [String](../../string/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)