---
title: IsNull()
second_title: Aspose.Slides C++ API Referencia
description: Ellenőrzi, hogy egy konkrét érték null-e. Verzió aritmetikai és enumerációs típusokhoz.
type: docs
weight: 1
url: /hu/system/testtools/isnull/
---
## TestTools::IsNull(T) metódus

Ellenőrzi, hogy a megadott érték null-e. [Version](../../version/) aritmetikai és enumerációs típusokra.

```cpp
template<typename T> static std::enable_if<std::is_arithmetic<T>::value||std::is_enum<T>::value, bool>::type System::TestTools::IsNull(T obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A vizsgálandó érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | T | A null értékre ellenőrzendő érték. |

### Visszatérési érték

Mindig hamis értéket ad vissza.

## TestTools::IsNull(const T\&) metódus

Ellenőrzi, hogy a megadott érték null-e. [Version](../../version/) nem aritmetikai és nem enumerációs értéktípusokra.

```cpp
template<typename T> static std::enable_if<!std::is_arithmetic<T>::value &&!std::is_enum<T>::value, bool>::type System::TestTools::IsNull(const T &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A vizsgálandó érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const T\& | A null értékre ellenőrzendő érték. |

### Visszatérési érték

Igaz, ha az objektum összehasonlítva a nullptr értékkel eredménye igaz, egyébként hamis.

## TestTools::IsNull(const SharedPtr\<T\>\&) metódus

Ellenőrzi, hogy a megadott érték null-e. [Version](../../version/) nem aritmetikai értéktípusokra.

```cpp
template<typename T> static bool System::TestTools::IsNull(const SharedPtr<T> &obj)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | A vizsgálandó érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<T\>\& | A null értékre ellenőrzendő érték. |

### Visszatérési érték

Igaz, ha az objektum összehasonlítva a nullptr értékkel eredménye igaz, egyébként hamis.

## TestTools::IsNull(System::Collections::Generic::KeyValuePair\<K, V\>\&) metódus

Ellenőrzi, hogy a megadott érték null-e. [Version](../../version/) kulcs-érték párokra.

```cpp
template<typename K,typename V> static bool System::TestTools::IsNull(System::Collections::Generic::KeyValuePair<K, V> &kvp)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| K | Kulcs típusa. |
| V | Érték típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| kvp | [System::Collections::Generic::KeyValuePair](../../../system.collections.generic/keyvaluepair/)\<K, V\>\& | Páros objektum. |

### Visszatérési érték

Igaz, ha a pár null-ként van értékelve, egyébként hamis.

## TestTools::IsNull(const System::String\&) metódus

Ellenőrzi, hogy a karakterlánc null-e.

```cpp
static bool System::TestTools::IsNull(const System::String &str)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) ellenőrzéshez. |

### Visszatérési érték

Igaz, ha a karakterlánc null-ként van értékelve, egyébként hamis.

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [KeyValuePair](../../../system.collections.generic/keyvaluepair/)
* Osztály [String](../../string/)
* Struct [TestTools](../)
* Névtér [System](../../)
* Library [Aspose.Slides](../../../)