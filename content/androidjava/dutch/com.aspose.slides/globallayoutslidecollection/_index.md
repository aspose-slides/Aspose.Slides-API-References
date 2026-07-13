---
title: GlobalLayoutSlideCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van alle layout-slides in de presentatie voor.
type: docs
url: /nl/com.aspose.slides/globallayoutslidecollection/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Stelt een verzameling van alle layout-slides in de presentatie voor. Breidt de LayoutSlideCollection-klasse uit met methoden voor het toevoegen/kopiëren van layout-slides in de context van het samenvoegen van de individuele collecties van de master-layout-slides.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Adds a copy of a specified layout slide to the presentation. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Adds a copy of a specified layout slide to the presentation. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Adds a new layout slide to the presentation. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Voegt een kopie van een opgegeven layout-slide toe aan de presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide to clone.

--------------------

Wanneer een layout tussen verschillende presentaties wordt gekloond, kan de master van de layout ook worden gekloond om de bronopmaak te behouden. Het interne register wordt gebruikt om automatisch gekloonde masters bij te houden en te voorkomen dat er meerdere klonen van dezelfde master-slide worden aangemaakt. Handmatig klonen van master-slides wordt noch voorkomen noch geregistreerd.

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde slide.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Voegt een kopie van een opgegeven layout-slide toe aan de presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide to clone. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide for a new layout.

--------------------

1) Nieuwe layout wordt gekoppeld aan de gedefinieerde master in de bestemmingspresentatie. Dit is het equivalent van kopiëren/plakken met de optie “Use Destination Theme” in PowerPoint. 2) Het equivalent van deze methode is methode [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) die toegankelijk is via de ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides))-eigenschap.

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde slide.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Voegt een nieuwe layout-slide toe aan de presentatie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide for a new layout. |
| layoutType | byte | Ondersteunde layout-types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere layout-types worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Naam voor de nieuwe layout. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als een null-parameter wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven layout-type (bijvoorbeeld "Title Slide" of "1\_Title Slide", "2\_..", etc.).

--------------------

1) Toegevoegde lay-out voor waarde SlideLayoutType.Custom van layoutType bevat geen tijdelijke aanduidingen en geen vormen. 2) Het equivalent van deze methode is methode [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) die toegankelijk is via de ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides))-eigenschap.

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde slide.