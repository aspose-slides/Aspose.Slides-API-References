---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een verzameling van alle lay-outdia's in de presentatie voor.
type: docs
url: /nl/com.aspose.slides/globallayoutslidecollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**All Implemented Interfaces:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Stelt een verzameling van alle lay-outdia's in de presentatie voor. Breidt de klasse LayoutSlideCollection uit met methoden voor het toevoegen/kopiëren van lay-outdia's in de context van het samenvoegen van de individuele collecties van de masterlay-outdia's.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Voegt een nieuwe lay-outdia toe aan de presentatie. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te klonen.

--------------------

Bij het klonen van een lay-out tussen verschillende presentaties kan de master van de lay-out ook worden gekloond om de bronopmaak te behouden. Een intern register wordt gebruikt om automatisch gekloonde masters bij te houden om het creëren van meerdere klonen van dezelfde masterdia te voorkomen. Handmatig klonen van masterdia's wordt niet voorkomen of geregistreerd. |

**Retour:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde dia.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```


Voegt een kopie van een opgegeven lay-outdia toe aan de presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te klonen. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterdia voor een nieuwe lay-out.

--------------------

1) Nieuwe lay-out wordt gekoppeld aan de gedefinieerde master in de doelpresentatie. Dit is dus het equivalent van kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint. 2) Het equivalent van deze methode is methode [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) die toegankelijk is via de ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) eigenschap. |

**Retour:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde dia.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```


Voegt een nieuwe lay-outdia toe aan de presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Masterdia voor een nieuwe lay-out. |
| layoutType | byte | Layout type voor een nieuwe lay-out. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als een null-parameter wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven layouttype (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_..", etc.).

--------------------

1) Toegevoegde lay-out voor de waarde SlideLayoutType.Custom van layoutType bevat geen tijdelijke aanduidingen en geen shapes. 2) Het equivalent van deze methode is methode [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) die toegankelijk is via de ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) eigenschap. |

**Retour:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde dia.