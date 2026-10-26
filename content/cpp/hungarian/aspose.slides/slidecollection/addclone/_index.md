---
title: AddClone()
second_title: Aspose.Slides C++ API hivatkozás
description: Hozzáad egy megadott dia másolatát a gyűjtemény végéhez.
type: docs
weight: 53
url: /hu/aspose.slides/slidecollection/addclone/
---
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>) metódus


Hozzáad egy megadott dia másolatát a gyűjtemény végéhez.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) to clone. |

### Visszatérési érték

Új dia.

## Megjegyzések



Dia másolásakor különböző bemutatók között a dia mester is másolható. Egy belső nyilvántartást használnak az automatikusan másolt mesterek nyomon követésére, hogy megakadályozzák ugyanazon mesterdia többszörös másolását. A mesterdia kézi másolását sem akadályozzák, sem regisztrálják. Ha nagyobb irányítást szeretne a másolási folyamat felett, használja a [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/addclone/) vagy a [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/addclone/) metódusokat dia másolásához, a [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) vagy a [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) metódusokat elrendezés másolásához és a [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) metódust mesterdia másolásához. 
## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) metódus


Hozzáad egy megadott dia másolatát a megadott szakasz végéhez.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) to clone. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) for a new slide. |

### Visszatérési érték

Új dia.

## Megjegyzések



```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Most a második szakasz tartalmazza az első dia másolatát.
```


## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metódus


Hozzáad egy megadott dia másolatát a gyűjtemény végéhez.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) to clone. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout slide for a new slide. |

### Visszatérési érték

Új dia.

## SlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metódus


Hozzáad egy megadott forrásdia másolatát a gyűjtemény végéhez. A megfelelő elrendezés automatikusan kiválasztásra kerül a megadott mesterből (a megfelelő elrendezés az, amelynek azonos típusa vagy neve van a forrásdia elrendezésével). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése másolásra kerül (ha az allowCloneMissingLayout igaz), vagy PptxEditException kivétel dobódik (ha az allowCloneMissingLayout hamis).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) to clone. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide for a new slide. |
| allowCloneMissingLayout | **bool** | If there is no appropriate layout in specified master then layout of the source slide will be cloned (if allowCloneMissingLayout is true) or PptxEditException will be thrown (if allowCloneMissingLayout is false). |

### Visszatérési érték

Új dia.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlide](../../islide/)
* Osztály [SlideCollection](../)
* Osztály [ISection](../../isection/)
* Osztály [ILayoutSlide](../../ilayoutslide/)
* Osztály [IMasterSlide](../../imasterslide/)
* Névterület [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)