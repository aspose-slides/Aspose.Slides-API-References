---
title: InsertClone()
second_title: Aspose.Slides pro C++ API Reference
description: Vloží kopii určeného master snímku na určenou pozici v kolekci. Propojené rozložení snímků bude také zkopírováno.
type: docs
weight: 105
url: /cs/aspose.slides/masterslidecollection/insertclone/
---
## MasterSlideCollection::InsertClone(int32_t, System::SharedPtr\<IMasterSlide\>) metoda

Vloží kopii určeného master snímku na určenou pozici v kolekci. Propojené rozložení snímků bude také zkopírováno.

```cpp
System::SharedPtr<IMasterSlide> Aspose::Slides::MasterSlideCollection::InsertClone(int32_t index, System::SharedPtr<IMasterSlide> sourceMaster) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| index | **int32_t** | Index nového snímku. |
| sourceMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | [Slide](../../slide/) k klonování. |

### Návratová hodnota

Vložený master snímek.

## Poznámky

Následující příklad ukazuje, jak klonovat master snímek v jiné PowerPoint [Presentation](../../presentation/). 
```cpp
// Vytvořte instanci třídy Presentation pro načtení zdrojového prezentačního souboru
auto srcPres = System::MakeObject<Presentation>(u"CloneToAnotherPresentationWithMaster.pptx");

// Vytvořte instanci třídy Presentation pro cílovou prezentaci (kde bude snímek klonován)
auto destPres = System::MakeObject<Presentation>();

// Vytvořte instanci ISlide ze sbírky snímků ve zdrojové prezentaci spolu s
// Master snímek
auto sourceSlide = srcPres->get_Slides()->idx_get(0);
auto sourceMaster = sourceSlide->get_LayoutSlide()->get_MasterSlide();
// Získat Master snímky cílové prezentace
auto masters = destPres->get_Masters();
// Klonovat požadovaný master snímek ze zdrojové prezentace do sbírky masterů v
// Cílové prezentaci
System::SharedPtr<IMasterSlide> iSlide = masters->AddClone(sourceMaster);
// Sbírka snímků v cílové prezentaci
auto slides = destPres->get_Slides();
// Klonovat zdrojový snímek do sbírky snímků cílové prezentace.
slides->AddClone(sourceSlide, iSlide, true);
// Uložit cílovou prezentaci na disk
destPres->Save(u"CloneToAnotherPresentationWithMaster_out.pptx", SaveFormat::Pptx);
```

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IMasterSlide](../../imasterslide/)
* Class [MasterSlideCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)