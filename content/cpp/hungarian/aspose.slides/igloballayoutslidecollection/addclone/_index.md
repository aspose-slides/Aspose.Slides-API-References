---
title: AddClone()
second_title: Aspose.Slides for C++ API referencia
description: Hozzáad egy másolatot a megadott elrendezési diáról a prezentációhoz.
type: docs
weight: 1
url: /hu/aspose.slides/igloballayoutslidecollection/addclone/
---
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>) metódus


Hozzáad egy másolatot a megadott elrendezési diáról a prezentációhoz.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klónozáshoz. |

### Visszatérési érték

Hozzáadott dia.
## Megjegyzések



Elrendezés klónozása során különböző prezentációk között az elrendezés mestere is klónozható, hogy megőrizze a forrás formázását. Egy belső regisztert használnak az automatikusan klónozott mesterek nyomon követésére, hogy megakadályozzák ugyanazon mesterdia több klónjának létrehozását. A mesterdiák kézi klónozása sem kerül megakadályozásra, sem kerül nyilvántartásba. 
## IGlobalLayoutSlideCollection::AddClone(System::SharedPtr\<ILayoutSlide\>, System::SharedPtr\<IMasterSlide\>) metódus


Hozzáad egy másolatot a megadott elrendezési diáról a prezentációhoz.

```cpp
virtual System::SharedPtr<ILayoutSlide> Aspose::Slides::IGlobalLayoutSlideCollection::AddClone(System::SharedPtr<ILayoutSlide> sourceLayout, System::SharedPtr<IMasterSlide> destMaster)=0
```


### Argumentumok

| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | [Slide](../../slide/) klónozáshoz. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Mester dia az új elrendezéshez. |

### Visszatérési érték

Hozzáadott dia.
## Megjegyzések



Az új elrendezés a célprezentációban meghatározott mesterhez lesz csatolva. Így ez a PowerPoint \"Use Destination Theme\" opciójának megfelelője a másolás/beillesztésnél. 
## Lásd még

* Typedef [SharedPtr](../../../system/sharedptr/)
* Osztály [ILayoutSlide](../../ilayoutslide/)
* Osztály [IGlobalLayoutSlideCollection](../)
* Osztály [IMasterSlide](../../imasterslide/)
* Névtér [Aspose::Slides](../../)
* Könyvtár [Aspose.Slides](../../../)