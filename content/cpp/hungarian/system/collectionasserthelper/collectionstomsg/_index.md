---
title: CollectionsToMsg()
second_title: Aspose.Slides for C++ API referencia
description: Két gyűjteményt sorosít az üzenetábrázoláshoz.
type: docs
weight: 53
url: /hu/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) metódus

Két gyűjteményt sorosít a üzenetábrázoláshoz.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```

### Sablonparaméterek

| Paraméter | Leírás |
| --- | --- |
| T1 | A várt gyűjteményelemek típusa. |
| T2 | A tényleges gyűjteményelemek típusa. |

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | Egy egyedi sztring, amely a várt érték előtt kerül beillesztésre az eredményül kapott üzenetben |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Várható gyűjtemény. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Aktuális gyűjtemény. |

### Visszatérési érték

Felhasználóbarát üzenet a gyűjtemények tartalmáról.

## Lásd még

* Typedef [SharedPtr](../../sharedptr/)
* Osztály [String](../../string/)
* Osztály [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struktúra [CollectionAssertHelper](../)
* Névtér [System](../../)
* Könyvtár [Aspose.Slides](../../../)