---
title: IsDBNull()
second_title: Aspose.Slides für C++ API Referenz
description: NICHT IMPLEMENTIERT.
type: docs
weight: 14
url: /de/system/convert/isdbnull/
---
## Convert::IsDBNull(const T\&) Methode

NICHT IMPLEMENTIERT.

```cpp
template<typename T> static std::enable_if_t<!IsSmartPtr<T>::value, bool> System::Convert::IsDBNull(const T &)
```

## Convert::IsDBNull(const SharedPtr\<T\>\&) Methode

NICHT IMPLEMENTIERT Scheinimplementierung, prüft, ob der Wert nullptr ist.

```cpp
template<typename T> static bool System::Convert::IsDBNull(const SharedPtr<T> &value)
```

## Siehe auch

* Typedef [SharedPtr](../../sharedptr/)
* Struktur [IsSmartPtr](../../issmartptr/)
* Struktur [Convert](../)
* Namensraum [System](../../)
* Bibliothek [Aspose.Slides](../../../)