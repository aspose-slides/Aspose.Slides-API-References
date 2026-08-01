---
title: CollectionsToMsg()
second_title: Aspose.Slides voor C++ API-referentie
description: Serialiseert twee collecties voor berichtrepresentatie.
type: docs
weight: 53
url: /nl/system/collectionasserthelper/collectionstomsg/
---
## CollectionAssertHelper::CollectionsToMsg(const System::String\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T1\>\>\&, const System::SharedPtr\<System::Collections::Generic::IEnumerable\<T2\>\>\&) method


Serialiseert twee collecties voor berichtrepresentatie.

```cpp
template<typename T1,typename T2> static System::String System::CollectionAssertHelper::CollectionsToMsg(const System::String &extra_msg, const System::SharedPtr<System::Collections::Generic::IEnumerable<T1>> &expected, const System::SharedPtr<System::Collections::Generic::IEnumerable<T2>> &actual)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T1 | Verwacht type van collectie-element. |
| T2 | Werkelijk type van collectie-element. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| extra_msg | const [System::String](../../string/)\& | Een aangepaste tekenreeks die wordt ingevoegd vóór de verwachte waarde in het resulterende bericht |
| expected | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T1\>\>\& | Verwachte collectie. |
| actual | const [System::SharedPtr](../../sharedptr/)\<[System::Collections::Generic::IEnumerable](../../../system.collections.generic/ienumerable/)\<T2\>\>\& | Werkelijke collectie. |

### Retourwaarde

Gebruiksvriendelijke bericht over de inhoud van de collecties.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Klasse [IEnumerable](../../../system.collections.generic/ienumerable/)
* Struct [CollectionAssertHelper](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)