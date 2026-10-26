---
title: ToArray()
second_title: Aspose.Slides für C++ API-Referenz
description: Erstellt und gibt ein Array mit allen Kommentaren zurück.
type: docs
weight: 66
url: /de/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() Methode


Erstellt und gibt ein Array mit allen Kommentaren zurück.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```


### Rückgabewert

Array von [IComment](../../icomment/).

## ICommentCollection::ToArray(int32_t, int32_t) Methode


Erstellt und gibt ein Array mit allen Kommentaren aus dem angegebenen Bereich zurück.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | **int32_t** | Der Index des ersten zurückzugebenden Kommentars. |
| count | **int32_t** | Eine Anzahl von zurückzugebenden Kommentaren. |

### Rückgabewert

Array von [IComment](../../icomment/).

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IComment](../../icomment/)
* Class [ICommentCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)