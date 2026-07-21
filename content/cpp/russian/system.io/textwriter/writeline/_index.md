---
title: WriteLine()
second_title: Справочник API Aspose.Slides для C++
description: Записывает символы завершения строки в поток.
type: docs
weight: 118
url: /ru/system.io/textwriter/writeline/
---
## TextWriter::WriteLine() метод

Записывает символы завершения строки в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine()
```

## TextWriter::WriteLine(const SharedPtr\<Object\>\&) метод

Записывает строковое представление указанного объекта, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(const SharedPtr<Object> &value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [SharedPtr](../../../system/sharedptr/)\<[Object](../../../system/object/)\>\& | Объект для записи |

## TextWriter::WriteLine(bool) метод

Записывает строковое представление указанного логического значения, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(bool value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | **bool** | Значение для записи |

## TextWriter::WriteLine(char_t) метод

Записывает указанный символ, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(char_t value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | char_t | Значение для записи |

## TextWriter::WriteLine(Decimal) метод

Записывает строковое представление указанного [Decimal](../../../system/decimal/) объекта, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(Decimal value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | [Decimal](../../../system/decimal/) | Объект для записи |

## TextWriter::WriteLine(double) метод

Записывает строковое представление указанного double-значения, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(double value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | **double** | Значение для записи |

## TextWriter::WriteLine(int) метод

Записывает строковое представление указанного 32-разрядного целого значения, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(int value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Значение для записи |

## TextWriter::WriteLine(int64_t) метод

Записывает строковое представление указанного 64-разрядного целого значения, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(int64_t value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | **int64_t** | Значение для записи |

## TextWriter::WriteLine(float) метод

Записывает строковое представление указанного одиночного float-значения, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(float value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | **float** | Значение для записи |

## TextWriter::WriteLine(const String\&) метод

Записывает указанную строку, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(const String &value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | Строка для записи |

## TextWriter::WriteLine(uint32_t) метод

Записывает строковое представление указанного беззнакового 32-разрядного целого значения, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint32_t value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint32_t** | Значение для записи |

## TextWriter::WriteLine(uint64_t) метод

Записывает строковое представление указанного беззнакового 64-разрядного целого значения, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(uint64_t value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | **uint64_t** | Значение для записи |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&) метод

Записывает все символы из указанного массива, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Массив, содержащий символы для записи |

## TextWriter::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) метод

Записывает указанный поддиапазон символов UTF-16 из указанного массива символов, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | Массив, содержащий символы для записи |
| index | **int32_t** | Нулевой индекс элемента в **buffer**, с которого начинается поддиапазон для записи |
| count | **int32_t** | Количество символов в поддиапазоне для записи; -1 указывает, что поддиапазон заканчивается в конце массива **buffer** |

## TextWriter::WriteLine(const char_t *) метод

Записывает указанную C-строку, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(const char_t *value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | C-строка для записи |

## TextWriter::WriteLine(const TypeInfo\&) метод

Записывает строковое представление указанного [TypeInfo](../../../system/typeinfo/) объекта, а затем символы завершения строки, в поток.

```cpp
virtual void System::IO::TextWriter::WriteLine(const TypeInfo &value)
```

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [TypeInfo](../../../system/typeinfo/)\& | Объект для записи |

## TextWriter::WriteLine(const String\&, const TArgs\&...) метод

Записывает указанные значения, отформатированные согласно заданному формату, а затем символы завершения строки, в поток.

```cpp
template<class...> void System::IO::TextWriter::WriteLine(const String &format, const TArgs &... args)
```

### Параметры шаблона

| Parameter | Description |
| --- | --- |
| TArgs | Список типов записываемых значений |

### Аргументы

| Parameter | Type | Description |
| --- | --- | --- |
| format | const [String](../../../system/string/)\& | Строковый формат |
| args | const TArgs\&... | Значения для записи |

## Смотрите также

* Typedef [SharedPtr](../../../system/sharedptr/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [TextWriter](../)
* Class [Object](../../../system/object/)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Class [TypeInfo](../../../system/typeinfo/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)