---
title: ToBoolean()
second_title: Aspose.Slides C++ API-referencia
description: Visszaadja a megadott logikai értéket.
type: docs
weight: 79
url: /hu/system/convert/toboolean/
---
## Convert::ToBoolean(bool) metódus


Visszaadja a megadott logikai értéket.

```cpp
static constexpr bool System::Convert::ToBoolean(bool value)
```

## Convert::ToBoolean(uint8_t) metódus


Átalakítja a megadott 8 bites előjel nélküli egész számot egy ekvivalens logikai értékké.

```cpp
static constexpr bool System::Convert::ToBoolean(uint8_t value)
```

## Convert::ToBoolean(int8_t) metódus


Átalakítja a megadott 8 bites előjeles egész számot egy ekvivalens logikai értékké.

```cpp
static constexpr bool System::Convert::ToBoolean(int8_t value)
```

## Convert::ToBoolean(uint16_t) metódus


Átalakítja a megadott 16 bites előjel nélküli egész számot egy ekvivalens logikai értékké.

```cpp
static constexpr bool System::Convert::ToBoolean(uint16_t value)
```

## Convert::ToBoolean(int16_t) metódus


Átalakítja a megadott 16 bites előjeles egész számot egy ekvivalens logikai értékké.

```cpp
static constexpr bool System::Convert::ToBoolean(int16_t value)
```

## Convert::ToBoolean(uint32_t) metódus


Átalakítja a megadott 32 bites előjel nélküli egész számot egy ekvivalens logikai értékké.

```cpp
static constexpr bool System::Convert::ToBoolean(uint32_t value)
```

## Convert::ToBoolean(int32_t) metódus


Átalakítja a megadott 32 bites előjeles egész számot egy ekvivalens logikai értékké.

```cpp
static constexpr bool System::Convert::ToBoolean(int32_t value)
```

## Convert::ToBoolean(uint64_t) metódus


Átalakítja a megadott 64 bites előjel nélküli egész számot egy ekvivalens logikai értékké.

```cpp
static constexpr bool System::Convert::ToBoolean(uint64_t value)
```

## Convert::ToBoolean(int64_t) metódus


Átalakítja a megadott 64 bites előjeles egész számot egy ekvivalens logikai értékké.

```cpp
static constexpr bool System::Convert::ToBoolean(int64_t value)
```

## Convert::ToBoolean(float) metódus


Átalakítja a megadott float számot egy ekvivalens logikai értékké.

```cpp
static constexpr bool System::Convert::ToBoolean(float value)
```

## Convert::ToBoolean(double) metódus


Átalakítja a megadott double számot egy ekvivalens logikai értékké.

```cpp
static constexpr bool System::Convert::ToBoolean(double value)
```

## Convert::ToBoolean(const Decimal\&) metódus


Átalakítja a megadott decimális számot egy ekvivalens logikai értékké.

```cpp
static bool System::Convert::ToBoolean(const Decimal &value)
```

## Convert::ToBoolean(char_t) metódus


Az átalakítás nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static bool System::Convert::ToBoolean(char_t value)
```

## Convert::ToBoolean(DateTime) metódus


Az átalakítás nem támogatott. Mindig InvalidCastException kivételt dob.

```cpp
static bool System::Convert::ToBoolean(DateTime value)
```

## Convert::ToBoolean(std::nullptr_t) metódus


Átalakítja a megadott null-karakterláncot az ekvivalens logikai értékké.

```cpp
static constexpr bool System::Convert::ToBoolean(std::nullptr_t)
```


### Visszatérési érték

False.

## Convert::ToBoolean(const char_t *) metódus


Átalakítja a megadott C-karakterláncot a bool típusú értékké.

```cpp
static bool System::Convert::ToBoolean(const char_t *value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const char_t * | A konvertálandó C-karakterlánc |

### Visszatérési érték

True, ha a megadott C-karakterlánc egyenlő a "True" értékkel, és false, ha a megadott C-karakterlánc egyenlő a "False" értékkel.

## Convert::ToBoolean(const String\&) metódus


Átalakítja a megadott stringet a bool típusú értékké.

```cpp
static bool System::Convert::ToBoolean(const String &value)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string |

### Visszatérési érték

True, ha a megadott string egyenlő a "True" értékkel, és false, ha a megadott string egyenlő a "False" értékkel.

## Convert::ToBoolean(const String\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott stringet a bool típusú értékké.

```cpp
static bool System::Convert::ToBoolean(const String &value, const SharedPtr<IFormatProvider> &)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | const [String](../../string/)\& | A konvertálandó string |

### Visszatérési érték

True, ha a megadott string egyenlő a "True" értékkel, és false, ha a megadott string egyenlő a "False" értékkel.

## Convert::ToBoolean(const SharedPtr\<Object\>\&, const SharedPtr\<IFormatProvider\>\&) metódus


Átalakítja a megadott dobozolt értéket egy ekvivalens logikai értékké.

```cpp
static bool System::Convert::ToBoolean(const SharedPtr<Object> &obj, const SharedPtr<IFormatProvider> &provider=nullptr)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | A megosztott mutató az objektumra, amely a konvertálandó értéket dobozza |
| provider | const [SharedPtr](../../sharedptr/)\<[IFormatProvider](../../iformatprovider/)\>\& | A string formátum, amelyet akkor kell használni, ha a dobozolt érték típusa [String](../../string/) |

### Visszatérési érték

Egy logikai érték, amely ekvivalens a megadott dobozolt értékkel

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [Decimal](../../decimal/)
* Osztály [DateTime](../../datetime/)
* Osztály [String](../../string/)
* Osztály [IFormatProvider](../../iformatprovider/)
* Osztály [Object](../../object/)
* Struktúra [Convert](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)