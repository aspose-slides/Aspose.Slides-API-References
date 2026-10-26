---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt een verzameling van alle lay-outdia's van een gedefinieerde masterslide voor.
type: docs
url: /nl/com.aspose.slides/imasterlayoutslidecollection/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Stelt een verzameling van alle lay-outdia's van een gedefinieerde masterslide voor. Breidt de ILayoutSlideCollection-interface uit met methoden voor het toevoegen/invoegen/verwijderen/kopiëren van lay-outdia's in de context van de afzonderlijke collecties van de lay-outs van de master.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven lay-outdia toe aan het einde van de collectie. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven lay-outdia in op een opgegeven positie van de collectie. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Voegt een nieuwe lay-outdia toe aan het einde van de collectie. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Voegt een nieuwe lay-outdia in op een opgegeven positie van de collectie. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de collectie. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Verplaatst de lay-outdia van de collectie naar de opgegeven positie. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Voegt een kopie van een opgegeven lay-outdia toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te klonen. |

--------------------

1) Nieuwe lay-out wordt gekoppeld aan de bovenliggende masterslide voor deze lay-outdia-collectie. Dit is dus een equivalent van kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint. 2) Equivalent van deze methode is methode [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) toegankelijk via de [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)-eigenschap.

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde dia.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Voegt een kopie van een opgegeven lay-outdia in op een opgegeven positie van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de nieuwe dia. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te klonen. |

--------------------

Nieuwe lay-out wordt gekoppeld aan de bovenliggende masterslide voor deze lay-outdia-collectie. Dit is dus een equivalent van kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint.

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Ingevoegde dia.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Voegt een nieuwe lay-outdia toe aan het einde van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layoutType | byte | Lay-outtype voor een nieuwe lay-out. Ondersteunde lay-outtypes: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere lay-outtypes worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als de parameter null is, wordt de naam automatisch gegenereerd op basis van het opgegeven lay-outtype (bijvoorbeeld "Title Slide" of "1\_Title Slide", "2\_..", enz.). |

--------------------

1) Toegevoegde lay-out voor de waarde SlideLayoutType.Custom van layoutType bevat geen placeholders en geen vormen. 2) Equivalent van deze methode is methode [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) toegankelijk via de [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)-eigenschap.

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde dia.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Voegt een nieuwe lay-outdia in op een opgegeven positie van de collectie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van de nieuwe dia. |
| layoutType | byte | Lay-outtype voor een nieuwe lay-out. Ondersteunde lay-outtypes: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere lay-outtypes worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als de parameter null is, wordt de naam automatisch gegenereerd op basis van het opgegeven lay-outtype (bijvoorbeeld "Title Slide" of "1\_Title Slide", "2\_..", enz.). |

--------------------

Ingevoegde lay-out voor de waarde SlideLayoutType.Custom van layoutType bevat geen placeholders en geen vormen.

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

1) Om het gooien van de PptxEditException te voorkomen, controleer eerst de HasDependingSlides-eigenschap van de lay-out. 2) Je kunt ook de [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove)-methode gebruiken om de code te vereenvoudigen.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Verplaatst de lay-outdia van de collectie naar de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Doelindex. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te verplaatsen. |