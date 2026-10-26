---
title: Storage
second_title: Aspose.Slides dla Androida poprzez odwołanie do API Java
description: Reprezentuje tymczasowe przechowywanie danych dla .
type: docs
url: /pl/com.aspose.slides/storage/
---
**Dziedziczenie:**
java.lang.Object
```
public final class Storage
```

Reprezentuje tymczasowe przechowywanie danych dla [WebDocument](../../com.aspose.slides/webdocument).

## Konstruktory

| Konstruktor | Opis |
| --- | --- |
| [Storage()](#Storage--) |  |

## Metody

| Metoda | Opis |
| --- | --- |
| [<TValue>put(String key, TValue value)](#-TValue-put-java.lang.String-TValue-) | Umieszcza wartość w magazynie. |
| [<TValue>get(String key)](#-TValue-get-java.lang.String-) | Pobiera dane z magazynu. |
| [containsKey(String key)](#containsKey-java.lang.String-) | Określa, czy magazyn zawiera element o określonym kluczu. |

### Storage() {#Storage--}
```
public Storage()
```

### <TValue>put(String key, TValue value) {#-TValue-put-java.lang.String-TValue-}
```
public final void <TValue>put(String key, TValue value)
```

Umieszcza wartość w magazynie.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| key | java.lang.String | Klucz dla wartości. |
| value | TValue | Wartość. |

### <TValue>get(String key) {#-TValue-get-java.lang.String-}
```
public final TValue <TValue>get(String key)
```

Pobiera dane z magazynu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| key | java.lang.String | Klucz wartości. |

**Zwraca:**
TValue - Wartość danych, jeśli jest obecna w kolekcji danych, null otherwise.

### containsKey(String key) {#containsKey-java.lang.String-}
```
public final boolean containsKey(String key)
```

Określa, czy magazyn zawiera element o określonym kluczu.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| key | java.lang.String | Klucz wartości. |

**Zwraca:**
boolean - true, jeśli magazyn zawiera element o określonym kluczu, false w przeciwnym razie.