---
title: Storage
second_title: Aspose.Slides pro Android pomocí Java API
description: Představuje dočasné úložiště dat pro .
type: docs
url: /cs/com.aspose.slides/storage/
---
**Dědičnost:**
java.lang.Object
```
public final class Storage
```

Představuje dočasné úložiště dat pro [WebDocument](../../com.aspose.slides/webdocument).
## Konstruktory

| Konstruktor | Popis |
| --- | --- |
| [Storage()](#Storage--) |  |
## Metody

| Metoda | Popis |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Ukládá hodnotu do úložiště. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Načítá data z úložiště. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Určuje, zda úložiště obsahuje prvek se specifikovaným klíčem. |
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

**Návratová hodnota:**
TValue - Hodnota dat, pokud je v datové kolekci přítomna, null jinak.
### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```


Určuje, zda úložiště obsahuje prvek se specifikovaným klíčem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| key | java.lang.String | Klíč hodnoty. |

**Návratová hodnota:**
boolean - true pokud úložiště obsahuje prvek se specifikovaným klíčem, false jinak.