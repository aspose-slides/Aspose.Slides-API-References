---
title: IGlobalLayoutSlideCollection
second_title: Aspose.Slides per Android tramite riferimento API Java
description: Rappresenta una raccolta di tutte le diapositive layout nella presentazione.
type: docs
url: /it/com.aspose.slides/igloballayoutslidecollection/
---
**All Implemented Interfaces:**
[com.aspose.slides.ILayoutSlideCollection](../../com.aspose.slides/ilayoutslidecollection)
```
public interface IGlobalLayoutSlideCollection extends ILayoutSlideCollection
```

Rappresenta una raccolta di tutte le diapositive layout nella presentazione. Estende l'interfaccia ILayoutSlideCollection con metodi per aggiungere/clonare diapositive layout nel contesto dell'unione delle singole raccolte di layout master.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addClone(ILayoutSlide sourceLayout)](#addClone-com.aspose.slides.ILayoutSlide-) | Aggiunge una copia di una diapositiva layout specificata alla presentazione. |
| [addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)](#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-) | Aggiunge una copia di una diapositiva layout specificata alla presentazione. |
| [add(IMasterSlide master, byte layoutType, String layoutName)](#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-) | Aggiunge una nuova diapositiva layout alla presentazione. |
### addClone(ILayoutSlide sourceLayout) {#addClone-com.aspose.slides.ILayoutSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout)
```

Aggiunge una copia di una diapositiva layout specificata alla presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva da clonare. |

--------------------

Quando si clona un layout tra presentazioni diverse, il master del layout può essere clonato anche per mantenere la formattazione di origine. Un registro interno è usato per tenere traccia dei master clonati automaticamente per evitare la creazione di più cloni dello stesso master slide. La clonazione manuale dei master slide non sarà né impedita né registrata. |

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.
### addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster) {#addClone-com.aspose.slides.ILayoutSlide-com.aspose.slides.IMasterSlide-}
```
public abstract ILayoutSlide addClone(ILayoutSlide sourceLayout, IMasterSlide destMaster)
```

Aggiunge una copia di una diapositiva layout specificata alla presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| sourceLayout | [ILayoutSlide](../../com.aspose.slides/ilayoutslide) | Diapositiva da clonare. |
| destMaster | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide per il nuovo layout. |

--------------------

Il nuovo layout sarà collegato al master definito nella presentazione di destinazione. È quindi l'analogo di copia/incolla con l'opzione "Usa tema di destinazione" in PowerPoint. |

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.
### add(IMasterSlide master, byte layoutType, String layoutName) {#add-com.aspose.slides.IMasterSlide-byte-java.lang.String-}
```
public abstract ILayoutSlide add(IMasterSlide master, byte layoutType, String layoutName)
```

Aggiunge una nuova diapositiva layout alla presentazione.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| master | [IMasterSlide](../../com.aspose.slides/imasterslide) | Master slide per il nuovo layout. |
| layoutType | byte | Tipo di layout per il nuovo layout. Tipi di layout supportati: Title, TitleOnly, Blank, TitleAndObject, VerticalText, VerticalTitleAndText, TwoObjects, SectionHeader, TwoTextAndTwoObjects, TitleObjectAndCaption, PictureAndCaption, Custom. Altri tipi di layout non sono attualmente supportati: Text, TwoColumnText, Table, TextAndChart, ChartAndText, Diagram, Chart, TextAndClipArt, ClipArtAndText, TextAndObject, ObjectAndText, Object, TextAndMedia, MediaAndText, ObjectOverText, TextOverObject, TextAndTwoObjects, TwoObjectsAndText, TwoObjectsOverText, FourObjects, ClipArtAndVerticalText, VerticalTitleAndTextOverChart, ObjectAndTwoObject, TwoObjectsAndObject. |
| layoutName | java.lang.String | Nome per il nuovo layout. Se il nome fornito è già in uso verrà sollevata un'ArgumentException. Se viene fornito un parametro null, il nome sarà generato automaticamente in base al tipo di layout fornito (ad esempio "Title Slide" o "1_Title Slide", "2_…", ecc.). |

--------------------

1) Il layout aggiunto per il valore SlideLayoutType.Custom di layoutType non contiene segnaposti né forme. 2) L'analogo di questo metodo è il metodo [IMasterLayoutSlideCollection.add(byte,String)](../../com.aspose.slides/imasterlayoutslidecollection\#add-byte-String-) accessibile con ([IMasterSlide.getLayoutSlides](../../com.aspose.slides/imasterslide\#getLayoutSlides)) property. |

**Restituisce:**
[ILayoutSlide](../../com.aspose.slides/ilayoutslide) - Diapositiva aggiunta.