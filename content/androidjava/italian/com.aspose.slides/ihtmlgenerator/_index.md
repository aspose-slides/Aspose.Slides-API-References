---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Generatore HTML.
type: docs
url: /it/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

Generatore HTML.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | Aggiunge testo HTML formattato. |
| [addHtml(char[] html)](#addHtml-char---) | Aggiunge testo HTML formattato. |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | Aggiunge testo HTML formattato. |
| [addText(String text)](#addText-java.lang.String-) | Aggiunge testo semplice ai file HTML, sostituendo i caratteri speciali con entità HTML. |
| [addText(char[] text)](#addText-char---) | Aggiunge testo semplice ai file HTML, sostituendo i caratteri speciali con entità HTML. |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | Aggiunge testo semplice ai file HTML, sostituendo i caratteri speciali con entità HTML. |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | Racchiude tra virgolette il valore dell'attributo e lo aggiunge al file HTML. |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | Racchiude tra virgolette il valore dell'attributo e lo aggiunge al file HTML. |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | Racchiude tra virgolette il valore dell'attributo e lo aggiunge al file HTML. |
| [getSlideImageSize()](#getSlideImageSize--) | Restituisce la dimensione dell'immagine della diapositiva. |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | Restituisce l'unità in cui è specificata la dimensione dell'immagine della diapositiva. |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | Restituisce un codice CSS dell'unità in cui è specificata la dimensione dell'immagine della diapositiva. |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | Restituisce l'indice della diapositiva precedentemente renderizzata o -1 se è in corso la prima diapositiva. |
| [getSlideIndex()](#getSlideIndex--) | Restituisce l'indice della diapositiva attualmente in rendering. |
| [getNextSlideIndex()](#getNextSlideIndex--) | Restituisce l'indice di una diapositiva che sarà renderizzata dopo quella corrente o -1 se la diapositiva corrente è l'ultima. |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

Aggiunge testo HTML formattato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| html | java.lang.String | Testo da aggiungere. |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

Aggiunge testo HTML formattato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| html | char[] | Testo da aggiungere. |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

Aggiunge testo HTML formattato.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| html | char[] | Testo da aggiungere. |
| startIndex | int | Indice iniziale della porzione da aggiungere. |
| length | int | Lunghezza della porzione da aggiungere. |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

Aggiunge testo semplice ai file HTML, sostituendo i caratteri speciali con entità HTML. I ritorni a capo e gli spazi bianchi non sono sostituiti.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | java.lang.String | Testo da aggiungere. |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

Aggiunge testo semplice ai file HTML, sostituendo i caratteri speciali con entità HTML. I ritorni a capo e gli spazi bianchi non sono sostituiti.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | char[] | Testo da aggiungere. |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

Aggiunge testo semplice ai file HTML, sostituendo i caratteri speciali con entità HTML. I ritorni a capo e gli spazi bianchi non sono sostituiti.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| text | char[] | Testo da aggiungere. |
| startIndex | int | Indice iniziale della porzione da aggiungere. |
| length | int | Lunghezza della porzione da aggiungere. |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

Racchiude tra virgolette il valore dell'attributo e lo aggiunge al file HTML.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String | Stringa del valore dell'attributo. |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

Racchiude tra virgolette il valore dell'attributo e lo aggiunge al file HTML.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char[] | Stringa del valore dell'attributo. |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

Racchiude tra virgolette il valore dell'attributo e lo aggiunge al file HTML.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | char[] | Stringa del valore dell'attributo. |
| startIndex | int | Indice iniziale della porzione da aggiungere. |
| length | int | Lunghezza della porzione da aggiungere. |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

Restituisce la dimensione dell'immagine della diapositiva. Solo lettura [SizeF](../../com.aspose.slides.android/sizef).

**Restituisce:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

Restituisce l'unità in cui è specificata la dimensione dell'immagine della diapositiva. Solo lettura [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit).

**Restituisce:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

Restituisce un codice CSS dell'unità in cui è specificata la dimensione dell'immagine della diapositiva. Solo lettura String.

**Restituisce:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

Restituisce l'indice della diapositiva precedentemente renderizzata o -1 se è in corso la prima diapositiva. Solo lettura int.

**Restituisce:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

Restituisce l'indice della diapositiva attualmente in rendering. Solo lettura int.

**Restituisce:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

Restituisce l'indice di una diapositiva che sarà renderizzata dopo quella corrente o -1 se la diapositiva corrente è l'ultima. Solo lettura int.

**Restituisce:**
int