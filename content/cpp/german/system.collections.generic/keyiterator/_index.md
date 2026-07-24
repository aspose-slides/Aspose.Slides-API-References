---
title: KeyIterator
second_title: Aspose.Slides für C++ API-Referenz
description: Dictionary-Iterator, der Zugriff auf Schlüssel bietet.
type: docs
weight: 365
url: /de/system.collections.generic/keyiterator/
---
## KeyIterator Klasse


[Dictionary](../dictionary/) Iterator, der Zugriff auf Schlüssel bietet.

```cpp
template<typename Dict>class KeyIterator : public System::Details::NativeIteratorWrapperBase<Dict::map_t::key_type, Dict::map_t::const_iterator>,
                                           private System::Details::IteratorPointerUpdater<Dict::map_t::key_type, false>
```


### Template-Parameter

| Parameter | Beschreibung |
| --- | --- |
| Dict | [Dictionary](../dictionary/) Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| System::Details::VirtualizedIteratorBase\<typename Dict::map_t::key_type\> * [CloneIterator](./cloneiterator/)() const override | Klont den aktuellen Iterator. |
| void [DecrementIterator](./decrementiterator/)() override | Bewegt den Iterator einen Schritt zurück. |
| void [IncrementIterator](./incrementiterator/)() override | Bewegt den Iterator einen Schritt vorwärts. |
|  [KeyIterator](./keyiterator/)(typename Dict::map_t::const_iterator\&&, typename Dict::map_t::const_iterator\&&) | Konstruktor. |
|  [KeyIterator](./keyiterator/)(const typename Dict::map_t::const_iterator\&, const typename Dict::map_t::const_iterator\&) | Konstruktor. |
|  [KeyIterator](./keyiterator/)([KeyIterator](./)\&&) | Move-Konstruktor. |
| void [ShiftIteratorBy](./shiftiteratorby/)(std::ptrdiff_t) override | Bewegt den Iterator um die angegebene Anzahl von Schritten. |
| virtual  [~KeyIterator](./~keyiterator/)() | Destruktor. |

## Siehe auch

* Namensraum [System::Collections::Generic](../)
* Bibliothek [Aspose.Slides](../../)