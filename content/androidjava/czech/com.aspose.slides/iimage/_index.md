---
title: IImage
second_title: Aspose.Slides pro Android pomocí Java API Reference
description: Představuje rastrový nebo vektorový obrázek.
type: docs
url: /cs/com.aspose.slides/iimage/
---
**Všechny implementované rozhraní:**
com.aspose.ms.System.IDisposable
```
public interface IImage extends System.IDisposable
```

Představuje rastrový nebo vektorový obrázek.

--------------------

Toto rozhraní poskytuje společnou abstrakci pro zpracování rastrových i vektorových obrázků. Implementace se mohou lišit v závislosti na základním typu obrázku.
## Metody

| Metoda | Popis |
| --- | --- |
| [save(String filename)](#save-java.lang.String-) | Uloží obrázek do souboru. |
| [save(String filename, int format)](#save-java.lang.String-int-) | Uloží obrázek do souboru ve zvoleném formátu. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Uloží obrázek do proudu ve zvoleném formátu. |
| [save(String filename, int format, int quality)](#save-java.lang.String-int-int-) | Uloží obrázek do souboru ve zvoleném formátu a kvalitě. |
| [save(OutputStream stream, int format, int quality)](#save-java.io.OutputStream-int-int-) | Uloží obrázek do proudu ve zvoleném formátu a kvalitě. |
| [getSize()](#getSize--) | Získá velikost obrázku. |
| [getWidth()](#getWidth--) | Získá šířku obrázku v pixelech. |
| [getHeight()](#getHeight--) | Získá výšku obrázku v pixelech. |
### save(String filename) {#save-java.lang.String-}
```
public abstract void save(String filename)
```

Uloží obrázek do souboru.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | java.lang.String | Cesta k souboru, do kterého bude obrázek uložen. |

### save(String filename, int format) {#save-java.lang.String-int-}
```
public abstract void save(String filename, int format)
```

Uloží obrázek do souboru ve zvoleném formátu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | java.lang.String | Cesta k souboru, do kterého bude obrázek uložen. |
| format | int | Formát obrázku. |

### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Uloží obrázek do proudu ve zvoleném formátu.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Proud, do kterého bude obrázek uložen. |
| format | int | Formát obrázku. |

### save(String filename, int format, int quality) {#save-java.lang.String-int-int-}
```
public abstract void save(String filename, int format, int quality)
```

Uloží obrázek do souboru ve zvoleném formátu a kvalitě.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| filename | java.lang.String | Cesta k souboru, do kterého bude obrázek uložen. |
| format | int | Formát obrázku. |
| quality | int | Kvalita uloženého obrázku (0 až 100). Tento parametr ovlivňuje ukládání pouze ve formátu [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); pro všechny ostatní formáty je ignorován. |

### save(OutputStream stream, int format, int quality) {#save-java.io.OutputStream-int-int-}
```
public abstract void save(OutputStream stream, int format, int quality)
```

Uloží obrázek do proudu ve zvoleném formátu a kvalitě.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| stream | java.io.OutputStream | Proud, do kterého bude obrázek uložen. |
| format | int | Formát obrázku. |
| quality | int | Kvalita uloženého obrázku (0 až 100). Tento parametr ovlivňuje ukládání pouze ve formátu [ImageFormat.Jpeg](../../com.aspose.slides/imageformat\#Jpeg); pro všechny ostatní formáty je ignorován. |

### getSize() {#getSize--}
```
public abstract Size getSize()
```

Získá velikost obrázku.

**Návratová hodnota:**
[Size](../../com.aspose.slides.android/size)
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```

Získá šířku obrázku v pixelech.

**Návratová hodnota:**
int
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```

Získá výšku obrázku v pixelech.

**Návratová hodnota:**
int