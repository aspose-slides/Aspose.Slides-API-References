---
title: Write()
second_title: Aspose.Slides för C++ API-referens
description: Skriver det angivna unsigned 8-bit heltalsvärdet till utdataflödet.
type: docs
weight: 92
url: /sv/system.io/binarywriter/write/
---
## BinaryWriter::Write(uint8_t) metod

Skriver det angivna unsigned 8-bit heltalsvärdet till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(uint8_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint8_t** | The value to write |

## BinaryWriter::Write(const ArrayPtr\<uint8_t\>\&, int, int) metod

Skriver det angivna delintervallet av byte från den angivna byte-arrayen till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<uint8_t> &buffer, int index=0, int count=-1)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | The array containing the bytes to write |
| index | int | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | int | The number of elements in the subrange to write; -1 specifies that the subrange ends where **buffer** array ends |

## BinaryWriter::Write(const ArrayPtr\<char_t\>\&, int, int) metod

Skriver det angivna delintervallet av UTF-16-tecken från den angivna tecken-arrayen till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(const ArrayPtr<char_t> &buffer, int index=0, int count=-1)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffer | const [ArrayPtr](../../../system/arrayptr/)\<char_t\>\& | The array containing the characters to write |
| index | int | A 0-based index of the elemnet in **buffer** at which the subrange to write begins |
| count | int | The number of characters in the subrange to write; -1 specifies that the subrange ends where **buffer** array ends |

## BinaryWriter::Write(bool) metod

Skriver en enda byte med värdet 0 om **value** är 'true' och 1 om **value** är 'false' till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(bool value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **bool** | The boolean value specifying the byte value to write to the output stream |

## BinaryWriter::Write(char16_t) metod

Skriver det angivna 16-bit breda teckenvärdet till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(char16_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | char16_t | The value to write |

## BinaryWriter::Write(int16_t) metod

Skriver det angivna 16-bit heltalsvärdet till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(int16_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **int16_t** | The value to write |

## BinaryWriter::Write(int) metod

Skriver det angivna 32-bit heltalsvärdet till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(int value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | int | The value to write |

## BinaryWriter::Write(int64_t) metod

Skriver det angivna 64-bit heltalsvärdet till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(int64_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **int64_t** | The value to write |

## BinaryWriter::Write(uint16_t) metod

Skriver det angivna unsigned 16-bit heltalsvärdet till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(uint16_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint16_t** | The value to write |

## BinaryWriter::Write(uint32_t) metod

Skriver det angivna unsigned 32-bit heltalsvärdet till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(uint32_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint32_t** | The value to write |

## BinaryWriter::Write(uint64_t) metod

Skriver det angivna unsigned 64-bit heltalsvärdet till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(uint64_t value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **uint64_t** | The value to write |

## BinaryWriter::Write(float) metod

Skriver det angivna enkelprecision flyttalvärdet till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(float value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **float** | The value to write |

## BinaryWriter::Write(double) metod

Skriver det angivna dubbelprecision flyttalvärdet till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(double value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | **double** | The value to write |

## BinaryWriter::Write(const Decimal\&) metod

Skriver byte-representationen av det angivna [Decimal](../../../system/decimal/)-värdet till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(const Decimal &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [Decimal](../../../system/decimal/)\& | The value to write |

## BinaryWriter::Write(const String\&) metod

Skriver en längd-prefixad sträng i den aktuella kodningen till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(const String &value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const [String](../../../system/string/)\& | The string to write |

## BinaryWriter::Write(const char_t *) metod

Skriver en längd-prefixad sträng i den aktuella kodningen till utdataflödet.

```cpp
virtual void System::IO::BinaryWriter::Write(const char_t *value)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | const char_t * | The c-string to write |

## Se även

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [BinaryWriter](../)
* Class [Decimal](../../../system/decimal/)
* Class [String](../../../system/string/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)