---
title: AddClone()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu.
type: docs
weight: 14
url: /de/aspose.slides/islidecollection/addclone/
---
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>) method


Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) zu klonen. |

### Rückgabewert

Neue Folie.
## Bemerkungen



Beim Klonen einer Folie zwischen verschiedenen Präsentationen kann der Master der Folie ebenfalls geklont werden. Ein internes Register wird verwendet, um automatisch geklonte Master zu verfolgen und die Erstellung mehrerer Klone desselben Master-Folien zu verhindern. Manuelles Klonen von Master-Folien wird weder verhindert noch registriert. Wenn Sie mehr Kontrolle über den Klonvorgang benötigen, verwenden Sie [AddClone(SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](./) oder [AddClone(SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](./) zum Klonen von Folien, [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>)](../../igloballayoutslidecollection/addclone/) oder [IGlobalLayoutSlideCollection::AddClone(SharedPtr<ILayoutSlide>, SharedPtr<IMasterSlide>)](../../igloballayoutslidecollection/addclone/) zum Klonen von Layouts und [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) zum Klonen von Mastern. 
## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ISection\>) method


Fügt eine Kopie einer angegebenen Folie am Ende des angegebenen Abschnitts hinzu.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ISection> section)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) zu klonen. |
| section | [System::SharedPtr](../../../system/sharedptr/)\<[ISection](../../isection/)\> | [Section](../../section/) für eine neue Folie. |

### Rückgabewert

Neue Folie.
## Bemerkungen



```cpp
auto presentation = MakeObject<Presentation>();
presentation->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 200.0f, 50.0f, 300.0f, 100.0f);
presentation->get_Sections()->AddSection(u"Section 1", presentation->get_Slides()->idx_get(0));
auto section2 = presentation->get_Sections()->AppendEmptySection(u"Section 2");
presentation->get_Slides()->AddClone(presentation->get_Slides()->idx_get(0), section2);
// Jetzt enthält der zweite Abschnitt eine Kopie der ersten Folie.
```


## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) method


Fügt eine Kopie einer angegebenen Folie am Ende der Sammlung hinzu.

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) zu klonen. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout-Folie für eine neue Folie. |

### Rückgabewert

Neue Folie.

## ISlideCollection::AddClone(System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) method


Fügt eine Kopie einer angegebenen Quellfolie am Ende der Sammlung hinzu. Das passende Layout wird automatisch aus dem angegebenen Master ausgewählt (ein passendes Layout ist das Layout mit dem gleichen Typ oder Namen wie das Layout der Quellfolie). Wenn kein passendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout wahr ist) oder eine PptxEditException ausgelöst (wenn allowCloneMissingLayout falsch ist).

```cpp
virtual System::SharedPtr<ISlide> Aspose::Slides::ISlideCollection::AddClone(System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout)=0
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) zu klonen. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master-Folie für eine neue Folie. |
| allowCloneMissingLayout | **bool** | Wenn im angegebenen Master kein passendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout wahr ist) oder es wird eine PptxEditException ausgelöst (wenn allowCloneMissingLayout falsch ist). |

### Rückgabewert

Neue Folie.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [ISlideCollection](../)
* Klasse [ISection](../../isection/)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterSlide](../../imasterslide/)
* Namensraum [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)