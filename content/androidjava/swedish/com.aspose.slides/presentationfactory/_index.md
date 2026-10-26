---
title: PresentationFactory
second_title: Aspose.Slides för Android via Java API-referens
description: Tillåter att skapa presentation via COM-gränssnitt
type: docs
url: /sv/com.aspose.slides/presentationfactory/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Tillåter att skapa presentation via COM-gränssnitt

--------------------

> ```
> The following example shows how to checking a Presentation Format.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  System.out.println(info.getLoadFormat()); // PPTX
>  IPresentationInfo info2 = PresentationFactory.getInstance().getPresentationInfo("pres.ppt");
>  System.out.println(info2.getLoadFormat()); // PPT
>  IPresentationInfo info3 = PresentationFactory.getInstance().getPresentationInfo("pres.odp");
>  System.out.println(info3.getLoadFormat()); // ODP
>  
>  The following example shows how to getting the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  System.out.println(props.getCreatedTime());
>  System.out.println(props.getSubject());
>  System.out.println(props.getTitle());
>  // ..
>  
>  The following example shows how to updating the properties of a Presentation.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setTitle("My title");
>  info.updateDocumentProperties(props);
> ```

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getInstance()](#getInstance--) | Statisk instans för presentationsfabrik. |
| [createPresentation()](#createPresentation--) | Skapar ny presentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Skapar ny presentation med ytterligare laddningsalternativ. |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Skapar ett nytt PresentationInfo-objekt från en fil och binder presentationen till det. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Skapar ett nytt PresentationInfo-objekt från ett flöde och binder presentationen till det. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Läser en befintlig presentation från en array. |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Läser en befintlig presentation från en array med ytterligare laddningsalternativ. |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Läser en befintlig presentation från ett flöde. |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Läser en befintlig presentation från ett flöde med ytterligare laddningsalternativ. |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Läser en befintlig presentation från en fil. |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Läser en befintlig presentation från ett flöde med ytterligare laddningsalternativ. |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Hämtar råtexten från bilderna. |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Hämtar råtexten från bilderna. |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Hämtar råtexten från bilderna. |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Statisk instans för presentationsfabrik. Skrivskyddad [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Returnerar:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

Skapar ny presentation.

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Ny presentation
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

Skapar ny presentation med ytterligare laddningsalternativ

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laddningsalternativ |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Ny presentation
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

Skapar ett nytt PresentationInfo-objekt från en fil och binder presentationen till det.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Presentationsfil. |

**Returnerar:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentationinformation bunden till presentationen.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

Skapar ett nytt PresentationInfo-objekt från ett flöde och binder presentationen till det. Hämtar information om presentationen i det specificerade flödet.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Presentationsflöde. |

**Returnerar:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentationinformation bunden till presentationen.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

Läser en befintlig presentation från en array

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Array att läsa från |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Läst presentation
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Läser en befintlig presentation från en array med ytterligare laddningsalternativ

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Array att läsa från |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laddningsalternativ |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Läst presentation
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPPresentation readPresentation(InputStream stream)
```

Läser en befintlig presentation från ett flöde

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Indataflöde att läsa |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Läst presentation
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Läser en befintlig presentation från ett flöde med ytterligare laddningsalternativ

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Indataflöde att läsa |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laddningsalternativ |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Läst presentation
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

Läser en befintlig presentation från en fil

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Filnamn |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Läst presentation
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```

Läser en befintlig presentation från en fil med ytterligare laddningsalternativ

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Filnamn |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laddningsalternativ |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Läst presentation
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

Hämtar råtexten från bilderna

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Indatafil |
| mode | int | Extraktionsläge |

**Returnerar:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instansen av PresentationText som innehåller SlideText-arrayen som representerar den råa bildtexten
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

Hämtar råtexten från bilderna

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Indataflöde |
| mode | int | Extraktionsläge |

**Returnerar:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instansen av PresentationText som innehåller SlideText-arrayen som representerar den råa bildtexten
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Hämtar råtexten från bilderna

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Indataflöde |
| mode | int | Extraktionsläge |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laddningsalternativ |

**Returnerar:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instansen av PresentationText som innehåller SlideText-arrayen som representerar den råa bildtexten