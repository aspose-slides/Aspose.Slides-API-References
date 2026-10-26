---
title: operator!=()
second_title: Aspose.Slides C++ API-referencia
description: Ellenőrzi, hogy a hivatkozott objektum nem null értékű-e.
type: docs
weight: 66
url: /hu/system/weakreference_tmpl_t__end_tmpl/operator_not_equal/
---
## WeakReference< T >::operator!=(std::nullptr_t) const metódus

Ellenőrzi, hogy a hivatkozott objektum nem null-e.

```cpp
bool System::WeakReference<T>::operator!=(std::nullptr_t) const
```

### Visszatérési érték

Igaz, ha a hivatkozott objektum nem null, egyébként hamis.

## WeakReference< T >::operator!=(const WeakReference\<T\>\&) const metódus

Összehasonlítja a hivatkozott objektumot egy másik WeakReference példányhoz.

```cpp
bool System::WeakReference<T>::operator!=(const WeakReference<T> &other) const
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| other | const [WeakReference](../weakreference/)\<T\>\& | [Object](../../object/) összehasonlítandó. |

### Visszatérési érték

Igaz, ha a összehasonlított objektumok különböző objektumokra mutatnak, hamis, ha ugyanazt az objektumot referálják.

## Lásd még

* Metódus [WeakReference](../weakreference/)
* Osztály [WeakReference< T >](../)
* Névterület [System](../../)
* Könyvtár [Aspose.Slides](../../../)