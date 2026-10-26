---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Skriver ut strängrepresentationen av det angivna bool-värdet till utdataflödet som representeras av det aktuella objektet.
type: docs
weight: 14
url: /sv/system/consoleoutput/write/
---
## ConsoleOutput::Write(bool) metod

Skriver ut strängrepresentationen av det angivna bool-värdet till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(bool value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **bool** | The value to output |

## ConsoleOutput::Write(const SharedPtr\<Object\>\&) metod

Skriver ut strängrepresentationen av det angivna objektet till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(const SharedPtr<Object> &value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | The object to output |

## ConsoleOutput::Write(char_t) metod

Skriver ut det angivna teckenvärdet till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(char_t value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char_t | The value to output |

## ConsoleOutput::Write(Decimal) metod

Skriver ut strängrepresentationen av [Decimal](../../decimal/)-värdet till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(Decimal value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | [Decimal](../../decimal/) | The value to output |

## ConsoleOutput::Write(double) metod

Skriver ut strängrepresentationen av ett dubbelprecisions flyttal till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(double value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | The value to output |

## ConsoleOutput::Write(int32_t) metod

Skriver ut strängrepresentationen av ett 32-bitars heltal till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(int32_t value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **int32_t** | The value to output |

## ConsoleOutput::Write(int64_t) metod

Skriver ut strängrepresentationen av ett 64-bitars heltal till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(int64_t value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **int64_t** | The value to output |

## ConsoleOutput::Write(float) metod

Skriver ut strängrepresentationen av ett enkelprecisions flyttal till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(float value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **float** | The value to output |

## ConsoleOutput::Write(const String\&) metod

Skriver ut det angivna string-objektet till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(const String &value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../string/)\& | The string object to output |

## ConsoleOutput::Write(uint32_t) metod

Skriver ut strängrepresentationen av ett osignerat 32-bitars heltal till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(uint32_t value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint32_t** | The value to output |

## ConsoleOutput::Write(uint64_t) metod

Skriver ut strängrepresentationen av ett osignerat 64-bitars heltal till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(uint64_t value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint64_t** | The value to output |

## ConsoleOutput::Write(const ArrayPtr\<char_t\>\&) metod

Skriver ut strängrepresentationen av den angivna teckenarrayen till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(const ArrayPtr<char_t> &buffer) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | The array to output |

## ConsoleOutput::Write(const ArrayPtr\<char_t\>\&, int32_t, int32_t) metod

Skriver ut strängrepresentationen av ett intervall av värden i den angivna teckenarrayen till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(const ArrayPtr<char_t> &buffer, int32_t index, int32_t count) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../arrayptr/)\<char_t\>\& | The array containing the values to output |
| index | **int32_t** | The index at which the range of elements to output begins |
| count | **int32_t** | The number of elements in the range of elements to output |

## ConsoleOutput::Write(const char_t *) metod

Skriver ut den angivna c-strängen till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(const char_t *value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | The c-string to output |

## ConsoleOutput::Write(const TypeInfo\&) metod

Skriver ut strängrepresentationen av det angivna [TypeInfo](../../typeinfo/)-objektet till utdataflödet som representeras av det aktuella objektet.

```cpp
void System::ConsoleOutput::Write(const TypeInfo &value) override
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [TypeInfo](../../typeinfo/)\& | The [TypeInfo](../../typeinfo/) object to output |

## ConsoleOutput::Write(const char *) metod

```cpp
void System::ConsoleOutput::Write(const char *)=delete
```

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Typedef [ArrayPtr](../../arrayptr/)
* Klass [ConsoleOutput](../)
* Klass [Object](../../object/)
* Klass [Decimal](../../decimal/)
* Klass [String](../../string/)
* Klass [TypeInfo](../../typeinfo/)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)