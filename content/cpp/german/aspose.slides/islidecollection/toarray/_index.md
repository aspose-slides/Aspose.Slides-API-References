---
title: ToArray()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt ein Array mit allen Folien und gibt es zurück.
type: docs
weight: 92
url: /de/aspose.slides/islidecollection/toarray/
---
## ISlideCollection::ToArray() Methode


Erstellt ein Array mit allen Folien und gibt es zurück.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray()=0
```


### Rückgabewert

Array von [ISlide](../../islide/)

## ISlideCollection::ToArray(int32_t, int32_t) Methode


Erstellt ein Array mit allen Folien aus dem angegebenen Bereich und gibt es zurück.

```cpp
virtual System::ArrayPtr<System::SharedPtr<ISlide>> Aspose::Slides::ISlideCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | **int32_t** | Ein Index der ersten Folie, die hinzugefügt werden soll. |
| count | **int32_t** | Eine Anzahl von Folien, die hinzugefügt werden sollen. |

### Rückgabewert

Array von [ISlide](../../islide/)

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [ISlideCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)