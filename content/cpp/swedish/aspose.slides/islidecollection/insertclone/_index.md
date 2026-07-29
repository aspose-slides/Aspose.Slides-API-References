---
title: InsertClone()
second_title: Aspose.Slides för C++ API-referens
description: Infogar en kopia av en angiven bild på en specificerad position i samlingen.
type: docs
weight: 27
url: /sv/aspose.slides/islidecollection/insertclone/
---
## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) metod


Infogar en kopia av en angiven bild på en specificerad position i samlingen.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för den nya bilden. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |

### Returvärde

Infogad bild.

## Anmärkningar



När en bild klonas mellan olika presentationer kan bildens master också klonas. Ett internt register används för att spåra automatiskt klonade masterbilder för att förhindra att flera kloner av samma masterbild skapas. Manuell kloning av masterbilder förhindras inte och registreras inte. Om du behöver mer kontroll över kloningsprocessen, använd [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) eller [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) för att klona bilder och [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) för att klona masterbilder. 

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) metod


Infogar en kopia av en angiven bild på en specificerad position i samlingen.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för den nya bilden. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout-bild för en ny bild. |

### Returvärde

Infogad bild.

## ISlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) metod


Infogar en kopia av en angiven källbild på en specificerad position i samlingen. Lämplig layout kommer att väljas automatiskt från den angivna masteren (en lämplig layout är den layout som har samma Typ eller Namn som layouten för källbilden). Om det saknas en lämplig layout kommer layouten för källbilden att klonas (om allowCloneMissingLayout är true) eller så kastas ett PptxEditException (om allowCloneMissingLayout är false).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Argument

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | **int32_t** | Index för den nya bilden. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) att klona. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master-bild för en ny bild. |
| allowCloneMissingLayout | **bool** | Om det inte finns någon lämplig layout i den angivna masteren så klonas layouten för källbilden (om allowCloneMissingLayout är true) eller så kastas ett PptxEditException (om allowCloneMissingLayout är false). |

### Returvärde

Infogad bild.

## Se också

* Typdefinition [SharedPtr](../../../system/sharedptr/)
* Klass [ISlide](../../islide/)
* Klass [ISlideCollection](../)
* Klass [ILayoutSlide](../../ilayoutslide/)
* Klass [IMasterSlide](../../imasterslide/)
* Namnområde [Aspose::Slides](../../)
* Bibliotek [Aspose.Slides](../../../)