---
title: AddClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Aggiunge una copia di una diapositiva specificata alla fine della raccolta.
type: docs
weight: 14
url: /it/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) metodo


Aggiunge una copia di una diapositiva specificata alla fine della raccolta.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |

### Valore di ritorno

Nuova diapositiva.

## Note



Quando si clona una diapositiva tra presentazioni diverse, il master della diapositiva può essere clonato anch'esso. Un registro interno è usato per tracciare i master clonato automaticamente per evitare la creazione di più copie dello stesso master. Il clonaggio manuale dei master non sarà né impedito né registrato. Se è necessario un controllo più dettagliato sul processo di clonazione, usare [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) o [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) per clonare le diapositive, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) o [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) per clonare i layout e [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) per clonare i master. 

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) metodo


Aggiunge una copia di una diapositiva specificata alla fine della sezione specificata.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) per una nuova diapositiva. |

### Valore di ritorno

Nuova diapositiva.

## Note



```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Ora la seconda sezione contiene una copia della prima diapositiva.
```


## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metodo


Aggiunge una copia di una diapositiva specificata alla fine della raccolta.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Slide di layout per una nuova diapositiva. |

### Valore di ritorno

Nuova diapositiva.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metodo


Aggiunge una copia di una diapositiva di origine specificata alla fine della raccolta. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è quello con lo stesso Tipo o Nome del layout della diapositiva di origine). Se non esiste un layout appropriato, il layout della diapositiva di origine sarà clonato (se allowCloneMissingLayout è true) oppure verrà sollevata PptxEditException (se allowCloneMissingLayout è false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Argomenti

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Slide master per una nuova diapositiva. |
| allowCloneMissingLayout | **bool** | Se non esiste un layout appropriato nel master specificato, allora il layout della diapositiva di origine sarà clonato (se allowCloneMissingLayout è true) oppure verrà sollevata PptxEditException (se allowCloneMissingLayout è false). |

### Valore di ritorno

Nuova diapositiva.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [ISlideCollection](../)
* Classe [ISection](../../isection/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)