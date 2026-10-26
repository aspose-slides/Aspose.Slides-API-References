---
title: MasterLayoutSlideCollection
second_title: Riferimento API Aspose.Slides per Java
description: Rappresenta una collezione di tutte le diapositive di layout della diapositiva master definita.
type: docs
url: /it/com.aspose.slides/masterlayoutslidecollection/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Tutte le interfacce implementate:**
[com.aspose.slides.IMasterLayoutSlideCollection](../../com.aspose.slides/imasterlayoutslidecollection)
```
public final class MasterLayoutSlideCollection extends LayoutSlideCollection implements IMasterLayoutSlideCollection
```

Rappresenta una raccolta di tutte le diapositive di layout di una diapositiva master definita. Estende la classe LayoutSlideCollection con metodi per aggiungere/inserire/rimuovere/clonare/riordinare le diapositive di layout nel contesto delle collezioni individuali delle diapositive di layout del master.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Aggiunge una copia di una diapositiva di layout specificata alla fine della collezione. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Inserisce una copia di una diapositiva di layout specificata nella posizione specificata della collezione. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Aggiunge una nuova diapositiva di layout alla fine della collezione. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Inserisce una nuova diapositiva di layout nella posizione specificata della collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della collezione. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Sposta la diapositiva di layout dalla collezione alla posizione specificata. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Aggiunge una copia di una diapositiva di layout specificata alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva da clonare. |

--------------------

1) Nuovo layout sarà collegato alla diapositiva master padre per questa collezione di layout. È l'analogo di copia/incolla con l'opzione "Use Destination Theme" in PowerPoint. 2) L'analogo di questo metodo è il metodo [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) accessibile tramite la proprietà ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.

### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Inserisce una copia di una diapositiva di layout specificata nella posizione specificata della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva da clonare. |

--------------------

Nuovo layout sarà collegato alla diapositiva master padre per questa collezione di layout. È l'analogo di copia/incolla con l'opzione "Use Destination Theme" in PowerPoint.

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva inserita.

### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public final ILayoutSlide add(byte layoutType, String layoutName)
```

Aggiunge una nuova diapositiva di layout alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layoutType | byte | Tipo di layout per un nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome per un nuovo layout. Se il nome fornito è già in uso verrà sollevata un'ArgumentException. Se il parametro è null, il nome viene generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" o "1_Title Slide", "2_..", ecc.). |

--------------------

1) Layout aggiunto per il valore SlideLayoutType.Custom di layoutType non contiene segnaposti né forme. 2) L'analogo di questo metodo è il metodo [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) accessibile tramite la proprietà ([IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides)).

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.

### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public final ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Inserisce una nuova diapositiva di layout nella posizione specificata della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova diapositiva. |
| layoutType | byte | Tipo di layout per un nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome per un nuovo layout. Se il nome fornito è già in uso verrà sollevata un'ArgumentException. Se il parametro è null, il nome viene generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" o "1_Title Slide", "2_..", ecc.). |

--------------------

Layout inserito per il valore SlideLayoutType.Custom di layoutType non contiene segnaposti né forme.

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva inserita.

### removeAt(int index) {#removeAt-int-}
```
public final void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

--------------------

1) Per evitare il lancio di PptxEditException verifica prima la proprietà HasDependingSlides del layout. 2) È anche possibile utilizzare il metodo [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) per semplificare il codice.

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public final void reorder(int index, ILayoutSlide layoutSlide)
```

Sposta la diapositiva di layout dalla collezione alla posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di destinazione. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva da spostare. |