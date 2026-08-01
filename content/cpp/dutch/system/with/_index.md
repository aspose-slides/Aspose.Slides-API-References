---
title: With()
second_title: Aspose.Slides voor C++ API Referentie
description: Kloont referentierecord en past de initialisator-functor toe.
type: docs
weight: 2614
url: /nl/system/with/
---
## System::With(const SharedPtr\<T\>\&, const A\&) functie


Kloont referentierecord en past de initialisator-functor toe.

```cpp
template<typename T,typename A> SharedPtr<T> System::With(const SharedPtr<T> &record, const A &initializer)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Record type to clone. |
| A | Initialization functor type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| record | const [SharedPtr](../sharedptr/)\<T\>\& | Shared pointer to the object to clone and initialize. |
| initializer | const A\& | Initialization functor being applied to record clone. |

### Retourwaarde

Gedeelde pointer naar gekloond record.

## System::With(const T\&, const A\&) functie


Kopieert structrecord en past de initialisator-functor toe.

```cpp
template<typename T,typename A> T System::With(const T &record, const A &initializer)
```


### Sjabloonparameters

| Parameter | Beschrijving |
| --- | --- |
| T | Record type to copy. |
| A | Initialization functor type. |

### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| record | const T\& | Record to copy and initialize. |
| initializer | const A\& | Initialization functor being applied to record copy. |

### Retourwaarde

Gekopieerd record.

## Zie ook

* Typedef [SharedPtr](../sharedptr/)
* Naamruimte [System](../)
* Bibliotheek [Aspose.Slides](../../)