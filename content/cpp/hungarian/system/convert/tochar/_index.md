---
title: ToChar()
second_title: Aspose.Slides for C++ API referencia
description: A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.
type: docs
weight: 118
url: /hu/system/convert/tochar/
---
## Convert::ToChar(bool) metódus


A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static char_t System::Convert::ToChar(bool value)
```

## Convert::ToChar(uint8_t) metódus


Átalakítja a megadott 8 bites előjeles nélküli egész számot egy ekvivalens unicode karakterre.

```cpp
static constexpr char_t System::Convert::ToChar(uint8_t value)
```

## Convert::ToChar(int8_t) metódus


Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens unicode karakterre.

```cpp
static char_t System::Convert::ToChar(int8_t value)
```

## Convert::ToChar(uint16_t) metódus


Átalakítja a megadott 16 bites előjeles nélküli egész számot egy ekvivalens unicode karakterre.

```cpp
static constexpr char_t System::Convert::ToChar(uint16_t value)
```

## Convert::ToChar(int16_t) metódus


Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens unicode karakterre.

```cpp
static char_t System::Convert::ToChar(int16_t value)
```

## Convert::ToChar(uint32_t) metódus


Átalakítja a megadott 32 bites előjeles nélküli egész számot egy ekvivalens unicode karakterre.

```cpp
static char_t System::Convert::ToChar(uint32_t value)
```

## Convert::ToChar(int32_t) metódus


Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens unicode karakterre.

```cpp
static char_t System::Convert::ToChar(int32_t value)
```

## Convert::ToChar(uint64_t) metódus


Átalakítja a megadott 64 bites előjeles nélküli egész számot egy ekvivalens unicode karakterre.

```cpp
static char_t System::Convert::ToChar(uint64_t value)
```

## Convert::ToChar(int64_t) metódus


Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens unicode karakterre.

```cpp
static char_t System::Convert::ToChar(int64_t value)
```

## Convert::ToChar(float) metódus


A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static char_t System::Convert::ToChar(float value)
```

## Convert::ToChar(double) metódus


A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static char_t System::Convert::ToChar(double value)
```

## Convert::ToChar(const Decimal\&) metódus


A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static char_t System::Convert::ToChar(const Decimal &value)
```

## Convert::ToChar(char_t) metódus


Visszaadja a megadott unicode karaktert.

```cpp
static constexpr char_t System::Convert::ToChar(char_t value)
```

## Convert::ToChar(DateTime) metódus


A konverzió nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static char_t System::Convert::ToChar(DateTime value)
```

## Convert::ToChar(const char_t *) metódus


Átalakítja a megadott c-string első és egyetlen karakterét egy char_t értékre.

```cpp
static char_t System::Convert::ToChar(const char_t *value)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const char_t * | A konvertálandó c-string; elvárás, hogy a c-string pontosan 1 karakter hosszú legyen. |

### Visszatérési érték

A megadott c-string első és egyetlen karaktere, ha pontosan 1 karakter hosszú, egyébként - 0

## Convert::ToChar(const String\&) metódus


Átalakítja a megadott string első és egyetlen karakterét egy char_t értékre.

```cpp
static char_t System::Convert::ToChar(const String &value)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string; elvárás, hogy a string pontosan 1 karakter hosszú legyen. |

### Visszatérési érték

A megadott string első és egyetlen karaktere, ha pontosan 1 karakter hosszú, egyébként - 0

## Convert::ToChar(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott string első és egyetlen karakterét egy char_t értékre.

```cpp
static char_t System::Convert::ToChar(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string; elvárás, hogy a string pontosan 1 karakter hosszú legyen. |

### Visszatérési érték

A megadott string első és egyetlen karaktere, ha pontosan 1 karakter hosszú, egyébként - 0

## Convert::ToChar(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott dobozott értéket egy ekvivalens unicode karakterre.

```cpp
static char_t System::Convert::ToChar(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A megosztott mutató az objektumra, amely becsomagolja a konvertálandó értéket. |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A string formátum, amelyet akkor kell használni, ha a dobozott érték típusa [String](../../string/). |

### Visszatérési érték

Egy unicode karakter, amely ekvivalens a megadott dobozott értékkel.

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [Decimal](../../decimal/)
* Osztály [DateTime](../../datetime/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [Object](../../object/)
* Struct [Convert](../)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)