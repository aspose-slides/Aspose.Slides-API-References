---
title: AddClone()
second_title: Aspose.Slides C++ API referencia
description: A megadott dia egy másolatát adja a gyűjtemény végéhez.
type: docs
weight: 14
url: /hu/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) metódus


Egy megadott dia másolatát adja a gyűjtemény végéhez.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klónozáshoz. |

### Visszatérési érték

New slide.
## Megjegyzések



Dia másolásakor különböző prezentációk között a dia mesterét is lehet klónozni. Egy belső regiszter van használva az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozzák ugyanazon mesterdia több klónjának létrehozását. A mesterdiák manuális klónozását sem akadályozzák, sem regisztrálják. Ha nagyobb irányítást szeretne a klónozási folyamat felett, használja a [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) vagy [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) dia-klónozáshoz, a [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) vagy [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) elrendezés-klónozáshoz és a [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) mester-klónozáshoz. 
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) metódus


Egy megadott dia másolatát adja a megadott szakasz végéhez.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klónozáshoz. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) új diára. |

### Visszatérési érték

New slide.
## Megjegyzések



```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Most a második szakasz tartalmaz egy másolatot az első diáról.
```


## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metódus


Egy megadott dia másolatát adja a gyűjtemény végéhez.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klónozáshoz. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Elrendezésdia új diára. |

### Visszatérési érték

New slide.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metódus


Egy megadott forrásdia másolatát adja a gyűjtemény végéhez. A megfelelő elrendezés automatikusan ki lesz választva a megadott mestertől (a megfelelő elrendezés az a elrendezés, amelynek típusa vagy neve megegyezik a forrásdia elrendezésével). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha allowCloneMissingLayout **true**), vagy PptxEditException lesz dobva (ha allowCloneMissingLayout **false**).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Argumentumok

| Parameter | Type | Description |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klónozáshoz. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Mesterdia új diára. |
| allowCloneMissingLayout | **bool** | Ha a megadott mesterben nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha allowCloneMissingLayout **true**), vagy PptxEditException lesz dobva (ha allowCloneMissingLayout **false**). |

### Visszatérési érték

New slide.

## Lásd még

* Típusdefiníció [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlide](../../islide/)
* Osztály [ISlideCollection](../)
* Osztály [ISection](../../isection/)
* Osztály [ILayoutSlide](../../ilayoutslide/)
* Osztály [IMasterSlide](../../imasterslide/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)