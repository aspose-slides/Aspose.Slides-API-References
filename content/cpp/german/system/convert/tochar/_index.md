---
title: ToChar()
second_title: Aspose.Slides für C++ API-Referenz
description: Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.
type: docs
weight: 118
url: /de/system/convert/tochar/
---
## Convert::ToChar(bool) Methode

Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) Methode

Konvertiert die angegebene 8-Bit-Ganzzahl ohne Vorzeichen in ein entsprechendes Unicode-Zeichen.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) Methode

Konvertiert die angegebene 8-Bit-Ganzzahl mit Vorzeichen in ein entsprechendes Unicode-Zeichen.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) Methode

Konvertiert die angegebene 16-Bit-Ganzzahl ohne Vorzeichen in ein entsprechendes Unicode-Zeichen.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) Methode

Konvertiert die angegebene 16-Bit-Ganzzahl mit Vorzeichen in ein entsprechendes Unicode-Zeichen.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) Methode

Konvertiert die angegebene 32-Bit-Ganzzahl ohne Vorzeichen in ein entsprechendes Unicode-Zeichen.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) Methode

Konvertiert die angegebene 32-Bit-Ganzzahl mit Vorzeichen in ein entsprechendes Unicode-Zeichen.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) Methode

Konvertiert die angegebene 64-Bit-Ganzzahl ohne Vorzeichen in ein entsprechendes Unicode-Zeichen.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) Methode

Konvertiert die angegebene 64-Bit-Ganzzahl mit Vorzeichen in ein entsprechendes Unicode-Zeichen.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) Methode

Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) Methode

Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) Methode

Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) Methode

Gibt das angegebene Unicode-Zeichen zurück.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) Methode

Konvertierung wird nicht unterstützt. Wirft immer InvalidCastException.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) Methode

Konvertiert das erste und einzige Zeichen des angegebenen C-Strings in einen char_t-Wert.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Der zu konvertierende C-String; es wird erwartet, dass der C-String genau 1 Zeichen lang ist. |

### Rückgabewert

Das erste und einzige Zeichen des angegebenen C-Strings, wenn er genau 1 Zeichen lang ist, sonst - 0

## Convert::ToChar(const String\&) Methode

Konvertiert das erste und einzige Zeichen des angegebenen Strings in einen char_t-Wert.

```cpp
static char_t System::Convert::ToChar(const String &value)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Der zu konvertierende String; es wird erwartet, dass der String genau 1 Zeichen lang ist. |

### Rückgabewert

Das erste und einzige Zeichen des angegebenen Strings, wenn er genau 1 Zeichen lang ist, sonst - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert das erste und einzige Zeichen des angegebenen Strings in einen char_t-Wert.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Der zu konvertierende String; es wird erwartet, dass der String genau 1 Zeichen lang ist. |

### Rückgabewert

Das erste und einzige Zeichen des angegebenen Strings, wenn er genau 1 Zeichen lang ist, sonst - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) Methode

Konvertiert den angegebenen boxed-Wert in ein entsprechendes Unicode-Zeichen.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der SharedPtr auf das Objekt, das den zu konvertierenden Wert enthält. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das Zeichenfolgendatenformat, das verwendet werden soll, falls der Typ des boxed-Werts [String](../../string/) ist. |

### Rückgabewert

Ein Unicode-Zeichen, das dem angegebenen boxed-Wert entspricht.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Decimal](../../decimal/)
* Klasse [DateTime](../../datetime/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [Object](../../object/)
* Struktur [Convert](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)