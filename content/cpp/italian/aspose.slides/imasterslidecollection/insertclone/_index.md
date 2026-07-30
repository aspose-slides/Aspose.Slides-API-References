---
title: InsertClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce una copia di una diapositiva master specificata nella posizione specificata della raccolta. Anche le diapositive di layout collegate verranno copiate.
type: docs
weight: 66
url: /it/aspose.slides/imasterslidecollection/insertclone/
---
## IMasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) metodo

Inserisce una copia di una diapositiva master specificata nella posizione specificata della raccolta. Le diapositive di layout collegate verranno copiate anch'esse.

```cpp
virtual System::SharedPtr<IMasterSlide> Aspose::Slides::IMasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice della nuova diapositiva. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) da clonare. |

### Valore restituito

Diapositiva master inserita.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMasterSlide](../../imasterslide/)
* Classe [IMasterSlideCollection](../)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)