---
title: Write()
second_title: Справочник API Aspose.Slides для C++
description: Записывает указанное беззнаковое 8-битное целое значение в выходной поток.
type: docs
weight: 92
url: /ru/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) метод

Записывает указанное беззнаковое 8-битное целое значение в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **uint8_t** | Значение для записи |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) метод

Записывает указанный поддиапазон байтов из заданного массива байтов в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | Массив, содержащий байты для записи |
| index | int | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | int | Количество элементов в поддиапазоне для записи; -1 указывает, что поддиапазон заканчивается в конце массива **buffer** |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) метод

Записывает указанный поддиапазон символов UTF-16 из заданного массива символов в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Массив, содержащий символы для записи |
| index | int | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | int | Количество символов в поддиапазоне для записи; -1 указывает, что поддиапазон заканчивается в конце массива **buffer** |

## BinaryWriter::Write(bool) метод

Записывает один байт со значением 0, если **value** равно «true», и 1, если **value** равно «false», в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **bool** | Булево значение, определяющее байтовое значение для записи в выходной поток |

## BinaryWriter::Write(char16_t) метод

Записывает указанное 16-битное широкое символьное значение в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char16_t | Значение для записи |

## BinaryWriter::Write(int16_t) метод

Записывает указанное 16-битное целое значение в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **int16_t** | Значение для записи |

## BinaryWriter::Write(int) метод

Записывает указанное 32-битное целое значение в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение для записи |

## BinaryWriter::Write(int64_t) метод

Записывает указанное 64-битное целое значение в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **int64_t** | Значение для записи |

## BinaryWriter::Write(uint16_t) метод

Записывает указанное беззнаковое 16-битное целое значение в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **uint16_t** | Значение для записи |

## BinaryWriter::Write(uint32_t) метод

Записывает указанное беззнаковое 32-битное целое значение в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **uint32_t** | Значение для записи |

## BinaryWriter::Write(uint64_t) метод

Записывает указанное беззнаковое 64-битное целое значение в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **uint64_t** | Значение для записи |

## BinaryWriter::Write(float) метод

Записывает указанное значение с плавающей запятой одинарной точности в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **float** | Значение для записи |

## BinaryWriter::Write(double) метод

Записывает указанное значение с плавающей запятой двойной точности в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **double** | Значение для записи |

## BinaryWriter::Write(const Decimal\&) метод

Записывает байтовое представление указанного [Decimal](../../../system/decimal/) значения в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | Значение для записи |

## BinaryWriter::Write(const String\&) метод

Записывает строку с префиксом длины в текущей кодировке в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Строка для записи |

## BinaryWriter::Write(const char_t *) метод

Записывает строку с префиксом длины в текущей кодировке в выходной поток.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### Параметры

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для записи |

## См. также

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Класс [BinaryWriter](../)
* Класс [Decimal](../../../system/decimal/)
* Класс [String](../../../system/string/)
* Пространство имён [System::IO](../../)
* Library [Aspose.Slides](../../../)