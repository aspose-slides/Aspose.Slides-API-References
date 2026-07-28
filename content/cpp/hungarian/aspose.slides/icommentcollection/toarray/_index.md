---
title: ToArray()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza és visszaad egy tömböt az összes megjegyzéssel.
type: docs
weight: 66
url: /hu/aspose.slides/icommentcollection/toarray/
---
## ICommentCollection::ToArray() metódus

Létrehozza és visszaad egy tömböt az összes megjegyzéssel.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray()=0
```

### Visszatérési érték

[IComment](../../icomment/) tömb.

## ICommentCollection::ToArray(int32_t, int32_t) metódus

Létrehozza és visszaad egy tömböt a megadott tartományban lévő összes megjegyzésből.

```cpp
virtual System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::ICommentCollection::ToArray(int32_t startIndex, int32_t count)=0
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | **int32_t** | Az első visszaadandó megjegyzés indexe. |
| count | **int32_t** | A visszaadandó megjegyzések száma. |

### Visszatérési érték

[IComment](../../icomment/) tömb.

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IComment](../../icomment/)
* Osztály [ICommentCollection](../)
* Névtér [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)