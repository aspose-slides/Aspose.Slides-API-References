---
title: IsNullOrEmpty()
second_title: Aspose.Slides für C++ API-Referenz
description: Überprüft, ob die Sammlung null oder leer ist.
type: docs
weight: 27
url: /de/system/testtools/isnullorempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) Methode

Überprüft, ob die Sammlung null oder leer ist.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```

### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| T | Sammlungstyp. |

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Zu prüfende Sammlung. |

### Rückgabewert

True, wenn die Sammlung null ist oder die Elementanzahl null ist, sonst false.

## TestTools::IsNullOrEmpty(const System::String\&) Methode

Überprüft, ob die Zeichenkette null oder leer ist.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) zu prüfen. |

### Rückgabewert

True, wenn die Zeichenkette null ist oder die Länge null ist, sonst false.

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Class [String](../../string/)
* Struct [TestTools](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)