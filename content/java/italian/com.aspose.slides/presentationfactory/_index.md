---
title: PresentationFactory
second_title: Riferimento API Aspose.Slides per Java
description: Consente di creare presentazioni tramite interfaccia COM
type: docs
url: /it/com.aspose.slides/presentationfactory/
---
**Ereditarietà:**
java.lang.Object

**Tutte le Interfacce Implementate:**
[com.aspose.slides.IPresentationFactory](../../com.aspose.slides/ipresentationfactory)
```
public class PresentationFactory implements IPresentationFactory
```

Consente di creare presentazioni tramite interfaccia COM

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

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PresentationFactory()](#PresentationFactory--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getInstance()](#getInstance--) | Istanza statica della factory di presentazione. |
| [createPresentation()](#createPresentation--) | Crea una nuova presentazione. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Crea una nuova presentazione con opzioni di caricamento aggiuntive |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Crea un oggetto PresentationInfo da file e associa la presentazione ad esso. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Crea un oggetto PresentationInfo da stream e associa la presentazione ad esso. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Legge una presentazione esistente da array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Legge una presentazione esistente da array con opzioni di caricamento aggiuntive |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Legge una presentazione esistente da stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Legge una presentazione esistente da stream con opzioni di caricamento aggiuntive |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Legge una presentazione esistente da file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Legge una presentazione esistente da stream con opzioni di caricamento aggiuntive |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Recupera il testo grezzo dalle diapositive |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Recupera il testo grezzo dalle diapositive |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Recupera il testo grezzo dalle diapositive |
### PresentationFactory() {#PresentationFactory--}
```
public PresentationFactory()
```

### getInstance() {#getInstance--}
```
public static PresentationFactory getInstance()
```

Istanza statica della factory di presentazione. Solo lettura [PresentationFactory](../../com.aspose.slides/presentationfactory).

**Restituisce:**
[PresentationFactory](../../com.aspose.slides/presentationfactory)
### createPresentation() {#createPresentation--}
```
public final IPresentation createPresentation()
```

Crea una nuova presentazione.

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nuova presentazione
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public final IPresentation createPresentation(ILoadOptions options)
```

Crea una nuova presentazione con opzioni di caricamento aggiuntive

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opzioni di caricamento |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nuova presentazione
### getPresentationInfo(String file) {#getPresentationInfo-java.lang.String-}
```
public final IPresentationInfo getPresentationInfo(String file)
```

Crea un oggetto PresentationInfo da file e associa la presentazione ad esso.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | File di presentazione. |

**Restituisce:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informazioni sulla presentazione associate alla presentazione.
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public final IPresentationInfo getPresentationInfo(InputStream stream)
```

Crea un oggetto PresentationInfo da stream e associa la presentazione ad esso. Ottiene informazioni sulla presentazione nello stream specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream di presentazione. |

**Restituisce:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informazioni sulla presentazione associate alla presentazione.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public final IPresentation readPresentation(byte[] data)
```

Legge una presentazione esistente da array

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | byte[] | Array da leggere |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Legge una presentazione esistente da array con opzioni di caricamento aggiuntive

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | byte[] | Array da leggere |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opzioni di caricamento |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public final IPresentation readPresentation(InputStream stream)
```

Legge una presentazione esistente da stream

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream di input da leggere |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Legge una presentazione esistente da stream con opzioni di caricamento aggiuntive

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream di input da leggere |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opzioni di caricamento |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public final IPresentation readPresentation(String file)
```

Legge una presentazione esistente da file

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | Nome del file |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public final IPresentation readPresentation(String file, ILoadOptions options)
```

Legge una presentazione esistente da file con opzioni di caricamento aggiuntive

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | Nome del file |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opzioni di caricamento |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public final IPresentationText getPresentationText(String file, int mode)
```

Recupera il testo grezzo dalle diapositive

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | File di input |
| mode | int | Modalità di estrazione |

**Restituisce:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - L'istanza di PresentationText contenente l'array SlideText che rappresenta il testo grezzo delle diapositive
### getPresentationText(InputStream stream, int mode) {#getPresentationText-java.io.InputStream-int-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode)
```

Recupera il testo grezzo dalle diapositive

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream di input |
| mode | int | Modalità di estrazione |

**Restituisce:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - L'istanza di PresentationText contenente l'array SlideText che rappresenta il testo grezzo delle diapositive
### getPresentationText(InputStream stream, int mode, ILoadOptions options) {#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-}
```
public final IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
```

Recupera il testo grezzo dalle diapositive

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream di input |
| mode | int | Modalità di estrazione |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opzioni di caricamento |

**Restituisce:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - L'istanza di PresentationText contenente l'array SlideText che rappresenta il testo grezzo delle diapositive