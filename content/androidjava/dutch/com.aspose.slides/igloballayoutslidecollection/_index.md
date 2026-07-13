---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van alle lay-outdia's in de presentatie voor.
type: docs
url: /nl/com.aspose.slides/igloballayoutslidecollection/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Stelt een verzameling van alle lay-outdia's in de presentatie voor. Breidt de ILayoutSlideCollection interface uit met methoden voor het toevoegen/kloon van lay-outdia's in de context van het samenvoegen van de individuele collecties van de master lay-outdia's.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Voegt een nieuwe lay-outdia toe aan de presentatie. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te klonen.

--------------------

Bij het klonen van een lay-out tussen verschillende presentaties kan de lay-out’s master ook gekloond worden om de oorspronkelijke opmaak te behouden. Een intern register wordt gebruikt om automatisch gekloonde masters bij te houden en zo het aanmaken van meerdere kopieën van dezelfde mastersdia te voorkomen. Handmatig klonen van mastersdia’s wordt noch verhinderd noch geregistreerd. |

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde dia.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te klonen. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterdia voor een nieuwe lay-out.

--------------------

Nieuwe lay-out wordt gekoppeld aan de gedefinieerde master in de bestemmingspresentatie. Dit is dus een equivalent van kopiëren/plakken met de optie “Use Destination Theme” in PowerPoint. |

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde dia.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Voegt een nieuwe lay-outdia toe aan de presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterdia voor een nieuwe lay-out. |
| layoutType | byte | Lay-outtype voor een nieuwe lay-out. Ondersteunde lay-outtypes: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere lay-outtypes worden nu niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als null wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven lay-outtype (bijvoorbeeld “Title Slide” of “1_Title Slide”, “2_..” enz.). |

--------------------

1) Toegevoegde lay-out voor de waarde SlideLayoutType.Custom van layoutType bevat geen tijdelijke aanduidingen en geen vormen. 2) Een equivalent van deze methode is methode [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) benaderd via ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) eigenschap. |

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde dia.