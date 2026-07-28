---
title: rbegin()
second_title: Aspose.Slides C++ API referencia
description: Visszaad egy fordított iterátort a megfordított tároló első eleméhez. Ez a nem megfordított tároló utolsó elemének felel meg. Ha a tároló üres, a visszaadott iterátor megegyezik a rend().
type: docs
weight: 469
url: /hu/system/array/rbegin/
---
## Array::rbegin() metódus

Returns a reverse iterator to the first element of the reversed container. It corresponds to the last element of the non-reversed container. If the container is empty, the returned iterator is equal to [rend()](../rend/).

```cpp
reverse_iterator System::Array<T>::rbegin() noexcept
```

### Visszatérési érték

An iterator pointing to the last element of the container.

## Array::rbegin() const metódus

Returns a reverse iterator to the first element of the reversed container. It corresponds to the last element of the non-reversed container. If the container is empty, the returned iterator is equal to [rend()](../rend/).

```cpp
const_reverse_iterator System::Array<T>::rbegin() const noexcept
```

### Visszatérési érték

An iterator pointing to the last element of the const-qualified container.

## Lásd még

* Typedef [reverse_iterator](../reverse_iterator/)
* Typedef [const_reverse_iterator](../const_reverse_iterator/)
* Osztály [Array](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)