---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides Androidra Java API Referencia
description: Az adott master diához tartozó összes elrendezési dia gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/masterlayoutslidecollection/
---
**Öröklés:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Minden megvalósított interfész:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Representálja a meghatározott mesterdia összes elrendezési diájának gyűjteményét. Kiterjeszti a LayoutSlideCollection osztályt olyan metódusokkal, amelyek a mesterdia elrendezési diáinak egyedi gyűjteményein belül lehetővé teszik elrendezési diák hozzáadását, beszúrását, eltávolítását, clonozását és újrarendezését.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Hozzáad a megadott elrendezési dia egy másolatát a gyűjtemény végéhez. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Beszúr egy másolatot a megadott elrendezési diából a gyűjtemény megadott pozíciójába. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Új elrendezési diát ad hozzá a gyűjtemény végéhez. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Új elrendezési diát szúr be a gyűjtemény megadott pozíciójába. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja az elemét a gyűjtemény megadott indexén. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Áthelyezi az elrendezési diát a gyűjteményből a megadott pozícióba. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Hozzáad a megadott elrendezési dia egy másolatát a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Clonálandó dia. |

--------------------

1) Az új elrendezés a szülő mesterdiához lesz kapcsolva ebben az elrendezési dia gyűjteményben. Ez a PowerPoint "Use Destination Theme" opcióval történő másolás/beillesztés analógiája. 2) Ennek a metódusnak az analógiája a [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) metódus, amely a ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) tulajdonsággal érhető el.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Beszúr egy másolatot a megadott elrendezési diából a gyűjtemény megadott pozíciójába.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Clonálandó dia. |

--------------------

Az új elrendezés a szülő mesterdiához lesz kapcsolva ebben az elrendezési dia gyűjteményben. Ez a PowerPoint "Use Destination Theme" opcióval történő másolás/beillesztés analógiája.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Beszúrt dia.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Új elrendezési diát ad hozzá a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| layoutType | byte | Az új elrendezés típusát határozza meg. Támogatott elrendezéstípusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Jelenleg nem támogatott elrendezéstípusok: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException lesz dobva. Ha null paramétert adunk meg, a név automatikusan generálódik a megadott elrendezéstípus alapján (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

--------------------

1) A SlideLayoutType.Custom értékű, layoutType-hoz tartozó elrendezés nem tartalmaz helyettesítő karaktereket és alakzatokat. 2) Ennek a metódusnak az analógiája a [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) metódus, amely a ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) tulajdonsággal érhető el.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Új elrendezési diát szúr be a gyűjtemény megadott pozíciójába.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| layoutType | byte | Az új elrendezés típusát határozza meg. Támogatott elrendezéstípusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Jelenleg nem támogatott elrendezéstípusok: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException lesz dobva. Ha null paramétert adunk meg, a név automatikusan generálódik a megadott elrendezéstípus alapján (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

--------------------

A SlideLayoutType.Custom értékű, layoutType-hoz tartozó elrendezés nem tartalmaz helyettesítő karaktereket és alakzatokat.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Beszúrt dia.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja az elemét a gyűjtemény megadott indexén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | A törlendő elem nullával kezdődő indexe. |

--------------------

1) A PptxEditException elkerülése érdekében előtte ellenőrizze a layout HasDependingSlides tulajdonságát. 2) A kód egyszerűsítéséhez használhatja a [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) metódust is.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Áthelyezi az elrendezési diát a gyűjteményből a megadott pozícióba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Cél index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Áthelyezendő dia. |