---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van alle layout-slides van een gedefinieerde master-slide voor.
type: docs
url: /nl/com.aspose.slides/masterlayoutslidecollection/
---
**Erfenis:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Stelt een verzameling van alle layout-slides van een gedefinieerde master-slide voor. Breidt de LayoutSlideCollection-klasse uit met methoden voor het toevoegen/invoegen/verwijderen/klonen/herordenen van layout-slides in de context van de individuele collecties van de master-layout-slides.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven layout-slide toe aan het einde van de collectie. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven layout-slide in op een opgegeven positie in de collectie. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Voegt een nieuwe layout-slide toe aan het einde van de collectie. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Voegt een nieuwe layout-slide in op een opgegeven positie in de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index in de collectie. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Verplaatst de layout-slide vanuit de collectie naar de opgegeven positie. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Voegt een kopie van een opgegeven layout-slide toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide om te klonen. |

--------------------

1) Nieuwe lay-out wordt gekoppeld aan de bovenliggende master-slide voor deze lay-out-slide-collectie. Dit is dus een analogie van copy-paste met de optie "Use Destination Theme" in PowerPoint. 2) Een analogie van deze methode is de methode [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) die toegankelijk is via de eigenschap ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) .

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde slide.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Voegt een kopie van een opgegeven layout-slide in op een opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de nieuwe slide. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide om te klonen. |

--------------------

Nieuwe lay-out wordt gekoppeld aan de bovenliggende master-slide voor deze lay-out-slide-collectie. Dit is dus een analogie van copy-paste met de optie "Use Destination Theme" in PowerPoint. 

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Ingevoegde slide.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Voegt een nieuwe layout-slide toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layoutType | byte | Lay-out type voor een nieuwe lay-out. Ondersteunde lay-out types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere lay-out types worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als een null-parameter wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven lay-out type (bijvoorbeeld "Title Slide" of "1\_Title Slide", "2\_..", etc.). |

--------------------

1) Toegevoegde lay-out voor waarde SlideLayoutType.Custom van layoutType bevat geen placeholders en geen shapes. 2) Een analogie van deze methode is de methode [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) die toegankelijk is via de eigenschap ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) .

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde slide.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Voegt een nieuwe layout-slide in op een opgegeven positie in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de nieuwe slide. |
| layoutType | byte | Lay-out type voor een nieuwe lay-out. Ondersteunde lay-out types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere lay-out types worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als een null-parameter wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven lay-out type (bijvoorbeeld "Title Slide" of "1\_Title Slide", "2\_..", etc.). |

--------------------

Ingevoegde lay-out voor de waarde SlideLayoutType.Custom van layoutType bevat geen placeholders en geen shapes. 

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Ingevoegde slide.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het element op de opgegeven index in de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het te verwijderen element. |

--------------------

1) Om het veroorzaken van een PptxEditException te voorkomen, controleer vooraf de eigenschap HasDependingSlides van de lay-out. 2) Je kunt ook de methode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) gebruiken om de code te vereenvoudigen. 

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Verplaatst de layout-slide vanuit de collectie naar de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Doel-index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide om te verplaatsen. |