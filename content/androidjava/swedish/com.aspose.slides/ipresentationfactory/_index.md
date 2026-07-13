---
title: IPresentationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Tillåter att skapa presentation via COM-gränssnitt
type: docs
url: /sv/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Tillåter att skapa presentation via COM-gränssnitt
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [createPresentation()](#createPresentation--) | Skapar ny presentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Skapar ny presentation med ytterligare laddningsalternativ |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Hämtar information om presentation i angiven fil. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Hämtar information om presentation i angiven ström. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Läser en befintlig presentation från array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Läser en befintlig presentation från array med ytterligare laddningsalternativ |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Läser en befintlig presentation från ström |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Läser en befintlig presentation från ström med ytterligare laddningsalternativ |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Läser en befintlig presentation från fil |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Läser en befintlig presentation från ström med ytterligare laddningsalternativ |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Hämtar den råa texten från bilderna |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Hämtar den råa texten från bilderna |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Hämtar den råa texten från bilderna |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

Skapar ny presentation.

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Ny presentation
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
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
public abstract IPresentationInfo getPresentationInfo(String file)
```

Hämtar information om presentation i angiven fil.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Presentationsfil. |

**Returnerar:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentationsinfo
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

Hämtar information om presentation i angiven ström.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Presentationsström. |

**Returnerar:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Presentationsinfo.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

Läser en befintlig presentation från array

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Array att läsa |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Läs presentation
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Läser en befintlig presentation från array med ytterligare laddningsalternativ

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| data | byte[] | Array att läsa |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laddningsalternativ |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Läs presentation
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

Läser en befintlig presentation från ström

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Inmatningsström att läsa |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Läs presentation
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Läser en befintlig presentation från ström med ytterligare laddningsalternativ

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Inmatningsström att läsa |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laddningsalternativ |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Läs presentation
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

Läser en befintlig presentation från fil

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Filnamn |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Läs presentation
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

Läser en befintlig presentation från ström med ytterligare laddningsalternativ

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Filnamn |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laddningsalternativ |

**Returnerar:**
[IPresentation](../../com.aspose.slides/ipresentation) - Läs presentation
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
```

Hämtar den råa texten från bilderna

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| file | java.lang.String | Indatafil |
| mode | int | Extraktionsläge |

**Returnerar:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instans av PresentationText som innehåller SlideText-arrayen som representerar den råa bildtexten
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
```

Hämtar den råa texten från bilderna

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Indataström |
| mode | int | Extraktionsläge |

**Returnerar:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instans av PresentationText som innehåller SlideText-arrayen som representerar den råa bildtexten
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Hämtar den råa texten från bilderna

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | java.io.InputStream | Indataström |
| mode | int | Extraktionsläge |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Laddningsalternativ |

**Returnerar:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - Instans av PresentationText som innehåller SlideText-arrayen som representerar den råa bildtexten.