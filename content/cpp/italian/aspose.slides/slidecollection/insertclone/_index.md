---
title: InsertClone()
second_title: Riferimento API Aspose.Slides per C++
description: Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta.
type: docs
weight: 66
url: /it/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) method

Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice della nuova diapositiva. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |

### Valore restituito

Diapositiva inserita.

## Osservazioni

Quando si clona una diapositiva tra presentazioni diverse, il master della diapositiva può essere clonato anche esso. Un registro interno viene utilizzato per tracciare i master clonati automaticamente per evitare la creazione di più copie dello stesso master di diapositiva. Il clonaggio manuale dei master di diapositiva non sarà né impedito né registrato. Se è necessario un maggiore controllo sul processo di clonazione, utilizzare [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) o [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) per clonare le diapositive e [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) per clonare i master.

Il seguente esempio mostra come clonare in un'altra posizione all'interno di [Presentation](../../presentation/). 
```cpp
// Istanzia la classe Presentation che rappresenta un file di presentazione
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Clona la diapositiva desiderata alla fine della collezione di diapositive nella stessa presentazione
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Clona la diapositiva desiderata all'indice specificato nella stessa presentazione
slides->InsertClone(2, slides->idx_get(1));
// Scrivi la presentazione modificata su disco
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 Il seguente esempio mostra come clonare in un'altra posizione all'interno di [Presentation](../../presentation/). 
```cpp
// Istanzia la classe Presentation per caricare il file di presentazione sorgente
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Istanzia la classe Presentation per il PPTX di destinazione (dove la diapositiva deve essere clonata)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Scrivi la presentazione di destinazione su disco
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method

Inserisce una copia di una diapositiva specificata nella posizione specificata della raccolta.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice della nuova diapositiva. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Diapositiva di layout per una nuova diapositiva. |

### Valore restituito

Diapositiva inserita.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method

Inserisce una copia di una diapositiva sorgente specificata nella posizione specificata della raccolta. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva sorgente). Se non esiste un layout appropriato nel master specificato, il layout della diapositiva sorgente sarà clonato (se allowCloneMissingLayout è true) o sarà sollevata PptxEditException (se allowCloneMissingLayout è false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice della nuova diapositiva. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slide master per una nuova diapositiva. |
| allowCloneMissingLayout | **bool** | Se non esiste un layout appropriato nel master specificato, il layout della diapositiva sorgente sarà clonato (se allowCloneMissingLayout è true) o sarà sollevata PptxEditException (se allowCloneMissingLayout è false). |

### Valore restituito

Diapositiva inserita.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ISlide](../../islide/)
* Class [SlideCollection](../)
* Class [ILayoutSlide](../../ilayoutslide/)
* Class [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)