---
title: rend()
second_title: Aspose.Slides für C++ API-Referenz
description: Gibt einen Reverse-Iterator auf das Element zurück, das dem letzten Element des umgekehrten Containers folgt. Es entspricht dem Element, das dem ersten Element des nicht umgekehrten Containers vorausgeht. Dieses Element dient als Platzhalter; ein Zugriff darauf führt zu undefiniertem Verhalten.
type: docs
weight: 287
url: /de/system.collections.specialized/stringcollection/rend/
---
## StringCollection::rend() Methode

Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior.

```cpp
reverse_iterator System::Collections::Specialized::StringCollection::rend() noexcept
```

### Rückgabewert

Ein Iterator, der auf das theoretische Element zeigt, das dem ersten Element des Containers vorausgeht.

## StringCollection::rend() const Methode

Returns a reverse iterator to the element following the last element of the reversed container. It corresponds to the element preceding the first element of the non-reversed container. This element acts as a placeholder, attempting to access it results in undefined behavior.

```cpp
const_reverse_iterator System::Collections::Specialized::StringCollection::rend() const noexcept
```

### Rückgabewert

Ein Iterator, der auf das theoretische Element zeigt, das dem ersten Element des const-qualifizierten Containers vorausgeht.

## Siehe auch

* Typedef [reverse_iterator](../reverse_iterator/)
* Typedef [const_reverse_iterator](../const_reverse_iterator/)
* Klasse [StringCollection](../)
* Namensraum [System::Collections::Specialized](../../)
* Library [Aspose.Slides](../../../)