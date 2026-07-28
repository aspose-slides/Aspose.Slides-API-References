---
title: ToArray()
second_title: Aspose.Slides C++ API referencia
description: Létrehozza és visszaad egy tömböt az összes megjegyzéssel.
type: docs
weight: 105
url: /hu/aspose.slides/commentcollection/toarray/
---
## CommentCollection::ToArray() metódus


Létrehozza és visszaad egy tömböt az összes megjegyzéssel.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray() override
```


### Visszatérési érték

Tömb a [Comment](../../comment/).

## CommentCollection::ToArray(int32_t, int32_t) metódus


Létrehozza és visszaad egy tömböt a megadott tartományban lévő összes megjegyzéssel.

```cpp
System::ArrayPtr<System::SharedPtr<IComment>> Aspose::Slides::CommentCollection::ToArray(int32_t startIndex, int32_t count) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| startIndex | **int32_t** | Az első visszaadandó megjegyzés indexe. |
| count | **int32_t** | A visszaadandó megjegyzések száma. |

### Visszatérési érték

Tömb a [Comment](../../comment/).

## Lásd még

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IComment](../../icomment/)
* Osztály [CommentCollection](../)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)