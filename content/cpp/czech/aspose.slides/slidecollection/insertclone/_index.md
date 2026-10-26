---
title: InsertClone()
second_title: Aspose.Slides pro C++ – API Reference
description: Vloží kopii určeného snímku na zadanou pozici ve sbírce.
type: docs
weight: 66
url: /cs/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) metoda


Vloží kopii zadaného snímku na určenou pozici ve sbírce.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového snímku. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |

### Návratová hodnota

Vložený snímek.

## Poznámky



Při klonování snímku mezi různými prezentacemi může být klonován také hlavní snímek. Interní registr se používá k sledování automaticky klonovaných hlavních snímků, aby se zabránilo vytvoření více kopií stejného hlavního snímku. Ruční klonování hlavních snímků nebude ani zabráněno, ani zaznamenáno. Pokud potřebujete větší kontrolu nad procesem klonování, použijte [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) nebo [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) pro klonování snímků a [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) pro klonování hlavních snímků. 


Následující příklad ukazuje, jak klonovat na jiné pozici v rámci [Presentation](../../presentation/). 
```cpp
// Vytvořte třídu Presentation, která představuje soubor prezentace
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Zkopírujte požadovaný snímek na konec kolekce snímků ve stejné prezentaci
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Zkopírujte požadovaný snímek na zadaný index ve stejné prezentaci
slides->InsertClone(2, slides->idx_get(1));
// Uložte upravenou prezentaci na disk
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 Následující příklad ukazuje, jak klonovat na jiné pozici v rámci [Presentation](../../presentation/). 
```cpp
// Instancujte třídu Presentation pro načtení zdrojového souboru prezentace
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Instancujte třídu Presentation pro cílový PPTX (kde bude snímek klonován)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Uložte cílovou prezentaci na disk
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metoda


Vloží kopii zadaného snímku na určenou pozici ve sbírce.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového snímku. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Rozložení snímku pro nový snímek. |

### Návratová hodnota

Vložený snímek.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metoda


Vloží kopii zadaného zdrojového snímku na určenou pozici ve sbírce. Vhodné rozložení bude automaticky vybráno ze zadaného hlavního snímku (vhodné rozložení je rozložení se stejným Type nebo Name jako rozložení zdrojového snímku). Pokud neexistuje vhodné rozložení, bude rozložení zdrojového snímku klonováno (pokud je allowCloneMissingLayout pravda) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout nepravda).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového snímku. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Hlavní snímek pro nový snímek. |
| allowCloneMissingLayout | **bool** | Pokud neexistuje vhodné rozložení ve zvoleném hlavním snímku, bude rozložení zdrojového snímku klonováno (pokud je allowCloneMissingLayout pravda) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout nepravda). |

### Návratová hodnota

Vložený snímek.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlide](../../islide/)
* Třída [SlideCollection](../)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [IMasterSlide](../../imasterslide/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)