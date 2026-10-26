---
title: CheckDiffForAny()
second_title: Aspose.Slides för C++ API-referens
description: Kontrollerar att något element i samlingen uppfyller predikatet.
type: docs
weight: 27
url: /sv/system/collectionasserthelper/checkdiffforany/
---
## CollectionAssertHelper::CheckDiffForAny(const std::function\<bool(int)>\&, const System::SharedPtr\<System::Collections::Generic::ICollection\<int32_t\>\>\&) metod

Kontrollerar att något element i samlingen uppfyller predikatet.

```cpp
static bool System::CollectionAssertHelper::CheckDiffForAny(const std::function<bool(int)> &pred, const System::SharedPtr<System::Collections::Generic::ICollection<int32_t>> &values)
```

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pred | const std::function\<**bool**(int)>\& | Predikat att kontrollera. |
| values | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::ICollection](../../../system.collections.generic/icollection/)\<**int32_t**\>\>\& | Värden att kontrollera. |

### Returvärde

Sant om kontrollen lyckas för något element, falskt om alla passerar.

## Se även

* Typdefinition [SharedPtr](../../sharedptr/)
* Klass [ICollection](../../../system.collections.generic/icollection/)
* Struktur [CollectionAssertHelper](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)