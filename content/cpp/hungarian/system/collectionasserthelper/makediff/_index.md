---
title: MakeDiff()
second_title: Aspose.Slides C++ API referencia
description: Kiszámítja a 'diff'-et két gyűjtemény között. Minden gyűjtemény minden elemére kulcsként a kapott érték pozitív lesz, ha az elem többször fordul elő a \"expected\" gyűjteményben, negatív, ha az elem többször fordul elő a \"actual\" gyűjteményben, és nulla, ha az elem egyenlő számban fordul elő mindkét gyűjteményben.
type: docs
weight: 1
url: /hu/system/collectionasserthelper/makediff/
---
## CollectionAssertHelper::MakeDiff(const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) metódus

Kiszámítja a 'diff'-et két gyűjtemény között. Minden gyűjtemény minden eleméről kulcsként a kapott érték pozitív lesz, ha az elem többször fordul elő a "expected" gyűjteményben, negatív, ha az elem többször fordul elő a "actual" gyűjteményben, és nulla, ha az elem egyenlő számban fordul elő mindkét gyűjteményben.

```cpp
template<typename T1,typename T2> static System::SharedPtr<System::Collections::Generic::Dictionary<T1, int32_t>> System::CollectionAssertHelper::MakeDiff(const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A várt gyűjtemény elem típusa. |
| T2 | A tényleges gyűjtemény elem típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | A várt gyűjtemény. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | A tényleges gyűjtemény. |

### Visszatérési érték

Az egyes értékek összehasonlítási eredményeinek térképe a fent leírt szabályok alapján.

## Lásd még

* Típusdefiníció [SharedPtr](../../sharedptr/)
* Osztály [Dictionary](../../../system.collections.generic/dictionary/)
* Osztály [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktúra [CollectionAssertHelper](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)