---
title: InsertClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce una copia di una diapositiva specificata nella posizione specificata della collezione.
type: docs
weight: 27
url: /it/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) method

Inserisce una copia di una diapositiva specificata nella posizione specificata della collezione.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice della nuova diapositiva. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |

### Valore di ritorno

Diapositiva inserita.

## Osservazioni

Quando si clona una diapositiva tra presentazioni diverse, anche il master della diapositiva può essere clonato. Un registro interno viene utilizzato per tenere traccia dei master clonati automaticamente per evitare la creazione di più cloni dello stesso master di diapositiva. Il cloning manuale dei master delle diapositive non verrà né impedito né registrato. Se hai bisogno di un controllo maggiore sul processo di cloning, usa [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) o [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) per clonare le diapositive e [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) per clonare i master. 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method

Inserisce una copia di una diapositiva specificata nella posizione specificata della collezione.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice della nuova diapositiva. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Diapositiva di layout per una nuova diapositiva. |

### Valore di ritorno

Diapositiva inserita.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method

Inserisce una copia di una diapositiva sorgente specificata nella posizione specificata della collezione. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva sorgente). Se non esiste un layout appropriato, il layout della diapositiva sorgente sarà clonato (se allowCloneMissingLayout è true) o verrà sollevata una PptxEditException (se allowCloneMissingLayout è false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice della nuova diapositiva. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Diapositiva master per una nuova diapositiva. |
| allowCloneMissingLayout | **bool** | Se non esiste un layout appropriato nel master specificato, il layout della diapositiva sorgente sarà clonato (se allowCloneMissingLayout è true) o verrà sollevata una PptxEditException (se allowCloneMissingLayout è false). |

### Valore di ritorno

Diapositiva inserita.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [ISlideCollection](../)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterSlide](../../imasterslide/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)