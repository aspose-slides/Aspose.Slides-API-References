---
title: Compare()
second_title: Aspose.Slides für C++ API-Referenz
description: Vergleicht zwei Smart-Pointer.
type: docs
weight: 1
url: /de/system.memoryextensions.details/compare/
---
## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const SharedPtr\<U\>\&) Funktion

Vergleicht zwei Smart-Pointer.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const SharedPtr<U> &b)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ des ersten Smart-Pointers |
| U | Typ des zweiten Smart-Pointers |

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Erster Smart-Pointer |
| b | const [SharedPtr](../../system/sharedptr/)\<U\>\& | Zweiter Smart-Pointer |

### Rückgabewert

[Comparison](../../system/comparison/) Ergebnis (0 wenn gleich, -1 wenn a < b, 1 wenn a > b)

## System::MemoryExtensions::Details::Compare(const T\&, const T\&) Funktion

Vergleicht zwei arithmetische Werte.

```cpp
template<typename T> int32_t System::MemoryExtensions::Details::Compare(const T &a, const T &b)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Arithmetischer Typ |

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| a | const T\& | Erster Wert |
| b | const T\& | Zweiter Wert |

### Rückgabewert

[Comparison](../../system/comparison/) Ergebnis (0 wenn gleich, -1 wenn a < b, 1 wenn a > b)

## System::MemoryExtensions::Details::Compare(const SharedPtr\<T\>\&, const U\&) Funktion

Vergleicht einen Smart-Pointer mit einem Wert.

```cpp
template<typename T,typename U> int32_t System::MemoryExtensions::Details::Compare(const SharedPtr<T> &a, const U &b)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Typ, auf den der Smart-Pointer zeigt |
| U | Typ des Wertes |

### Argumente

| Parameter | Type | Beschreibung |
| --- | --- | --- |
| a | const [SharedPtr](../../system/sharedptr/)\<T\>\& | Smart-Pointer |
| b | const U\& | Wert |

### Rückgabewert

[Comparison](../../system/comparison/) Ergebnis (0 wenn gleich, -1 wenn a < b, 1 wenn a > b)

## Siehe auch

* Typedef [SharedPtr](../../system/sharedptr/)
* Namensraum [System::MemoryExtensions::Details](../)
* Bibliothek [Aspose.Slides](../../)