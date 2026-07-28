---
title: CollectionAssertHelper
second_title: Aspose.Slides C++ API referencia
description: Heler API a gyűjteményekkel kapcsolatos műveletekhez.
type: docs
weight: 1548
url: /hu/system/collectionasserthelper/
---
## CollectionAssertHelper struktúra

Heler API a gyűjteményekhez kapcsolódó műveletekhez.

```cpp
class CollectionAssertHelper
```

## Methods

| Metódus | Leírás |
| --- | --- |
| static **bool** [CheckDiffForAll](./checkdiffforall/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Ellenőrzi, hogy a gyűjtemény minden eleme megfelel a predikátumnak. |
| static **bool** [CheckDiffForAny](./checkdiffforany/)(const std::function\<**bool**(int)>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::ICollection](../../system.collections.generic/icollection/)\<**int32_t**\>\>\&) | Ellenőrzi, hogy a gyűjtemény bármely eleme megfelel a predikátumnak. |
| static [System::String](../string/) [CollectionsToMsg](./collectionstomsg/)(const [System::String](../string/)\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Serializálja a két gyűjteményt üzenetábrázoláshoz. |
| static [System::String](../string/) [IEnumerableToStr](./ienumerabletostr/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T\>\>\&) | Átalakítja a gyűjteményt karakterlánccá az elemek karakterlánc-ábrázolásainak összefűzésével. |
| static [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::Dictionary](../../system.collections.generic/dictionary/)\<T1, **int32_t**\>\> [MakeDiff](./makediff/)(const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T1\>\>\&, const [System::SharedPtr](../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../system.collections.generic/ienumerable/)\<T2\>\>\&) | Kiszámítja a két gyűjtemény közti 'diff' értéket. Minden egyes gyűjtemény elemét kulcsként kezelve az eredmény pozitív lesz, ha az elem az "expected" gyűjteményben gyakrabban fordul elő, negatív, ha az "actual" gyűjteményben fordul elő gyakrabban, és nulla, ha az elem minden gyűjteményben egyenlő számú alkalommal fordul elő. |
| static [System::String](../string/) [ToFullMessage](./tofullmessage/)(const [System::String](../string/)\&) | Formázza a karakterláncot, hogy üzenetszövegként használható legyen. |
## Lásd még

* Névtér [System](../)
* Könyvtár [Aspose.Slides](../../)