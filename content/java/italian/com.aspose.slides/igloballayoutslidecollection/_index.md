---
title: IGlobalLayoutSlideCollection
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta una collezione di tutte le diapositive di layout nella presentazione.
type: docs
url: /it/com.aspose.slides/igloballayoutslidecollection/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Rappresenta una collezione di tutte le diapositive di layout nella presentazione. Estende l'interfaccia ILayoutSlideCollection con metodi per aggiungere/duplicare diapositive di layout nel contesto dell'unione delle singole collezioni dei layout dei master.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Aggiunge una copia di una diapositiva di layout specificata alla presentazione. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Aggiunge una copia di una diapositiva di layout specificata alla presentazione. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Aggiunge una nuova diapositiva di layout alla presentazione. |

### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Aggiunge una copia di una diapositiva di layout specificata alla presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva da duplicare. |

--------------------

Quando si clona un layout tra presentazioni diverse, il master del layout può essere clonato anch'esso per mantenere la formattazione di origine. Un registro interno è usato per tracciare i master clonati automaticamente e prevenire la creazione di più cloni dello stesso master slide. Il clono manuale dei master slide non sarà né impedito né registrato.

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.

### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Aggiunge una copia di una diapositiva di layout specificata alla presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva da duplicare. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva master per un nuovo layout. |

--------------------

Il nuovo layout sarà collegato al master definito nella presentazione di destinazione. È quindi l'analogo di copia/incolla con l'opzione “Use Destination Theme” in PowerPoint.

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.

### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Aggiunge una nuova diapositiva di layout alla presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Diapositiva master per un nuovo layout. |
| layoutType | byte | Layout type for a new layout. Supported layout types: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Other layout types are not supported now: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome per un nuovo layout. Se il nome fornito è già in uso verrà sollevata l'Exception ArgumentException. Se viene passato un parametro null, il nome verrà generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" o "1\_Title Slide", "2\_..", ecc.). |

--------------------

1) Layout aggiunto per il valore SlideLayoutType.Custom di layoutType non contiene segnaposti né forme. 2) L'analogo di questo metodo è il metodo [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) accessibile tramite la proprietà ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)).

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.