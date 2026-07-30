---
title: AddClone()
second_title: Aspose.Slides pro C++ – referenční příručka API
description: Přidá kopii určeného snímku na konec kolekce.
type: docs
weight: 53
url: /cs/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) metoda

Přidá kopii určeného snímku na konec kolekce.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |

### Návratová hodnota

Nový snímek.

## Poznámky

Při klonování snímku mezi různými prezentacemi může být také klonován hlavní snímek. Interní registr se používá k sledování automaticky klonovaných hlavních snímků, aby se zabránilo vytvoření více kopií stejného hlavního snímku. Ruční klonování hlavních snímků nebude ani zabráněno, ani registrováno. Pokud potřebujete větší kontrolu nad procesem klonování, použijte [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) nebo [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) pro klonování snímků, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) nebo [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) pro klonování rozvržení a [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) pro klonování hlavních snímků. 

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) metoda

Přidá kopii určeného snímku na konec zadané sekce.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) pro nový snímek. |

### Návratová hodnota

Nový snímek.

## Poznámky

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Nyní druhá sekce obsahuje kopii prvního snímku.
```

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metoda

Přidá kopii určeného snímku na konec kolekce.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Rozvržení snímku pro nový snímek. |

### Návratová hodnota

Nový snímek.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metoda

Přidá kopii určeného zdrojového snímku na konec kolekce. Vhodné rozvržení bude automaticky vybráno ze zadaného hlavního snímku (vhodné rozvržení je rozvržení se stejným Typem nebo názvem jako rozvržení zdrojového snímku). Pokud neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Hlavní snímek pro nový snímek. |
| allowCloneMissingLayout | **bool** | Pokud v zadaném hlavním snímku neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku klonováno (pokud je allowCloneMissingLayout true) nebo bude vyvolána výjimka PptxEditException (pokud je allowCloneMissingLayout false). |

### Návratová hodnota

Nový snímek.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlide](../../islide/)
* Třída [SlideCollection](../)
* Třída [ISection](../../isection/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [IMasterSlide](../../imasterslide/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)