---
title: IsNullOrEmpty()
second_title: Aspose.Slides C++ API hivatkozás
description: Ellenőrzi, hogy a gyűjtemény null vagy üres.
type: docs
weight: 27
url: /hu/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) metódus


Ellenőrzi, hogy a gyűjtemény null vagy üres.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```


### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T | Gyűjtemény típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Ellenőrzendő gyűjtemény. |

### Visszatérési érték

Igaz, ha a gyűjtemény null, vagy nulla elemszámmal rendelkezik, egyébként hamis.

## TestTools::IsNullOrEmpty(const System::String\&) metódus


Ellenőrzi, hogy a karakterlánc null vagy üres.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) ellenőrzéshez. |

### Visszatérési érték

Igaz, ha a karakterlánc null, vagy nulla hosszúságú, egyébként hamis.

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Struktúra [TestTools](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)