---
title: IsEmpty()
second_title: Aspose.Slides pro C++ API reference
description: Kontroluje, zda je řetězec prázdný.
type: docs
weight: 14
url: /cs/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) metoda

Kontroluje, zda je řetězec prázdný.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) pro kontrolu, zda je prázdný. |

### Návratová hodnota

True pokud je řetězec prázdný (null-length), false jinak.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) metoda

Kontroluje, zda je kolekce prázdná.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ kolekce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Kolekce k prověření. |

### Návratová hodnota

True pokud má kolekce nulový počet prvků, false jinak.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Struktura [TestTools](../)
* Jmenný prostor [System](../../)
* Knihovna [Aspose.Slides](../../../)