---
title: ToArray()
second_title: Aspose.Slides voor C++ API-referentie
description: Maakt een array met alle opmerkingen aan en retourneert deze.
type: docs
weight: 105
url: /nl/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() methode


Maakt en retourneert een array met alle opmerkingen.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```


### Retourwaarde

Array van [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) methode


Maakt en retourneert een array met alle opmerkingen uit het opgegeven bereik.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Argumenten

| Parameter | Type | Beschrijving |
| --- | --- | --- |
| startIndex | **int32_t** | Een index van de eerste opmerking die moet worden geretourneerd. |
| count | **int32_t** | Het aantal opmerkingen dat moet worden geretourneerd. |

### Retourwaarde

Array van [Comment](../../comment/).

## Zie ook

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComment](../../icomment/)
* Klasse [CommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)