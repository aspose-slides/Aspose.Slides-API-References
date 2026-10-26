---
title: InsertClone()
second_title: Aspose.Slides für C++ API Referenz
description: Fügt eine Kopie einer angegebenen Folie an der angegebenen Position der Sammlung ein.
type: docs
weight: 66
url: /de/aspose.slides/slidecollection/insertclone/
---
## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>) Methode


Fügt eine Kopie einer angegebenen Folie an der angegebenen Position der Sammlung ein.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index der neuen Folie. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) zum Klonen. |

### Rückgabewert

Eingefügte Folie.
## Bemerkungen



Beim Klonen einer Folie zwischen verschiedenen Präsentationen kann auch das Master der Folie geklont werden. Ein internes Register wird verwendet, um automatisch geklonte Master zu verfolgen und die Erstellung mehrerer Klone derselben Masterfolie zu verhindern. Das manuelle Klonen von Masterfolien wird weder verhindert noch registriert. Wenn Sie mehr Kontrolle über den Klonvorgang benötigen, verwenden Sie [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<ILayoutSlide>)](../../islidecollection/insertclone/) oder [InsertClone(int32_t, SharedPtr<ISlide>, SharedPtr<IMasterSlide>, bool)](../../islidecollection/insertclone/) zum Klonen von Folien und [IMasterSlideCollection::AddClone(SharedPtr<IMasterSlide>)](../../imasterslidecollection/addclone/) zum Klonen von Mastern. 


Das folgende Beispiel zeigt, wie man innerhalb von [Presentation](../../presentation/) an einer anderen Position klont. 
```cpp
// Instanziieren Sie die Presentation-Klasse, die eine Präsentationsdatei darstellt
auto pres = System::MakeObject<Presentation>(u"CloneWithInSamePresentation.pptx");

// Klonen Sie die gewünschte Folie an das Ende der Folienammlung in derselben Präsentation
System::SharedPtr<ISlideCollection> slides = pres->get_Slides();
// Klonen Sie die gewünschte Folie an den angegebenen Index in derselben Präsentation
slides->InsertClone(2, slides->idx_get(1));
// Speichern Sie die modifizierte Präsentation auf dem Datenträger
pres->Save(u"Aspose_CloneWithInSamePresentation_out.pptx", SaveFormat::Pptx);
```
 Das folgende Beispiel zeigt, wie man innerhalb von [Presentation](../../presentation/) an einer anderen Position klont. 
```cpp
// Instanziieren Sie die Presentation-Klasse, um die Quellpräsentationsdatei zu laden
auto srcPres = System::MakeObject<Presentation>(u"CloneAtEndOfAnother.pptx");

// Instanziieren Sie die Presentation-Klasse für die Ziel-PPTX (in die die Folie geklont wird)
auto destPres = System::MakeObject<Presentation>();

destPres->get_Slides()->InsertClone(2, srcPres->get_Slides()->idx_get(0));
// Schreiben Sie die Zielpräsentation auf die Festplatte
destPres->Save(u"Aspose2_out.pptx", SaveFormat::Pptx);
```

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<ILayoutSlide\>) Methode


Fügt eine Kopie einer angegebenen Folie an der angegebenen Position der Sammlung ein.

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<ILayoutSlide> destLayout) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index der neuen Folie. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) zum Klonen. |
| destLayout | [System::SharedPtr](../../../system/sharedptr/)\<[ILayoutSlide](../../ilayoutslide/)\> | Layout-Folie für die neue Folie. |

### Rückgabewert

Eingefügte Folie.

## SlideCollection::InsertClone(int32_t, System::SharedPtr\<ISlide\>, System::SharedPtr\<IMasterSlide\>, bool) Methode


Fügt eine Kopie einer angegebenen Quellfolie an der angegebenen Position der Sammlung ein. Das passende Layout wird automatisch aus dem angegebenen Master ausgewählt (ein passendes Layout ist das Layout mit demselben Typ oder Namen wie das Layout der Quellfolie). Wenn kein passendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder es wird eine PptxEditException ausgelöst (wenn allowCloneMissingLayout false ist).

```cpp
System::SharedPtr<ISlide> Aspose::Slides::SlideCollection::InsertClone(int32_t index, System::SharedPtr<ISlide> sourceSlide, System::SharedPtr<IMasterSlide> destMaster, bool allowCloneMissingLayout) override
```


### Argumente

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | **int32_t** | Index der neuen Folie. |
| sourceSlide | [System::SharedPtr](../../../system/sharedptr/)\<[ISlide](../../islide/)\> | [Slide](../../slide/) zum Klonen. |
| destMaster | [System::SharedPtr](../../../system/sharedptr/)\<[IMasterSlide](../../imasterslide/)\> | Master-Folie für die neue Folie. |
| allowCloneMissingLayout | **bool** | Wenn im angegebenen Master kein passendes Layout vorhanden ist, wird das Layout der Quellfolie geklont (wenn allowCloneMissingLayout true ist) oder es wird eine PptxEditException ausgelöst (wenn allowCloneMissingLayout false ist). |

### Rückgabewert

Eingefügte Folie.

## Siehe auch

* Typedef [SharedPtr](../../../system/sharedptr/)
* Klasse [ISlide](../../islide/)
* Klasse [SlideCollection](../)
* Klasse [ILayoutSlide](../../ilayoutslide/)
* Klasse [IMasterSlide](../../imasterslide/)
* Namespace [Aspose::Slides](../../)
* Bibliothek [Aspose.Slides](../../../)