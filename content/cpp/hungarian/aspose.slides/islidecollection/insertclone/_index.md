---
title: InsertClone()
second_title: Aspose.Slides C++ API referencia
description: Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába.
type: docs
weight: 27
url: /hu/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) metódus


Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új dia indexe. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klónozáshoz. |

### Visszatérési érték

Beszúrt dia.

## Megjegyzés



Különböző bemutatók között dia klónozása esetén a dia mesterét is lehet klónozni. Belső regisztert használnak az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozzák ugyanazon mesterdia több klónjának létrehozását. A mesterdiák manuális klónozását sem akadályozzák meg, sem nem regisztrálják. Ha nagyobb ellenőrzésre van szükség a klónozási folyamat felett, használja a [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) vagy [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) elemeket diák klónozásához, és a [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) elemet mesterek klónozásához. 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metódus


Beszúr egy megadott dia másolatát a gyűjtemény megadott pozíciójába.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új dia indexe. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klónozáshoz. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Elrendezésdia egy új diához. |

### Visszatérési érték

Beszúrt dia.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metódus


Beszúr egy megadott forrásdia másolatát a gyűjtemény megadott pozíciójába. A megfelelő elrendezés automatikusan ki lesz választva a megadott mesterből (a megfelelő elrendezés az a layout, amelynek típusa vagy neve megegyezik a forrásdia elrendezésével). Ha nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), vagy PptxEditException lesz dobva (ha az allowCloneMissingLayout hamis).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | **int32_t** | Az új dia indexe. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) klónozáshoz. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Mesterdia egy új diához. |
| allowCloneMissingLayout | **bool** | Ha a megadott mesterben nincs megfelelő elrendezés, akkor a forrásdia elrendezése lesz klónozva (ha az allowCloneMissingLayout igaz), vagy PptxEditException lesz dobva (ha az allowCloneMissingLayout hamis). |

### Visszatérési érték

Beszúrt dia.

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ISlide](../../islide/)
* Osztály [ISlideCollection](../)
* Osztály [ILayoutSlide](../../ilayoutslide/)
* Osztály [IMasterSlide](../../imasterslide/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)