---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides Androidhoz Java API referencia
description: A meghatározott fődia összes elrendezési diájának gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/imasterlayoutslidecollection/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

A meghatározott mesterdia diában definiált összes elrendezési diát képviseli. Kiterjeszti az ILayoutSlideCollection interfészt olyan módszerekkel, amelyek hozzáadnak/beszúrnak/eltávolítanak/klónoznak elrendezési diákot a mesterdia elrendezési diáinak egyedi gyűjteményeiben.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Hozzáad egy megadott elrendezési dia másolatát a gyűjtemény végéhez. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Beszúr egy megadott elrendezési dia másolatát a gyűjtemény megadott pozíciójába. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Új elrendezési diát ad hozzá a gyűjtemény végéhez. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Új elrendezési diát szúr be a gyűjtemény megadott pozíciójába. |
| [removeAt(int index)](#removeAt-int-) | Eltávolítja a gyűjteményben a megadott indexű elemet. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Áthelyezi az elrendezési diát a gyűjteményből a megadott pozícióba. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Hozzáad egy megadott elrendezési dia másolatát a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klónozandó dia. |

1) Az új elrendezés a szülő fődia-hoz lesz kapcsolva ebben az elrendezési dia gyűjteményben. Így ez a PowerPoint "Use Destination Theme" opcióval történő másolás/beillesztés analógiája. 2) Ennek a módszernek az analógiája a(z) [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) metódus, amely a [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) tulajdonsággal érhető el.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Beszúr egy megadott elrendezési dia másolatát a gyűjtemény megadott pozíciójába.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klónozandó dia. |

Az új elrendezés a szülő fődia-hoz lesz kapcsolva ebben az elrendezési dia gyűjteményben. Így ez a PowerPoint "Use Destination Theme" opcióval történő másolás/beillesztés analógiája.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Beszúrt dia.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Új elrendezési diát ad hozzá a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| layoutType | byte | Elrendezés típusa egy új elrendezéshez. Támogatott elrendezési típusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Egyéb elrendezési típusok jelenleg nem támogatottak: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException lesz dobva. Ha null értékű paramétert ad át, a név automatikusan lesz generálva a megadott layoutType alapján (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

1) A SlideLayoutType.Custom értékhez tartozó hozzáadott elrendezés nem tartalmaz helyőrzőket és alakzatokat. 2) Ennek a módszernek az analógiája a(z) [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) metódus, amely a [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) tulajdonsággal érhető el.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Beszúr egy új elrendezési diát a gyűjtemény megadott pozíciójába.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| layoutType | byte | Elrendezés típusa egy új elrendezéshez. Támogatott elrendezési típusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Egyéb elrendezési típusok jelenleg nem támogatottak: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException lesz dobva. Ha null értékű paramétert ad át, a név automatikusan lesz generálva a megadott layoutType alapján (például "Title Slide" vagy "1_Title Slide", "2_..", stb.). |

A SlideLayoutType.Custom értékhez tartozó beszúrt elrendezés nem tartalmaz helyőrzőket és alakzatokat.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Beszúrt dia.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Eltávolítja a gyűjteményben a megadott indexű elemet.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nulla-alapú indexe. |

1) Az PptxEditException dobásának elkerülése érdekében először ellenőrizze a layout HasDependingSlides tulajdonságát. 2) A kód egyszerűsítéséhez használhatja a(z) [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) metódust is.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Áthelyezi az elrendezési diát a gyűjteményből a megadott pozícióba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Cél index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Áthelyezendő dia. |