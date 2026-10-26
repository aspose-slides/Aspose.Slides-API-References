---
title: IImage
second_title: Aspose.Slides per Android - Riferimento API Java
description: Rappresenta un'immagine raster o vettoriale.
type: docs
url: /it/com.aspose.slides/iimage/
---
**Tutte le interfacce implementate:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Rappresenta un'immagine raster o vettoriale.

--------------------

Questa interfaccia fornisce un'astrazione comune per gestire sia le immagini raster che vettoriali. Le implementazioni possono variare a seconda del tipo di immagine sottostante.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Salva l'immagine in un file. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Salva l'immagine in un file nel formato specificato. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Salva l'immagine in un flusso nel formato specificato. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Salva l'immagine in un file nel formato e nella qualità specificati. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Salva l'immagine in un flusso nel formato e nella qualità specificati. |
| [getSize()](#getSize--) | Ottiene la dimensione dell'immagine. |
| [getWidth()](#getWidth--) | Ottiene la larghezza dell'immagine in pixel. |
| [getHeight()](#getHeight--) | Ottiene l'altezza dell'immagine in pixel. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Salva l'immagine in un file.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Il percorso del file in cui l'immagine verrà salvata. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Salva l'immagine in un file nel formato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Il percorso del file in cui l'immagine verrà salvata. |
| format | int | Il formato dell'immagine. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Salva l'immagine in un flusso nel formato specificato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Il flusso in cui l'immagine verrà salvata. |
| format | int | Il formato dell'immagine. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Salva l'immagine in un file nel formato e nella qualità specificati.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filename | java.lang.String | Il percorso del file in cui l'immagine verrà salvata. |
| format | int | Il formato dell'immagine. |
| quality | int | La qualità dell'immagine salvata (da 0 a 100). Questo parametro influisce solo sul salvataggio in [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); per tutti gli altri formati, viene ignorato. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Salva l'immagine in un flusso nel formato e nella qualità specificati.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| stream | java.io.OutputStream | Il flusso in cui l'immagine verrà salvata. |
| format | int | Il formato dell'immagine. |
| quality | int | La qualità dell'immagine salvata (da 0 a 100). Questo parametro influisce solo sul salvataggio in [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); per tutti gli altri formati, viene ignorato. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

Ottiene la dimensione dell'immagine.

**Restituisce:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Ottiene la larghezza dell'immagine in pixel.

**Restituisce:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Ottiene l'altezza dell'immagine in pixel.

**Restituisce:**
int