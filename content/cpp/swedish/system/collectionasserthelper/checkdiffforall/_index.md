---
title: CheckDiffForAll()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar att alla samlingselement följer predikatet.
type: docs
weight: 14
url: /sv/system/collectionasserthelper/checkdiffforall/
---
## CollectionAssertHelper::CheckDiffForAll(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) metod

Kontrollerar att alla samlingselement följer predikatet.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAll(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predikat att kontrollera. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Värden att kontrollera. |

### Returvärde

Falskt om kontrollen misslyckas för något element, sant om alla klarar.

## Se även

* Typdef [SharedPtr](../../sharedptr/)
* Klass [ICollection](../../../system.collections.generic/icollection/)
* Struktur [CollectionAssertHelper](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)