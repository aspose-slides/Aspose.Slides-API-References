---
title: AddClone()
second_title: Riferimento API Aspose.Slides per C++
description: Aggiunge una copia di una diapositiva specificata alla fine della raccolta.
type: docs
weight: 53
url: /it/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) metodo


Aggiunge una copia di una diapositiva specificata alla fine della raccolta.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |

### Valore restituito

Nuova diapositiva.
## Note



Durante la clonazione di una diapositiva tra presentazioni diverse, il master della diapositiva può essere clonato anch'esso. Viene utilizzato un registro interno per tenere traccia dei master clonati automaticamente e prevenire la creazione di più cloni dello stesso master. La clonazione manuale dei master non è né impedita né registrata. Se è necessario un maggiore controllo sul processo di clonazione, utilizzare [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) o [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) per clonare le diapositive, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) o [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) per clonare i layout e [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) per clonare i master. 
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) metodo


Aggiunge una copia di una diapositiva specificata alla fine della sezione specificata.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) per una nuova diapositiva. |

### Valore restituito

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


## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metodo


Aggiunge una copia di una diapositiva specificata alla fine della raccolta.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout slide per una nuova diapositiva. |

### Valore restituito

Nuova diapositiva.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metodo


Aggiunge una copia di una diapositiva sorgente specificata alla fine della raccolta. Il layout appropriato verrà selezionato automaticamente dal master specificato (il layout appropriato è il layout con lo stesso Tipo o Nome del layout della diapositiva sorgente). Se non esiste un layout appropriato, il layout della diapositiva sorgente verrà clonato (se allowCloneMissingLayout è true) o verrà sollevata un'eccezione PptxEditException (se allowCloneMissingLayout è false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) da clonare. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide per una nuova diapositiva. |
| allowCloneMissingLayout | **bool** | Se non esiste un layout appropriato nel master specificato, il layout della diapositiva sorgente verrà clonato (se allowCloneMissingLayout è true) o verrà sollevata un'eccezione PptxEditException (se allowCloneMissingLayout è false). |

### Valore restituito

Nuova diapositiva.

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [ISlide](../../islide/)
* Classe [SlideCollection](../)
* Classe [ISection](../../isection/)
* Classe [ILayoutSlide](../../ilayoutslide/)
* Classe [IMasterSlide](../../imasterslide/)
* Spazio dei nomi [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)