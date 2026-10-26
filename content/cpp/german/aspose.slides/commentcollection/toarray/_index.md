---
title: ToArray()
second_title: Aspose.Slides für C++ API Referenz
description: Erstellt und gibt ein Array mit allen Kommentaren zurück.
type: docs
weight: 105
url: /de/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() Methode

Erstellt und gibt ein Array mit allen Kommentaren zurück.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```

### Rückgabewert

Array von [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) Methode

Erstellt und gibt ein Array mit allen Kommentaren aus dem angegebenen Bereich zurück.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```

### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| startIndex | **int32_t** | Ein Index des ersten zurückzugebenden Kommentars. |
| count | **int32_t** | Eine Anzahl von zurückzugebenden Kommentaren. |

### Rückgabewert

Array von [Comment](../../comment/).

## Siehe auch

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [IComment](../../icomment/)
* Klasse [CommentCollection](../)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)