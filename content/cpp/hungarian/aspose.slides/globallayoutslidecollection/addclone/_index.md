---
title: AddClone()
second_title: Aspose.Slides C++ API hivatkozás
description: Hozzáad egy megadott elrendezési dia másolatát a prezentációhoz.
type: docs
weight: 1
url: /hu/aspose.slides/globallayoutslidecollection/addclone/
---
## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metódus

Hozzáad egy megadott elrendezési dia másolatát a prezentációhoz.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klónozáshoz. |

### Visszatérési érték

Hozzáadott dia.

## Megjegyzések

Különböző prezentációk között elrendezés klónozása esetén a layout mesterét is lehet klónozni a forrásformázás megtartása érdekében. Egy belső regiszter használatos az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozza ugyanazon mester dia több példányának létrehozását. A mesterdia kézi klónozását sem akadályozzák, sem nem regisztrálják.

## GlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) metódus

Hozzáad egy megadott elrendezési dia másolatát a prezentációhoz.

```cpp
System::SharedPtr<ILayoutSlide> Aspose::Slides::GlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster) override
```

### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klónozáshoz. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master slide for a new layout. |

### Visszatérési érték

Hozzáadott dia.

## Megjegyzések

1) Az új elrendezés a célprezentációban megadott mesterrel lesz összekapcsolva. Ez tehát a PowerPoint "Use Destination Theme" opcióval ellátott másolás/beillesztés analógja. 2) Ennek a metódusnak az analógja a [IMasterLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../imasterlayoutslidecollection/addclone/) metódus, amely a [IMasterSlide::get_LayoutSlides()](../../imasterslide/get_layoutslides/) tulajdonnal érhető el. 

## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ILayoutSlide](../../ilayoutslide/)
* Osztály [GlobalLayoutSlideCollection](../)
* Osztály [IMasterSlide](../../imasterslide/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)