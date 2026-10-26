---
title: "System::Collections"
second_title: Aspose.Slides C++ API-referencia
description: 
type: docs
weight: 300
url: /hu/system.collections/
---
## Osztályok

| Osztály | Leírás |
| --- | --- |
| [BitArray](./bitarray/) | [Array](../system/array/) bitek, amelyek index alapján címezhetők. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az new operátor használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való függvényeknek való átadásra. |
| [BitArrayPtr](./bitarrayptr/) | Mutató a [BitArray](./bitarray/)-ra. Ez a típus egy mutató, amely más objektumok törlését kezeli. Ezt a stacken kell lefoglalni, és függvényeknek vagy értékként, vagy const referenciaként kell átadni. |
| [CollectionBase](./collectionbase/) | Absztrakt alaposztályt biztosít egy erősen típusos gyűjteményhez. |
| [ICollection](./icollection/) | Nem generikus gyűjteményinterfészt definiál. |
| [IEnumerable](./ienumerable/) | [IEnumerable](./ienumerable/) az alapinterfész minden felsorolható nem generikus gyűjteményhez. |
| [IEnumerator](./ienumerator/) | Az enumerátor interfésze, amelyet elemek bejárására lehet használni. Ennek az osztálynak az objektumait csak a [System::MakeObject()](../system/makeobject/) függvény használatával szabad lefoglalni. Soha ne hozzon létre példányt ebből a típusból a stacken vagy az new operátor használatával, mivel ez futásidejű hibákat és/vagy állítási hibákat eredményez. Mindig csomagolja be ezt az osztályt egy [System::SmartPtr](../system/smartptr/) pointerbe, és használja ezt a pointert az argumentumként való függvényeknek való átadásra. |
| [IEnumeratorImplRefType](./ienumeratorimplreftype/) | Olyan becsomagoló, amely nem generikus [IEnumerator](./ienumerator/) implementációt hoz létre a generikus Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) fölött – referencia típusokhoz tartozó becsomagoló. |
| [IEnumeratorImplValueType](./ienumeratorimplvaluetype/) | Olyan becsomagoló, amely nem generikus [IEnumerator](./ienumerator/) implementációt hoz létre a generikus Iterator [IEnumeratorImplRefType](./ienumeratorimplreftype/) fölött – értéktípusokhoz tartozó becsomagoló. |
| [IEqualityComparer](./iequalitycomparer/) |  |
| [IList](./ilist/) | [IList](./ilist/) egy nem generikus objektumgyűjteményt képvisel, amely egyes elemeket index szerint érhet el. |
| [IListImplRefType](./ilistimplreftype/) | Csontváz, amely a [System::Collections::IList](./ilist/) interfészt valósítja meg egy [System::Collections::Generic::List](../system.collections.generic/list/) objektumon – referencia típusok implementációja. |
| [IListImplValueType](./ilistimplvaluetype/) | Csontváz, amely a [System::Collections::IList](./ilist/) interfészt valósítja meg egy [System::Collections::Generic::List](../system.collections.generic/list/) objektumon – értéktípusok implementációja. |
| [IListWrapper](./ilistwrapper/) | Interfész a generikus és nem generikus gyűjtemény közötti átkonvertálás támogatásához. |
| [Invalidatable](./invalidatable/) | Osztály, amely lehetővé teszi leszármazottjai állapotának követését [InvalidatableTracker](./invalidatabletracker/) objektumokon keresztül. |
| [InvalidatableTracker](./invalidatabletracker/) | Osztály, amely a [Invalidatable](./invalidatable/) objektumok nyomkövetőit valósítja meg. |