---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides voor Java API-referentie
description: Stelt een verzameling van alle lay-outdia's van een gedefinieerde masterdia voor.
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

Stelt een verzameling van alle lay-outdia's van een gedefinieerde masterdia voor. Breidt de LayoutSlideCollection-klasse uit met methoden voor het toevoegen/invoegen/verwijderen/klonen/herordenen van lay-outdia's in de context van de individuele verzamelingen van de lay-outs van de masterdia.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven lay-outdia toe aan het einde van de verzameling. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Voegt een kopie van een opgegeven lay-outdia in op een opgegeven positie in de verzameling. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Voegt een nieuwe lay-outdia toe aan het einde van de verzameling. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Voegt een nieuwe lay-outdia in op een opgegeven positie in de verzameling. |
| [removeAt(int index)](#removeAt-int-) | Verwijdert het element op de opgegeven index van de verzameling. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Verplaatst een lay-outdia van de verzameling naar de opgegeven positie. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Voegt een kopie van een opgegeven lay-outdia toe aan het einde van de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te klonen. |

--------------------

1) Nieuwe lay-out wordt gekoppeld aan de bovenliggende masterdia voor deze lay-outdia-verzameling. Dit is dus het equivalent van kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint. 2) Het equivalent van deze methode is de methode [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) die toegankelijk is via de ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides))-eigenschap.

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde dia.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Voegt een kopie van een opgegeven lay-outdia in op een opgegeven positie in de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van nieuwe dia. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te klonen. |

--------------------

Nieuwe lay-out wordt gekoppeld aan de bovenliggende masterdia voor deze lay-outdia-verzameling. Dit is dus het equivalent van kopiëren/plakken met de optie "Use Destination Theme" in PowerPoint.

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Ingevoegde dia.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Voegt een nieuwe lay-outdia toe aan het einde van de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| layoutType | byte | Lay-outtype voor een nieuwe lay-out. Ondersteunde lay-outtypen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere lay-outtypen worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als een null-parameter wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven lay-outtype (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_…", enz.). |

--------------------

1) Toegevoegde lay-out voor de waarde SlideLayoutType.Custom van layoutType bevat geen placeholders en geen vormen. 2) Het equivalent van deze methode is de methode [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) die toegankelijk is via de ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides))-eigenschap.

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Toegevoegde dia.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Voegt een nieuwe lay-outdia in op een opgegeven positie in de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Index van nieuwe dia. |
| layoutType | byte | Lay-outtype voor een nieuwe lay-out. Ondersteunde lay-outtypen: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Andere lay-outtypen worden momenteel niet ondersteund: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Naam voor een nieuwe lay-out. Als de opgegeven naam al in gebruik is, wordt een ArgumentException gegooid. Als een null-parameter wordt doorgegeven, wordt de naam automatisch gegenereerd op basis van het opgegeven lay-outtype (bijvoorbeeld "Title Slide" of "1_Title Slide", "2_…", enz.). |

--------------------

Ingevoegde lay-out voor de waarde SlideLayoutType.Custom van layoutType bevat geen placeholders en geen vormen.

**Retourwaarde:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Ingevoegde dia.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Verwijdert het element op de opgegeven index van de verzameling.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | De nul-gebaseerde index van het te verwijderen element. |

--------------------

1) Controleer vóór het uitvoeren van deze bewerking de HasDependingSlides-eigenschap van de lay-out om het gooien van een PptxEditException te voorkomen. 2) U kunt ook de methode [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) gebruiken om de code te vereenvoudigen.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Verplaatst een lay-outdia van de verzameling naar de opgegeven positie.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| index | int | Doel-index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Dia om te verplaatsen. |