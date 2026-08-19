---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een verzameling van alle layout-dia's van een gedefinieerde masterdia voor.
type: docs
url: /nl/com.aspose.slides/imasterlayoutslidecollection/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Stelt een verzameling van alle layout-dia's van een gedefinieerde masterdia voor. Breidt de ILayoutSlideCollection-interface uit met methoden voor het toevoegen/invoegen/verwijderen/kopiëren van layout-dia's in de context van de individuele collecties van de master layout-dia's.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven layout-dia toe aan het einde van de collectie. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven layout-dia in op een opgegeven positie van de collectie. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Voegt een nieuwe layout-dia toe aan het einde van de collectie. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Voegt een nieuwe layout-dia in op een opgegeven positie van de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Verplaatst een layout-dia van de collectie naar de opgegeven positie. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Voegt een kopie van een opgegeven layout-dia toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te klonen. |

--------------------

1) Nieuwe layout wordt gekoppeld aan de bovenliggende masterdia voor deze layout-dia-collectie. Dit is dus een equivalent van kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint. 2) Een equivalent van deze methode is de methode [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) die toegankelijk is via de eigenschap [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde dia.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Voegt een kopie van een opgegeven layout-dia in op een opgegeven positie van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de nieuwe dia. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te klonen. |

--------------------

Nieuwe layout wordt gekoppeld aan de bovenliggende masterdia voor deze layout-dia-collectie. Dit is dus een equivalent van kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint.

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Ingevoegde dia.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Voegt een nieuwe layout-dia toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layoutType | byte | Layouttype voor een nieuwe layout. Ondersteunde layouttypes: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere layouttypes worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Naam voor een nieuwe layout. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als een null-parameter wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven layouttype (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_..", etc.). |

--------------------

1) Toegevoegde layout voor de waarde SlideLayoutType.Custom van layoutType bevat geen placeholders en geen shapes. 2) Een equivalent van deze methode is de methode [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) die toegankelijk is via de eigenschap [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde dia.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Voegt een nieuwe layout-dia in op een opgegeven positie van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de nieuwe dia. |
| layoutType | byte | Layouttype voor een nieuwe layout. Ondersteunde layouttypes: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere layouttypes worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Naam voor een nieuwe layout. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als een null-parameter wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven layouttype (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_..", etc.). |

--------------------

Ingevoegde layout voor de waarde SlideLayoutType.Custom van layoutType bevat geen placeholders en geen shapes.

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Ingevoegde dia.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nulgebaseerde index van het te verwijderen element. |

--------------------

1) Om het gooien van de PptxEditException te voorkomen, controleer eerst de HasDependingSlides-eigenschap van de layout. 2) Je kunt ook de methode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) gebruiken om de code te vereenvoudigen.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Verplaatst een layout-dia van de collectie naar de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Doelindex. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te verplaatsen. |