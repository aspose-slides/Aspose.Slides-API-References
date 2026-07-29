---
title: "System::Collections"
second_title: Aspose.Slides för C++ API-referens
description: 
type: docs
weight: 300
url: /sv/system.collections/
---
## Klasser

| Klass | Beskrivning |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) av bitar som kan adresseras med index. Objekt av den här klassen bör endast allokeras med [System::MakeObject()](../system/makeobject/) funktion. Skapa aldrig en instans av den här typen på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller påståendedefekter. Omslut alltid den här klassen med [System::SmartPtr](../system/smartptr/) pekare och använd den pekaren för att skicka den till funktioner som argument. |
| [BitArrayPtr](./bitarrayptr/) | Pekare till [BitArray](./bitarray/). Denna typ är en pekare för att hantera andras objekts borttagning. Den bör allokeras på stacken och skickas till funktioner antingen som värde eller som konstant referens. |
| [CollectionBase](./collectionbase/) | Tillhandahåller en abstrakt basklass för en starkt typad samling. |
| [ICollection](./icollection/) | Definierar ett icke generiskt samlingsgränssnitt. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) är basgränssnittet för alla icke-generiska samlingar som kan enumereras. |
| [IEnumerator](./ienumerator/) | Gränssnitt för en enumerator som kan användas för att iterera genom vissa element. Objekt av den här klassen bör endast allokeras med [System::MakeObject()](../system/makeobject/) funktion. Skapa aldrig en instans av den här typen på stacken eller med operator new, eftersom det kan leda till körningsfel och/eller påståendedefekter. Omslut alltid den här klassen med [System::SmartPtr](../system/smartptr/) pekare och använd den pekaren för att skicka den till funktioner som argument. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Omslag som skapar en icke-generisk [IEnumerator](./ienumerator/) implementation över den generiska Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) – omslag för referenstyper. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Omslag som skapar en icke-generisk [IEnumerator](./ienumerator/) implementation över den generiska Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) – omslag för värdetyper. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) Representerar en icke-generisk samling av objekt som kan nås individuellt via index. |
| [IListImplRefType](./ilistimplreftype/) | Stub som implementerar [System::Collections::IList](./ilist/) gränssnitt på [System::Collections::Generic::List](../system.collections.generic/list/) objekt Implementering för referenstyper. |
| [IListImplValueType](./ilistimplvaluetype/) | Stub som implementerar [System::Collections::IList](./ilist/) gränssnitt på [System::Collections::Generic::List](../system.collections.generic/list/) objekt Implementering för värdetyper. |
| [IListWrapper](./ilistwrapper/) | Gränssnitt för att stödja typkonvertering från generisk till icke-generisk samling. |
| [Invalidatable](./invalidatable/) | Klass som möjliggör att spåra tillståndet för dess efterkommande genom [InvalidatableTracker](./invalidatabletracker/) objekt. |
| [InvalidatableTracker](./invalidatabletracker/) | Klass som implementerar spårare för [Invalidatable](./invalidatable/) objekt. |