---
title: WriteLine()
second_title: Aspose.Slides для C++ справочник API
description: Выводит текущий символ завершения строки в поток вывода, представляемый текущим объектом.
type: docs
weight: 27
url: /ru/system/consoleoutput/writeline/
---
## ConsoleOutput::WriteLine() метод

Выводит текущий символ завершения строки в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine() override
```

## ConsoleOutput::WriteLine(const SharedPtr\<Object\>\&) метод

Выводит строковое представление указанного объекта, за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(const SharedPtr<Object> &value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Объект для вывода |

## ConsoleOutput::WriteLine(bool) метод

Выводит строковое представление указанного булевого значения, за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(bool value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **bool** | Значение для вывода |

## ConsoleOutput::WriteLine(char_t) метод

Выводит указанное символьное значение, за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(char_t value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | char_t | Значение для вывода |

## ConsoleOutput::WriteLine(Decimal) метод

Выводит строковое представление значения [Decimal](../../decimal/), за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(Decimal value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Decimal](../../decimal/) | Значение для вывода |

## ConsoleOutput::WriteLine(double) метод

Выводит строковое представление значения двойной точности, за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(double value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **double** | Значение для вывода |

## ConsoleOutput::WriteLine(int) метод

Выводит строковое представление 32-разрядного целого значения, за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(int value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Значение для вывода |

## ConsoleOutput::WriteLine(int64_t) метод

Выводит строковое представление 64-разрядного целого значения, за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(int64_t value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **int64_t** | Значение для вывода |

## ConsoleOutput::WriteLine(float) метод

Выводит строковое представление значения с одинарной точностью, за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(float value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **float** | Значение для вывода |

## ConsoleOutput::WriteLine(const String\&) метод

Выводит указанный объект строки, за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(const String &value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [String](../../string/)\& | Объект строки для вывода |

## ConsoleOutput::WriteLine(uint32_t) метод

Выводит строковое представление беззнакового 32-разрядного целого значения, за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(uint32_t value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **uint32_t** | Значение для вывода |

## ConsoleOutput::WriteLine(uint64_t) метод

Выводит строковое представление беззнакового 64-разрядного целого значения, за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(uint64_t value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | **uint64_t** | Значение для вывода |

## ConsoleOutput::WriteLine(const ArrayPtr\<char_t\>\&) метод

Выводит строковое представление указанного массива символов, за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(const ArrayPtr<char_t> &buffer) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Массив для вывода |

## ConsoleOutput::WriteLine(const ArrayPtr\<char_t\>\&, int32_t, int32_t) метод

Выводит строковое представление диапазона значений указанного массива символов, за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | Массив, содержащий значения для вывода |
| index | **int32_t** | Индекс, с которого начинается диапазон элементов для вывода |
| count | **int32_t** | Количество элементов в диапазоне элементов для вывода |

## ConsoleOutput::WriteLine(const char_t *) метод

Выводит указанную C-строку, за которой следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(const char_t *value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const char_t * | C-строка для вывода |

## ConsoleOutput::WriteLine(const TypeInfo\&) метод

Выводит строковое представление указанного объекта [TypeInfo](../../typeinfo/), за которым следует текущий символ завершения строки, в поток вывода, представляемый текущим объектом.

```cpp
void System::ConsoleOutput::WriteLine(const TypeInfo &value) override
```

### Аргументы

| Параметр | Тип | Описание |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | Объект [TypeInfo](../../typeinfo/) для вывода |

## ConsoleOutput::WriteLine(const char *) метод

```cpp
void System::ConsoleOutput::WriteLine(const char *)=delete
```

## Смотрите также

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Class [ConsoleOutput](../)
* Class [Object](../../object/)
* Class [Decimal](../../decimal/)
* Class [String](../../string/)
* Class [TypeInfo](../../typeinfo/)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)