---
title: InsertClone()
second_title: Aspose.Slides C++ API referencia
description: Beszúr egy megadott mesterdia másolatát a gyűjtemény megadott pozíciójába. A kapcsolt elrendezési diákat is másolja.
type: docs
weight: 66
url: /hu/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) metódus


Beszúr egy példányt a megadott mesterdiáról a gyűjtemény megadott pozíciójába. A kapcsolt elrendezési diákat is másolja.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új dia indexe. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) a klónozáshoz. |

### Visszatérési érték

A beszúrt mesterdia.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [IMasterSlide](../../imasterslide/)
* Osztály [IMasterSlideCollection](../)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)