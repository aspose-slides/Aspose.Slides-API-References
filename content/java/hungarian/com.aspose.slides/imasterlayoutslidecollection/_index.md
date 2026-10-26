---
title: IMasterLayoutSlideCollection
second_title: Aspose.Slides a Java API referenciája
description: Az adott mesterdia meghatározott összes elrendezésdiájának gyűjteményét képviseli.
type: docs
url: /hu/com.aspose.slides/imasterlayoutslidecollection/
---
**Minden megvalósított interfész:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Az adott mester dia definiált összes elrendezésdiaszóló gyűjteményét képviseli. Kiterjeszti az ILayoutSlideCollection interfészt módszerekkel az elrendezésdiák hozzáadására/beszúrására/eltávolítására/másolására a mester elrendezésdiai gyűjteményének egyedi gyűjteményeiben.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Adds a copy of a specified layout slide to the end of the collection. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Inserts a copy of a specified layout slide to specified position of the collection. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Adds a new layout slide to the end of the collection. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Inserts a new layout slide to specified position of the collection. |
| [removeAt(int index)](#removeAt-int-) | Removes the element at the specified index of the collection. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Moves layout slide from the collection to the specified position. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Másolatot ad hozzá a megadott elrendezésdiáról a gyűjtemény végén.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klónozandó dia.

--------------------

1) Az új elrendezés a szülő mester diával lesz összekapcsolva ezen elrendezésdiák gyűjteményéhez. Ez tehát a másolás/beillesztés analógiája a PowerPointban lévő "Use Destination Theme" opciónál. 2) Ennek a módszernek az analógiája a [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) metódus, a [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) tulajdonsággal érhető el.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```


Beszúr egy másolatot a megadott elrendezésdiáról a gyűjtemény megadott pozíciójába.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Klónozandó dia.

--------------------

Az új elrendezés a szülő mester diával lesz összekapcsolva ezen elrendezésdiák gyűjteményéhez. Ez tehát a másolás/beillesztés analógiája a PowerPointban lévő "Use Destination Theme" opcionál.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Beszúrt dia.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```


Új elrendezésdiai diát ad hozzá a gyűjtemény végéhez.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| layoutType | byte | Az új elrendezés típusát adja meg. Támogatott elrendezés típusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Jelenleg nem támogatott elrendezés típusok: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException kerül dobásra. Ha null paramétert adunk meg, a név automatikusan generálódik a megadott elrendezés típusnak megfelelően (például "Title Slide" vagy "1\_Title Slide", "2\_..", stb.). |

--------------------

1) A SlideLayoutType.Custom értékhez hozzáadott elrendezésnem tartalmaz helyőrzőket és alakzatokat. 2) Ennek a módszernek az analógiája a [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) metódus, a [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides) tulajdonsággal érhető el.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Hozzáadott dia.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```


Beszúr egy új elrendezésdiai diát a gyűjtemény megadott pozíciójába.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az új dia indexe. |
| layoutType | byte | Az új elrendezés típusát adja meg. Támogatott elrendezés típusok: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Jelenleg nem támogatott elrendezés típusok: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Az új elrendezés neve. Ha a megadott név már használatban van, ArgumentException kerül dobásra. Ha null paramétert adunk meg, a név automatikusan generálódik a megadott elrendezés típusnak megfelelően (például "Title Slide" vagy "1\_Title Slide", "2\_..", stb.). |

--------------------

A SlideLayoutType.Custom értékhez beszúrt elrendezés nem tartalmaz helyőrzőket és alakzatokat.

**Visszatérési érték:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Beszúrt dia.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```


Eltávolítja a gyűjtemény megadott indexű elemét.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Az eltávolítandó elem nullárol indexelt (zero-based) indexe.

--------------------

1) A PptxEditException dobásának elkerülése érdekében ellenőrizze a layout HasDependingSlides tulajdonságát előtte. 2) A [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) metódus is használható a kód egyszerűsítéséhez.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```


Áthelyezi az elrendezésdiát a gyűjteményből a megadott pozícióba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| index | int | Cél index. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Áthelyezendő dia. |