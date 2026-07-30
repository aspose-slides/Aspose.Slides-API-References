---
title: "System::Collections"
second_title: Aspose.Slides pro C++ API Reference
description: 
type: docs
weight: 300
url: /cs/system.collections/
---
## Třídy

| Třída | Popis |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) bitů, které lze adresovat pomocí indexu. Objektů této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operator new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [BitArrayPtr](./bitarrayptr/) | Ukazatel na [BitArray](./bitarray/). Tento typ je ukazatel pro správu mazání jiného objektu. Měl by být alokován na zásobníku a předáván funkcím buď hodnotou, nebo jako const reference. |
| [CollectionBase](./collectionbase/) | Poskytuje abstraktní základní třídu pro silně typovanou kolekci. |
| [ICollection](./icollection/) | Definuje rozhraní ne generické kolekce. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) je základní rozhraní pro všechny ne-generické kolekce, které lze enumerovat. |
| [IEnumerator](./ienumerator/) | Rozhraní enumerátoru, který lze použít k iteraci přes některé prvky. Objekty této třídy by měly být alokovány pouze pomocí funkce [System::MakeObject()](../system/makeobject/). Nikdy nevytvářejte instanci tohoto typu na zásobníku ani pomocí operator new, protože to povede k chybám za běhu a/nebo selháním asercí. Vždy zabalte tuto třídu do ukazatele [System::SmartPtr](../system/smartptr/) a použijte tento ukazatel k předání funkci jako argument. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Obal, který vytváří ne-generickou implementaci [IEnumerator](./ienumerator/) nad generickým Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) - obal pro referenční typy. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Obal, který vytváří ne-generickou implementaci [IEnumerator](./ienumerator/) nad generickým Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) - obal pro hodnotové typy. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) představuje ne-generickou kolekci objektů, ke které lze jednotlivě přistupovat pomocí indexu. |
| [IListImplRefType](./ilistimplreftype/) | Stub, který implementuje rozhraní [System::Collections::IList](./ilist/) na objektu [System::Collections::Generic::List](../system.collections.generic/list/). Implementace pro referenční typy. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub, který implementuje rozhraní [System::Collections::IList](./ilist/) na objektu [System::Collections::Generic::List](../system.collections.generic/list/). Implementace pro hodnotové typy. |
| [IListWrapper](./ilistwrapper/) | Rozhraní pro podporu přetypování z generické na ne-generickou kolekci. |
| [Invalidatable](./invalidatable/) | Třída, která umožňuje sledovat stav svých potomků prostřednictvím objektů [InvalidatableTracker](./invalidatabletracker/). |
| [InvalidatableTracker](./invalidatabletracker/) | Třída, která implementuje sledovače objektů [Invalidatable](./invalidatable/). |