---
title: IsNullOrEmpty()
second_title: Aspose.Slides voor C++ API-referentie
description: Controleert of de collectie null is of leeg.
type: docs
weight: 27
url: /nl/system/testtools/isnullarempty/
---
## TestTools::IsNullOrEmpty(const SharedPtr\<T\>\&) method


Controleert of de collectie null is of leeg.

```cpp
template<typename T> static bool System::TestTools::IsNullOrEmpty(const SharedPtr<T> &collection)
```


### Sjabloonparameters

| Parameter | Description |
| --- | --- |
| T | Collectietype. |

### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| collection | const [SharedPtr](../../sharedptr/)\<T\>\& | Collectie om te controleren. |

### Retourwaarde

True als de collectie null is of een elemententelling van nul heeft, false anders.

## TestTools::IsNullOrEmpty(const System::String\&) method


Controleert of de string null is of leeg.

```cpp
static bool System::TestTools::IsNullOrEmpty(const System::String &str)
```


### Argumenten

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [System::String](../../string/)\& | [String](../../string/) om te controleren. |

### Retourwaarde

True als de string null is of een lengte van nul heeft, false anders.

## Zie ook

* Typedef [SharedPtr](../../sharedptr/)
* Klasse [String](../../string/)
* Struct [TestTools](../)
* Naamruimte [System](../../)
* Bibliotheek [Aspose.Slides](../../../)