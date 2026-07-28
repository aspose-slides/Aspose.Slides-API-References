---
title: IsEmpty()
second_title: Aspose.Slides C++ API Referenciája
description: Ellenőrzi, hogy a karakterlánc üres-e.
type: docs
weight: 14
url: /hu/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) metódus

Ellenőrzi, hogy a karakterlánc üres-e.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) az üresség ellenőrzéséhez. |

### Visszatérési érték

Igaz, ha a karakterlánc üres (nullhosszúságú), egyébként hamis.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) metódus

Ellenőrzi, hogy a gyűjtemény üres-e.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Gyűjtemény típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | A ellenőrzendő gyűjtemény. |

### Visszatérési érték

Igaz, ha a gyűjtemény elemszáma nulla, egyébként hamis.

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Struktúra [TestTools](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)