---
title: MasterLayoutSlideCollection
second_title: Aspose.Slides per Android via Java API Reference
description: Rappresenta una raccolta di tutte le diapositive layout di una master slide definita.
type: docs
url: /it/com.aspose.slides/masterlayoutslidecollection/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**All Implemented Interfaces:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Rappresenta una raccolta di tutte le diapositive layout di una master slide definita. Estende la classe LayoutSlideCollection con metodi per aggiungere/inserire/rimuovere/clonare/riordinare le diapositive layout nel contesto delle collezioni individuali delle diapositive layout del master.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Aggiunge una copia di una diapositiva layout specificata alla fine della raccolta. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Inserisce una copia di una diapositiva layout specificata nella posizione indicata della raccolta. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Aggiunge una nuova diapositiva layout alla fine della raccolta. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Inserisce una nuova diapositiva layout nella posizione specificata della raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della raccolta. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Sposta la diapositiva layout dalla raccolta alla posizione specificata. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```


Aggiunge una copia di una diapositiva layout specificata alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva da clonare.

--------------------

1) Il nuovo layout sarà collegato alla master slide padre per questa raccolta di diapositive layout. È quindi l'analogo di copia/incolla con l'opzione "Usa tema destinazione" in PowerPoint. 2) L'analogo di questo metodo è il metodo [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) accessibile con la proprietà ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)). |

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```


Inserisce una copia di una diapositiva layout specificata nella posizione indicata della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva da clonare.

--------------------

Il nuovo layout sarà collegato alla master slide padre per questa raccolta di diapositive layout. È quindi l'analogo di copia/incolla con l'opzione "Usa tema destinazione" in PowerPoint. |

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva inserita.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```


Aggiunge una nuova diapositiva layout alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layoutType | byte | Tipo di layout per il nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome per il nuovo layout. Se il nome fornito è già in uso verrà sollevata un'ArgumentException. Se viene passato null, il nome verrà generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" o "1_Title Slide", "2_..", ecc.).

--------------------

1) Il layout aggiunto per il valore SlideLayoutType.Custom di layoutType non contiene segnaposti né forme. 2) L'analogo di questo metodo è il metodo [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) accessibile con la proprietà ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)). |

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```


Inserisce una nuova diapositiva layout nella posizione specificata della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| layoutType | byte | Tipo di layout per il nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome per il nuovo layout. Se il nome fornito è già in uso verrà sollevata un'ArgumentException. Se viene passato null, il nome verrà generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" o "1_Title Slide", "2_..", ecc.).

--------------------

Il layout inserito per il valore SlideLayoutType.Custom di layoutType non contiene segnaposti né forme. |

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva inserita.
### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```


Rimuove l'elemento all'indice specificato della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere.

--------------------

1) Per evitare il lancio di PptxEditException controllare prima la proprietà HasDependingSlides del layout. 2) È possibile utilizzare anche il metodo [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) per semplificare il codice. |

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```


Sposta la diapositiva layout dalla raccolta alla posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di destinazione. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva da spostare. |