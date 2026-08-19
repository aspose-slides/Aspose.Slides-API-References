---
title: IMasterLayoutSlideCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una raccolta di tutti i layout slide della master slide definita.
type: docs
url: /it/com.aspose.slides/imasterlayoutslidecollection/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IMasterLayoutSlideCollection extends ILayoutSlideCollection
```

Rappresenta una raccolta di tutti i layout slide di una master slide definita. Estende l'interfaccia ILayoutSlideCollection con metodi per aggiungere/inserire/rimuovere/clonare i layout slide nel contesto delle singole raccolte dei layout slide della master.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Aggiunge una copia di un layout slide specificato alla fine della raccolta. |
| [insertClone(int index, ILayoutSlide sourceLayout)](#insertClone-int-com.aspose.slides.ILayoutSlide-) | Inserisce una copia di un layout slide specificato nella posizione specificata della raccolta. |
| [add(byte layoutType, String layoutName)](#add-byte-java.lang.String-) | Aggiunge un nuovo layout slide alla fine della raccolta. |
| [insert(int index, byte layoutType, String layoutName)](#insert-int-byte-java.lang.String-) | Inserisce un nuovo layout slide nella posizione specificata della raccolta. |
| [removeAt(int index)](#removeAt-int-) | Rimuove l'elemento all'indice specificato della raccolta. |
| [reorder(int index, ILayoutSlide layoutSlide)](#reorder-int-com.aspose.slides.ILayoutSlide-) | Sposta il layout slide dalla raccolta alla posizione specificata. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Aggiunge una copia di un layout slide specificato alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide da clonare. |

--------------------

1) Il nuovo layout sarà collegato alla master slide genitore per questa raccolta di layout slide. Quindi è l'analogo di copia/incolla con l'opzione "Use Destination Theme" in PowerPoint. 2) L'analogo di questo metodo è il metodo [IGlobalLayoutSlideCollection.addClone(ILayoutSlide,IMasterSlide)](../../com.aspose.slides/igloballayoutslidecollection\#addClone-ILayoutSlide-IMasterSlide-) accessibile tramite la proprietà [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide aggiunta.
### insertClone(int index, ILayoutSlide sourceLayout) {#insertClone-int-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide insertClone(int index, ILayoutSlide sourceLayout)
```

Inserisce una copia di un layout slide specificato nella posizione specificata della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del nuovo slide. |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide da clonare. |

--------------------

Il nuovo layout sarà collegato alla master slide genitore per questa raccolta di layout slide. Quindi è l'analogo di copia/incolla con l'opzione "Use Destination Theme" in PowerPoint.

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide inserita.
### add(byte layoutType, String layoutName) {#add-byte-java.lang.String-}
```
public abstract ILayoutSlide add(byte layoutType, String layoutName)
```

Aggiunge un nuovo layout slide alla fine della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| layoutType | byte | Tipo di layout per un nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome per un nuovo layout. Se il nome fornito è già in uso verrà generata un'ArgumentException. Se viene passato un parametro null, il nome verrà generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" oppure "1\_Title Slide", "2\_..", ecc.). |

--------------------

1) Il layout aggiunto per il valore SlideLayoutType.Custom di layoutType non contiene segnaposti né forme. 2) L'analogo di questo metodo è il metodo [IGlobalLayoutSlideCollection.add(IMasterSlide,byte,String)](../../com.aspose.slides/igloballayoutslidecollection\#add-IMasterSlide-byte-String-) accessibile tramite la proprietà [IPresentation.getLayoutSlides](../../com.aspose.slides/ipresentation\#getLayoutSlides).

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide aggiunta.
### insert(int index, byte layoutType, String layoutName) {#insert-int-byte-java.lang.String-}
```
public abstract ILayoutSlide insert(int index, byte layoutType, String layoutName)
```

Inserisce un nuovo layout slide nella posizione specificata della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice del nuovo slide. |
| layoutType | byte | Tipo di layout per un nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome per un nuovo layout. Se il nome fornito è già in uso verrà generata un'ArgumentException. Se viene passato un parametro null, il nome verrà generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" oppure "1\_Title Slide", "2\_..", ecc.). |

--------------------

Il layout inserito per il valore SlideLayoutType.Custom di layoutType non contiene segnaposti né forme.

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Slide inserita.
### removeAt(int index) {#removeAt-int-}
```
public abstract void removeAt(int index)
```

Rimuove l'elemento all'indice specificato della raccolta.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | L'indice basato su zero dell'elemento da rimuovere. |

--------------------

1) Per evitare il lancio di PptxEditException controllare prima la proprietà HasDependingSlides del layout. 2) È anche possibile utilizzare il metodo [ILayoutSlide.remove](../../com.aspose.slides/ilayoutslide\#remove) per semplificare il codice.
### reorder(int index, ILayoutSlide layoutSlide) {#reorder-int-com.aspose.slides.ILayoutSlide-}
```
public abstract void reorder(int index, ILayoutSlide layoutSlide)
```

Sposta il layout slide dalla raccolta alla posizione specificata.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | int | Indice di destinazione. |
| layoutSlide | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Slide da spostare. |