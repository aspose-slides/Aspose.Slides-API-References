---
title: ToBoolean()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt den angegebenen booleschen Wert zurück.
type: docs
weight: 79
url: /de/system/convert/toboolean/
---
## Convert::ToBoolean(bool) Methode


Gibt den angegebenen booleschen Wert zurück.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) Methode


Konvertiert die angegebene 8-bit unsigned integer in einen äquivalenten booleschen Wert.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) Methode


Konvertiert die angegebene 8-bit signed integer in einen äquivalenten booleschen Wert.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) Methode


Konvertiert die angegebene 16-bit unsigned integer in einen äquivalenten booleschen Wert.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) Methode


Konvertiert die angegebene 16-bit signed integer in einen äquivalenten booleschen Wert.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) Methode


Konvertiert die angegebene 32-bit unsigned integer in einen äquivalenten booleschen Wert.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) Methode


Konvertiert die angegebene 32-bit signed integer in einen äquivalenten booleschen Wert.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) Methode


Konvertiert die angegebene 64-bit unsigned integer in einen äquivalenten booleschen Wert.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) Methode


Konvertiert die angegebene 64-bit signed integer in einen äquivalenten booleschen Wert.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) Methode


Konvertiert die angegebene float-Zahl in einen äquivalenten booleschen Wert.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) Methode


Konvertiert die angegebene double-Zahl in einen äquivalenten booleschen Wert.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) Methode


Konvertiert die angegebene decimal-Zahl in einen äquivalenten booleschen Wert.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) Methode


Konvertierung wird nicht unterstützt. Wirft stets InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) Methode


Konvertierung wird nicht unterstützt. Wirft stets InvalidCastException.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) Methode


Konvertiert die angegebene Null-Zeichenkette in den entsprechenden booleschen Wert.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### Rückgabewert

Falsch.

## Convert::ToBoolean(const char_t *) Methode


Konvertiert die angegebene C-Zeichenkette in den Wert des Typs bool.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const char_t * | Die C-Zeichenkette, die konvertiert werden soll |

### Rückgabewert

Wahr, wenn die angegebene C-Zeichenkette gleich "True" ist und falsch, wenn die angegebene C-Zeichenkette gleich "False" ist.

## Convert::ToBoolean(const String\&) Methode


Konvertiert die angegebene Zeichenkette in den Wert des Typs bool.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die Zeichenkette, die konvertiert werden soll |

### Rückgabewert

Wahr, wenn die angegebene Zeichenkette gleich "True" ist und falsch, wenn die angegebene Zeichenkette gleich "False" ist.

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert die angegebene Zeichenkette in den Wert des Typs bool.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | const [String](../../string/)\& | Die Zeichenkette, die konvertiert werden soll |

### Rückgabewert

Wahr, wenn die angegebene Zeichenkette gleich "True" ist und falsch, wenn die angegebene Zeichenkette gleich "False" ist.

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) Methode


Konvertiert den angegebenen boxed-Wert in einen äquivalenten booleschen Wert.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | Der SharedPtr zum Objekt, das den zu konvertierenden Wert kapselt |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | Das Zeichenkettenformat, das verwendet wird, wenn der Typ des boxed-Werts [String](../../string/) ist |

### Rückgabewert

Ein boolescher Wert, der dem angegebenen boxed-Wert entspricht

## See Also

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [Decimal](../../decimal/)
* Klasse [DateTime](../../datetime/)
* Klasse [String](../../string/)
* Klasse [IFormatProvider](../../iformatprovider/)
* Klasse [Object](../../object/)
* Struct [Convert](../)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)