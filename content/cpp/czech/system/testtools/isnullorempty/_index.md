---
title: IsNullOrEmpty()
second_title: Aspose.Slides pro C++ API Reference
description: Kontroluje, zda je kolekce null nebo prázdná.
type: docs
weight: 27
url: /cs/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) metoda

Kontroluje, zda je kolekce null nebo prázdná.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```

### Parametry šablony

| Parametr | Popis |
| --- | --- |
| T | Typ kolekce. |

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Kolekce k kontrole. |

### Návratová hodnota

Vrací true, pokud je kolekce null nebo má nulový počet prvků, jinak false.

## TestTools::IsNullOrEmpty(const System::String\&) metoda

Kontroluje, zda je řetězec null nebo prázdný.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) ke kontrole. |

### Návratová hodnota

Vrací true, pokud je řetězec null nebo má nulovou délku, jinak false.

## Viz také

* Typedef [SharedPtr](../../sharedptr/)
* Třída [String](../../string/)
* Struct [TestTools](../)
* Jmenný prostor [System](../../)
* Library [Aspose.Slides](../../../)