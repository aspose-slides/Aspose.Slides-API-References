---
title: operator[]()
second_title: Aspose.Slides C++ API-referencia
description: Hozzáférési operátor a kulcstípus konverziójával való munkához.
type: docs
weight: 14
url: /hu/system.collections.generic/dictionaryptr/operator[]/
---
## DictionaryPtr::operator[](const X\&) const metódus

Hozzáférési operátor a kulcstípus konverziójával való munkához.

```cpp
template<class X> V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const X &key) const
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| X | Forrás kulcstípus. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | const X\& | [Dictionary](../../dictionary/) kulcs. |

### Visszatérési érték

Az átadott kulcshoz tartozó érték referenciája, legyen az meglévő vagy újból létrehozott.

## DictionaryPtr::operator[](const T\&) const metódus

Hozzáférési operátor.

```cpp
V & System::Collections::Generic::DictionaryPtr<T, V>::operator[](const T &key) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| key | const T\& | [Dictionary](../../dictionary/) kulcs. |

### Visszatérési érték

Az átadott kulcshoz tartozó érték referenciája, legyen az meglévő vagy újból létrehozott.

## Lásd még

* osztály [DictionaryPtr](../)
* névtér [System::Collections::Generic](../../)
* könyvtár [Aspose.Slides](../../../)