---
title: "System::Collections"
second_title: Aspose.Slides für C++ API-Referenz
description: 
type: docs
weight: 300
url: /de/system.collections/
---
## Klassen

| Klasse | Beschreibung |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) von Bits, die per Index adressierbar sind. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/)-Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [BitArrayPtr](./bitarrayptr/) | Zeiger auf [BitArray](./bitarray/). Dieser Typ ist ein Zeiger zur Verwaltung der Löschung anderer Objekte. Er sollte im Stack zugewiesen und an Funktionen entweder per Wert oder per const-Referenz übergeben werden. |
| [CollectionBase](./collectionbase/) | Stellt eine abstrakte Basisklasse für eine stark typisierte Sammlung bereit. |
| [ICollection](./icollection/) | Definiert eine nicht-generische Schnittstelle für Sammlungen. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) ist die Basisschnittstelle für alle nicht-generischen Sammlungen, die enumerierbar sind. |
| [IEnumerator](./ienumerator/) | Schnittstelle eines Enumerators, der zum Durchlaufen einiger Elemente verwendet werden kann. Objekte dieser Klasse sollten nur mit der [System::MakeObject()](../system/makeobject/)-Funktion zugewiesen werden. Erzeugen Sie niemals eine Instanz dieses Typs im Stack oder mit operator new, da dies zu Laufzeitfehlern und/oder Assertion-Fehlern führt. Wickeln Sie diese Klasse stets in einen [System::SmartPtr](../system/smartptr/)-Zeiger ein und verwenden Sie diesen Zeiger, um ihn als Argument an Funktionen zu übergeben. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Wrapper, der eine nicht-generische [IEnumerator](./ienumerator/)-Implementierung über den generischen Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) erstellt – Wrapper für Referenztypen. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Wrapper, der eine nicht-generische [IEnumerator](./ienumerator/)-Implementierung über den generischen Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) erstellt – Wrapper für Werttypen. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) stellt eine nicht-generische Sammlung von Objekten dar, die einzeln per Index zugänglich sind. |
| [IListImplRefType](./ilistimplreftype/) | Stub, der die [System::Collections::IList](./ilist/)-Schnittstelle auf dem [System::Collections::Generic::List](../system.collections.generic/list/)-Objekt implementiert. Implementierung für Referenztypen. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub, der die [System::Collections::IList](./ilist/)-Schnittstelle auf dem [System::Collections::Generic::List](../system.collections.generic/list/)-Objekt implementiert. Implementierung für Werttypen. |
| [IListWrapper](./ilistwrapper/) | Schnittstelle zur Unterstützung des Castings von generischen zu nicht-generischen Sammlungen. |
| [Invalidatable](./invalidatable/) | Klasse, die es ermöglicht, den Zustand ihrer Nachkommen über [InvalidatableTracker](./invalidatabletracker/)-Objekte zu verfolgen. |
| [InvalidatableTracker](./invalidatabletracker/) | Klasse, die Tracker von [Invalidatable](./invalidatable/)-Objekten implementiert. |