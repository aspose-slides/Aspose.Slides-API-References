---
title: AddClone()
second_title: Aspose.Slides pro C++ API Reference
description: Přidá kopii zadaného snímku na konec kolekce.
type: docs
weight: 14
url: /cs/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) metoda

Přidá kopii zadaného snímku na konec kolekce.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |

### Návratová hodnota

New slide.

## Poznámky

Při klonování snímku mezi různými prezentacemi může být také klonován master snímku. Interní registr se používá k sledování automaticky klonovaných masterů, aby se zabránilo vytvoření více kopií stejného master snímku. Manuální klonování master snímků nebude ani zabráněno, ani registrováno. Pokud potřebujete větší kontrolu nad procesem klonování, použijte [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) nebo [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) pro klonování snímků, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) nebo [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) pro klonování rozvržení a [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) pro klonování masterů.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) metoda

Přidá kopii zadaného snímku na konec určené sekce.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) pro nový snímek. |

### Návratová hodnota

New slide.

## Poznámky

```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Nyní druhá sekce obsahuje kopii prvního snímku.
```

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metoda

Přidá kopii zadaného snímku na konec kolekce.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout slide pro nový snímek. |

### Návratová hodnota

New slide.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metoda

Přidá kopii zadaného zdrojového snímku na konec kolekce. Vhodné rozvržení bude automaticky vybráno ze zadaného masteru (vhodné rozvržení je rozvržení se stejným Typem nebo názvem jako rozvržení zdrojového snímku). Pokud neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku zkopírováno (pokud je allowCloneMissingLayout nastaveno na true) nebo bude vyhozena výjimka PptxEditException (pokud je allowCloneMissingLayout nastaveno na false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```

### Argumenty

| Parametr | Typ | Popis |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) ke klonování. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide pro nový snímek. |
| allowCloneMissingLayout | **bool** | Pokud v zadaném masteru neexistuje vhodné rozvržení, bude rozvržení zdrojového snímku zkopírováno (pokud je allowCloneMissingLayout nastaveno na true) nebo bude vyhozena výjimka PptxEditException (pokud je allowCloneMissingLayout nastaveno na false). |

### Návratová hodnota

New slide.

## Viz také

* Typedef [SharedPtr](../../../system/sharedptr/)
* Třída [ISlide](../../islide/)
* Třída [ISlideCollection](../)
* Třída [ISection](../../isection/)
* Třída [ILayoutSlide](../../ilayoutslide/)
* Třída [IMasterSlide](../../imasterslide/)
* Jmenný prostor [Aspose::Slides](../../)
* Knihovna [Aspose.Slides](../../../)