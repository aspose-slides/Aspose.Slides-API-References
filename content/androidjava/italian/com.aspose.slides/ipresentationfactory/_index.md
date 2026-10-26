---
title: IPresentationFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create presentation via COM interface
type: docs
url: /it/com.aspose.slides/ipresentationfactory/
---```
public interface IPresentationFactory
```

Consente di creare una presentazione tramite interfaccia COM

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [createPresentation()](#createPresentation--) | Crea una nuova presentazione. |
| [createPresentation(ILoadOptions options)](#createPresentation-com.aspose.slides.ILoadOptions-) | Crea una nuova presentazione con opzioni di caricamento aggiuntive |
| [getPresentationInfo(String file)](#getPresentationInfo-java.lang.String-) | Ottiene informazioni sulla presentazione nel file specificato. |
| [getPresentationInfo(InputStream stream)](#getPresentationInfo-java.io.InputStream-) | Ottiene informazioni sulla presentazione nel flusso specificato. |
| [readPresentation(byte[] data)](#readPresentation-byte---) | Legge una presentazione esistente da un array |
| [readPresentation(byte[] data, ILoadOptions options)](#readPresentation-byte---com.aspose.slides.ILoadOptions-) | Legge una presentazione esistente da un array con opzioni di caricamento aggiuntive |
| [readPresentation(InputStream stream)](#readPresentation-java.io.InputStream-) | Legge una presentazione esistente da un flusso |
| [readPresentation(InputStream stream, ILoadOptions options)](#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-) | Legge una presentazione esistente da un flusso con opzioni di caricamento aggiuntive |
| [readPresentation(String file)](#readPresentation-java.lang.String-) | Legge una presentazione esistente da un file |
| [readPresentation(String file, ILoadOptions options)](#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-) | Legge una presentazione esistente da un flusso con opzioni di caricamento aggiuntive |
| [getPresentationText(String file, int mode)](#getPresentationText-java.lang.String-int-) | Recupera il testo grezzo dalle diapositive |
| [getPresentationText(InputStream stream, int mode)](#getPresentationText-java.io.InputStream-int-) | Recupera il testo grezzo dalle diapositive |
| [getPresentationText(InputStream stream, int mode, ILoadOptions options)](#getPresentationText-java.io.InputStream-int-com.aspose.slides.ILoadOptions-) | Recupera il testo grezzo dalle diapositive |
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

Ottiene informazioni sulla presentazione nel flusso specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Flusso della presentazione. |

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

Legge una presentazione esistente da un flusso

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Flusso di input da leggere |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### readPresentation(InputStream stream, ILoadOptions options) {#readPresentation-java.io.InputStream-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(InputStream stream, ILoadOptions options)
```

Legge una presentazione esistente da un flusso con opzioni di caricamento aggiuntive

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.InputStream | Flusso di input da leggere |
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
| file | java.lang.String | Nome del file |

**Restituisce:**
[IPresentation](../../com.aspose.slides/ipresentation) - Presentazione letta
### readPresentation(String file, ILoadOptions options) {#readPresentation-java.lang.String-com.aspose.slides.ILoadOptions-}
```
public abstract IPresentation readPresentation(String file, ILoadOptions options)
```

Legge una presentazione esistente da un file con opzioni di caricamento aggiuntive

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| file | java.lang.String | Nome del file |
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
| stream | java.io.InputStream | Flusso di input |
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
| stream | java.io.InputStream | Flusso di input |
| mode | int | Modalità di estrazione |
| options | [ILoadOptions](../../com.aspose.slides/iloadoptions) | Opzioni di caricamento |

**Restituisce:**
[IPresentationText](../../com.aspose.slides/ipresentationtext) - L'istanza di PresentationText contenente l'array SlideText che rappresenta il testo grezzo delle diapositive