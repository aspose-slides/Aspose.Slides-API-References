---
title: "System::Collections"
second_title: Aspose.Slides dla C++ – Dokumentacja API
description: 
type: docs
weight: 300
url: /pl/system.collections/
---
## Klasy

| Klasa | Opis |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) bitów, które mogą być adresowane przez indeks. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani nie używaj operatora new, ponieważ może to spowodować błędy w czasie wykonywania i/lub awarie asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika, aby przekazać go do funkcji jako argument. |
| [BitArrayPtr](./bitarrayptr/) | Wskaźnik do [BitArray](./bitarray/). Ten typ jest wskaźnikiem służącym do zarządzania usuwaniem innych obiektów. Powinien być alokowany na stosie i przekazywany do funkcji albo przez wartość, albo przez referencję const. |
| [CollectionBase](./collectionbase/) | Dostarcza abstrakcyjną klasę bazową dla silnie typowanej kolekcji. |
| [ICollection](./icollection/) | Definiuje interfejs kolekcji nieogenericznej. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) jest bazowym interfejsem dla wszystkich nieogenericznych kolekcji, które mogą być wyliczane. |
| [IEnumerator](./ienumerator/) | Interfejs enumeratora, który może być używany do iteracji po niektórych elementach. Obiekty tej klasy powinny być alokowane wyłącznie przy użyciu funkcji [System::MakeObject()](../system/makeobject/). Nigdy nie twórz instancji tego typu na stosie ani nie używaj operatora new, ponieważ może to spowodować błędy w czasie wykonywania i/lub awarie asercji. Zawsze opakuj tę klasę w wskaźnik [System::SmartPtr](../system/smartptr/) i użyj tego wskaźnika, aby przekazać go do funkcji jako argument. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Wrapper tworzący nieogenericzną implementację [IEnumerator](./ienumerator/) nad generycznym iteratorem [IEnumeratorImplRefType](./ienumeratorimplreftype/) - wrapper dla typów referencyjnych. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Wrapper tworzący nieogenericzną implementację [IEnumerator](./ienumerator/) nad generycznym iteratorem [IEnumeratorImplRefType](./ienumeratorimplreftype/) - wrapper dla typów wartości. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) reprezentuje nieogenericzną kolekcję obiektów, które mogą być indywidualnie dostępne przez indeks. |
| [IListImplRefType](./ilistimplreftype/) | Szablon implementujący interfejs [System::Collections::IList](./ilist/) na obiekcie [System::Collections::Generic::List](../system.collections.generic/list/). Implementacja dla typów referencyjnych. |
| [IListImplValueType](./ilistimplvaluetype/) | Szablon implementujący interfejs [System::Collections::IList](./ilist/) na obiekcie [System::Collections::Generic::List](../system.collections.generic/list/). Implementacja dla typów wartości. |
| [IListWrapper](./ilistwrapper/) | Interfejs umożliwiający rzutowanie z kolekcji generycznej na nieogenericzną. |
| [Invalidatable](./invalidatable/) | Klasa umożliwiająca śledzenie stanu swoich potomków poprzez obiekty [InvalidatableTracker](./invalidatabletracker/). |
| [InvalidatableTracker](./invalidatabletracker/) | Klasa implementująca trackery obiektów [Invalidatable](./invalidatable/). |