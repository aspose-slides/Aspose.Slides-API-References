---
title: IMasterLayoutSlideCollection
second_title: Riferimento API Java per Aspose.Slides per Android
description: Rappresenta una collezione di tutte le slide di layout di una master slide definita.
type: docs
url: /it/com.aspose.slides/imasterlayoutslidecollection/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Rappresenta una collezione di tutte le slide di layout di una master slide definita. Estende l'interfaccia ILayoutSlideCollection con metodi per aggiungere/inserire/rimuovere/clonare le slide di layout nel contesto delle singole collezioni di layout della master slide.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Aggiunge una copia di una slide di layout specificata alla fine della collezione. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Inserisce una copia di una slide di layout specificata nella posizione indicata della collezione. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Aggiunge una nuova slide di layout alla fine della collezione. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Inserisce una nuova slide di layout nella posizione indicata della collezione. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della collezione. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Sposta la slide di layout dalla collezione alla posizione specificata. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Aggiunge una copia di una slide di layout specificata alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide da clonare. |

--------------------
1) Il nuovo layout sarà collegato alla master slide padre per questa collezione di slide di layout. Questo è l'analogo di copia/incolla con l'opzione "Use Destination Theme" in PowerPoint. 2) L'analogo di questo metodo è il metodo [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) accessibile tramite la proprietà [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides). 

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide aggiunta.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Inserisce una copia di una slide di layout specificata nella posizione indicata della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova slide. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide da clonare. |

--------------------
Il nuovo layout sarà collegato alla master slide padre per questa collezione di slide di layout. Questo è l'analogo di copia/incolla con l'opzione "Use Destination Theme" in PowerPoint. 

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide inserita.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Aggiunge una nuova slide di layout alla fine della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layoutType | byte | Tipo di layout per un nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome per un nuovo layout. Se il nome fornito è già in uso verrà sollevata l'ArgumentException. Se viene passato un parametro null, il nome verrà generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" o "1\_Title Slide", "2\_..", ecc.). |

--------------------
1) Il layout aggiunto per il valore SlideLayoutType.Custom di layoutType non contiene segnaposti né forme. 2) L'analogo di questo metodo è il metodo [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) accessibile tramite la proprietà [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides). 

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide aggiunta.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Inserisce una nuova slide di layout nella posizione indicata della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice della nuova slide. |
| layoutType | byte | Tipo di layout per un nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome per un nuovo layout. Se il nome fornito è già in uso verrà sollevata l'ArgumentException. Se viene passato un parametro null, il nome verrà generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" o "1\_Title Slide", "2\_..", ecc.). |

--------------------
Il layout inserito per il valore SlideLayoutType.Custom di layoutType non contiene segnaposti né forme. 

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide inserita.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della collezione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

--------------------
1) Per evitare il lancio di PptxEditException, controllare prima la proprietà HasDependingSlides del layout. 2) È possibile utilizzare anche il metodo [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) per semplificare il codice. 

### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Sposta la slide di layout dalla collezione alla posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di destinazione. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide da spostare. |