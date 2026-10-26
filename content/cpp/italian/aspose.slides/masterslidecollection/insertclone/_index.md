---
title: InsertClone()
second_title: Riferimento API di Aspose.Slides per C++
description: Inserisce una copia di una slide master specificata nella posizione specificata della collezione. Le slide di layout collegate verranno copiate anch'esse.
type: docs
weight: 105
url: /it/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) metodo

Inserisce una copia di una slide master specificata nella posizione specificata della collezione. Le slide di layout collegate verranno copiate anch'esse.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### Argomenti

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | **int32_t** | Indice della nuova slide. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) da clonare. |

### Valore di ritorno

Slide master inserita.

## Osservazioni

Il seguente esempio mostra come clonare una slide master in un altro PowerPoint [Presentation](../../presentation/). 
```cpp
// Istanziare la classe Presentation per caricare il file di presentazione di origine
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Istanziare la classe Presentation per la presentazione di destinazione (dove la slide verrà clonata)
auto destPres = System::MakeObject<Presentation>();

// Istanziare ISlide dalla raccolta di slide nella presentazione di origine
// Slide master
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Ottenere le slide master della presentazione di destinazione
auto masters = destPres->get_Masters();
// Clonare la slide master desiderata dalla presentazione di origine nella collezione dei master nella
// Presentazione di destinazione
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Raccolta di slide nella presentazione di destinazione
auto slides = destPres->get_Slides();
// Clonare la slide di origine nella collezione di slide di destinazione.
slides->AddClone(sourceSlide, iSlide, true);
// Salvare la presentazione di destinazione su disco
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Vedi anche

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IMasterSlide](../../imasterslide/)
* Classe [MasterSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Libreria [Aspose.Slides](../../../)