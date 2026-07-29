---
title: CollectionsToMsg()
second_title: Aspose.Slides för C++ API-referens
description: Serialiserar två samlingar för meddelanderepresentation.
type: docs
weight: 53
url: /sv/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) metod

Serialiserar två samlingar för meddelanderepresentation.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Mallparametrar

| Parameter | Beskrivning |
| --- | --- |
| T1 | Förväntad samlingselementtyp. |
| T2 | Faktisk samlingselementtyp. |

### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | En anpassad sträng som infogas före det förväntade värdet i det resulterande meddelandet |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Förväntad samling. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Faktisk samling. |

### Returvärde

Användarvänligt meddelande om samlingarnas innehåll.

## Se även

* Typedef [SharedPtr](../../sharedptr/)
* Klass [String](../../string/)
* Klass [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktur [CollectionAssertHelper](../)
* Namnrymd [System](../../)
* Bibliotek [Aspose.Slides](../../../)