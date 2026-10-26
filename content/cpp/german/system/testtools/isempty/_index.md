---
title: IsEmpty()
second_title: Aspose.Slides für C++ API Referenz
description: Prüft, ob die Zeichenkette leer ist.
type: docs
weight: 14
url: /de/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) Methode

Prüft, ob die Zeichenkette leer ist.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) zur Prüfung, ob sie leer ist. |

### Rückgabewert

True, wenn die Zeichenkette leer ist (null-länge), false sonst.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) Methode

Prüft, ob die Sammlung leer ist.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```

### Template parameters

| Parameter | Beschreibung |
| --- | --- |
| T | Sammlungstyp. |

### Arguments

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Zu prüfende Sammlung. |

### Rückgabewert

True, wenn die Sammlung keine Elemente enthält, false sonst.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Struct [TestTools](../)
* Namensraum [System](../../)
* Library [Aspose.Slides](../../../)