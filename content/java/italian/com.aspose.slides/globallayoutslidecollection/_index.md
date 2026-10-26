---
title: GlobalLayoutSlideCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una collezione di tutte le diapositive di layout nella presentazione.
type: docs
url: /it/com.aspose.slides/globallayoutslidecollection/
---
**Ereditarietà:**  
java.lang.Object, [com.aspose.slides.LayoutSlideCollection](../../com.aspose.slides/layoutslidecollection)

**Tutte le Interfacce Implementate:**  
[com.aspose.slides.IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)  
```
public final class GlobalLayoutSlideCollection extends LayoutSlideCollection implements IGlobalLayoutSlideCollection
```

Rappresenta una collezione di tutte le diapositive di layout nella presentazione. Estende la classe LayoutSlideCollection con metodi per aggiungere/clonare diapositive di layout nel contesto dell'unione delle collezioni individuali delle diapositive master.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Aggiunge una copia di una diapositiva di layout specificata alla presentazione. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Aggiunge una copia di una diapositiva di layout specificata alla presentazione. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Aggiunge una nuova diapositiva di layout alla presentazione. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Aggiunge una copia di una diapositiva di layout specificata alla presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva da clonare. |

--------------------

Durante la clonazione di un layout tra presentazioni diverse, il master del layout può essere clonato anche per mantenere la formattazione originale. Un registro interno è utilizzato per tracciare i master clonati automaticamente, al fine di evitare la creazione di più cloni della stessa diapositiva master. La clonazione manuale delle diapositive master non sarà né impedita né registrata.  

**Restituisce:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public final ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Aggiunge una copia di una diapositiva di layout specificata alla presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva da clonare. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva master per un nuovo layout. |

--------------------

1) Il nuovo layout sarà collegato al master definito nella presentazione di destinazione. Quindi è analogo a copia/incolla con l'opzione "Use Destination Theme" in PowerPoint. 2) L'analogo di questo metodo è il metodo [IMasterLayoutSlideCollection.addClone(ILayoutSlide)](../../com.aspose.slides/imasterlayoutslidecollection\#addClone-ILayoutSlide-) accessibile tramite la proprietà ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).  

**Restituisce:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public final ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Aggiunge una nuova diapositiva di layout alla presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva master per un nuovo layout. |
| layoutType | byte | Tipo di layout per un nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome per un nuovo layout. Se il nome fornito è già in uso verrà sollevata un'ArgumentException. Se viene passato un parametro null, il nome verrà generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" o "1_Title Slide", "2_..", ecc.). |

--------------------

1) Il layout aggiunto per il valore SlideLayoutType.Custom di layoutType non contiene segnaposti né forme. 2) L'analogo di questo metodo è il metodo [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) accessibile tramite la proprietà ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).  

**Restituisce:**  
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.