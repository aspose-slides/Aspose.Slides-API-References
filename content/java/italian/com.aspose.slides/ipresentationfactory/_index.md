---
title: IPresentationFactory
second_title: Aspose.Slides for Java API Reference
description: Consente di creare una presentazione tramite interfaccia COM
type: docs
url: /it/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Consente di creare una presentazione tramite interfaccia COM
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createPresentation()](#createPresentation--) | Creates new presentation. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Creates new presentation with additional load options |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Gets info about presentation in specified file. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Gets info about presentation in specified stream. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Reads an existing presentation from array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Reads an existing presentation from array with additional load options |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Reads an existing presentation from stream |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Reads an existing presentation from file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Reads an existing presentation from stream with additional load options |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Retrieves the raw text from the slides |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Retrieves the raw text from the slides |
### createPresentation() {#createPresentation--}
```
public abstract IPresentation createPresentation()
```

Crea una nuova presentazione.

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Nuova presentazione
### createPresentation(ILoadOptions options) {#createPresentation-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation createPresentation(ILoadOptions options)
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
public abstract IPresentationInfo getPresentationInfo(String file)
```

Ottiene informazioni sulla presentazione nel file specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | File della presentazione. |

**Restituisce:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informazioni sulla presentazione
### getPresentationInfo(InputStream stream) {#getPresentationInfo-java.io.InputStream-}
```
public abstract IPresentationInfo getPresentationInfo(InputStream stream)
```

Ottiene informazioni sulla presentazione nello stream specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream della presentazione. |

**Restituisce:**
[IPresentationInfo](../../com.aspose.slides/ipresentationinfo) - Informazioni sulla presentazione.
### readPresentation(byte[] data) {#readPresentation-byte---}
```
public abstract IPresentation readPresentation(byte[] data)
```

Legge una presentazione esistente da un array

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | byte[] | Array da leggere |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### readPresentation(byte[] data, ILoadOptions options) {#readPresentation-byte---com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(byte[] data, ILoadOptions options)
```

Legge una presentazione esistente da un array con opzioni di caricamento aggiuntive

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| data | byte[] | Array da leggere |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opzioni di caricamento |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### readPresentation(InputStream stream) {#readPresentation-java.io.InputStream-}
```
public abstract IPresentation readPresentation(InputStream stream)
```

Legge una presentazione esistente da un stream

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream di input da leggere |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Legge una presentazione esistente da un stream con opzioni di caricamento aggiuntive

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Stream di input da leggere |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opzioni di caricamento |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### readPresentation(String file) {#readPresentation-java.lang.String-}
```
public abstract IPresentation readPresentation(String file)
```

Legge una presentazione esistente da un file

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | Nome file |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

Legge una presentazione esistente da file con opzioni di caricamento aggiuntive

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | Nome file |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opzioni di caricamento |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### getPresentationText(String file, int mode) {#getPresentationText-java.lang.String-int-}
```
public abstract IPresentationText getPresentationText(String file, int mode)
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
public abstract IPresentationText getPresentationText(InputStream stream, int mode)
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
public abstract IPresentationText getPresentationText(InputStream stream, int mode, ILoadOptions options)
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