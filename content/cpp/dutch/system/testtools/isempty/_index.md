---
title: IsEmpty()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of de string leeg is.
type: docs
weight: 14
url: /nl/system/testtools/isempty/
---
## TestTools::IsEmpty(const System::String\&) method


Controleert of de string leeg is.

```cpp
static bool System::TestTools::IsEmpty(const System::String &str)
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) om te controleren op leeg zijn. |

### Retourwaarde

True als de string leeg is (null-length), false anders.

## TestTools::IsEmpty(const SharedPtr\<T\>\&) method


Controleert of de collectie leeg is.

```cpp
template<typename T> static bool System::TestTools::IsEmpty(const SharedPtr<T> &collection)
```


### Template-parameters

| Parameter | Beschrijving |
| --- | --- |
| T | Collectietype. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Collectie om te controleren. |

### Retourwaarde

True als de collectie nul elementen bevat, false anders.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Struct [TestTools](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)