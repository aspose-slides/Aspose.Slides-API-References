---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides Java API referencia
description: A meghatározott mesterdia összes elrendezési diáját tartalmazó gyűjteményt képviseli.
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

A megadott mester dia összes elrendezési diáját tartalmazó gyűjteményt képviseli. Kiterjeszti a LayoutSlideCollection osztályt olyan módszerekkel, amelyek lehetővé teszik elrendezési diák hozzáadását/beszúrását/eltávolítását/másolását/újrarendezését a mester elrendezési diáinak egyedi gyűjteményeiben.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Hozzáad egy megadott elrendezési dia másolatát a gyűjtemény végéhez. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Beszúr egy megadott elrendezési dia másolatát a gyűjtemény megadott pozíciójába. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Új elrendezési diát ad hozzá a gyűjtemény végéhez. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Új elrendezési diát szúr be a gyűjtemény megadott pozíciójába. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjtemény megadott indexű elemét. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Áthelyezi az elrendezési diát a gyűjteményből a megadott pozícióba. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Egy megadott elrendezési dia másolatát adja hozzá a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klónozandó dia. |

--------------------

1) Az új elrendezés összekapcsolódik a szülő mester diával ebben az elrendezési diák gyűjteményben. Így ez a másolás/beillesztés analógiája a PowerPointban a "Use Destination Theme" opcióval. 2) Ennek a módszernek az analógja a(z) [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) metódus, amely a ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) tulajdonnal érhető el.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Beszúr egy megadott elrendezési dia másolatát a gyűjtemény megadott pozíciójába.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klónozandó dia. |

--------------------

Az új elrendezés összekapcsolódik a szülő mester diával ebben az elrendezési diák gyűjteményben. Így ez a másolás/beillesztés analógiája a PowerPointban a "Use Destination Theme" opcióval.

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
| layoutType | byte | Az új elrendezés típusát adja meg. Támogatott elrendezési típusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Egyéb elrendezési típusok jelenleg nem támogatottak: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException lesz dobva. Ha null paramétert adnak meg, a név automatikusan generálódik a megadott elrendezési típus alapján (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

--------------------

1) A SlideLayoutType.Custom értékhez hozzáadott elrendezés nem tartalmaz helyettesítőket és alakzatokat. 2) Ennek a módszernek az analógja a(z) [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) metódus, amely a ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)) tulajdonnal érhető el.

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
| layoutType | byte | Az új elrendezés típusát adja meg. Támogatott elrendezési típusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Egyéb elrendezési típusok jelenleg nem támogatottak: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException lesz dobva. Ha null paramétert adnak meg, a név automatikusan generálódik a megadott elrendezési típus alapján (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

--------------------

A SlideLayoutType.Custom értékhez beszúrt elrendezés nem tartalmaz helyettesítőket és alakzatokat.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Beszúrt dia.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Eltávolítja a gyűjtemény megadott indexű elemét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem null-alapú indexe. |

--------------------

1) A PptxEditException elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előtte. 2) Használhatja a [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) metódust is a kód egyszerűsítéséhez.
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