---
title: Storage
second_title: Aspose.Slides pro Java referenční příručka API
description: Reprezentuje dočasné úložiště dat pro .
type: docs
url: /cs/com.aspose.slides/storage/
---
**Dědičnost:**
java.lang.Object
```
public final class Storage
```

Reprezentuje dočasné úložiště dat pro [WebDocument](../../com.aspose.slides/webdocument).
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Storage()](#Storage--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Ukládá hodnotu do úložiště. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Načítá data z úložiště. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Určuje, zda úložiště obsahuje prvek se zadaným klíčem. |
### Storage() {#Storage--}
```
public Storage()
```


### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```


Ukládá hodnotu do úložiště.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| key | java.lang.String | Klíč pro hodnotu. |
| value | TValue | Hodnota. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```


Načítá data z úložiště.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| key | java.lang.String | Klíč hodnoty. |

**Vrací:**
TValue - Datová hodnota, pokud je v kolekci dat přítomna, null jinak.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Určuje, zda úložiště obsahuje prvek se zadaným klíčem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| key | java.lang.String | Klíč hodnoty. |

**Vrací:**
boolean - true, pokud úložiště obsahuje prvek se zadaným klíčem, false jinak.