---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides per Android tramite Java API Riferimento
description: Oggetto immutabile che contiene le proprietà di riempimento a pattern efficaci.
type: docs
url: /it/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Oggetto immutabile che contiene le proprietà di riempimento a pattern efficaci.

--------------------

Questa interfaccia è usata come parte di [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) e [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Restituisce lo stile del pattern. |
| [getForeColor()](#getForeColor--) | Restituisce il colore di primo piano del pattern. |
| [getBackColor()](#getBackColor--) | Restituisce il colore di sfondo del pattern. |
| [getTileIImage(Integer background, Integer foreground)](#getTileIImage-java.lang.Integer-java.lang.Integer-) | Crea un'immagine tile per il riempimento a pattern con i colori specificati. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```


Restituisce lo stile del pattern. Solo lettura [PatternStyle](../../com.aspose.slides/patternstyle).

**Restituisce:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Integer getForeColor()
```


Restituisce il colore di primo piano del pattern. Solo lettura java.lang.Integer.

**Restituisce:**
java.lang.Integer
### getBackColor() {#getBackColor--}
```
public abstract Integer getBackColor()
```


Restituisce il colore di sfondo del pattern. Solo lettura java.lang.Integer.

**Restituisce:**
java.lang.Integer
### getTileIImage(Integer background, Integer foreground) {#getTileIImage-java.lang.Integer-java.lang.Integer-}
```
public abstract IImage getTileIImage(Integer background, Integer foreground)
```


Crea un'immagine tile per il riempimento a pattern con i colori specificati.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| background | java.lang.Integer | Il java.lang.Integer di sfondo per il pattern. |
| foreground | java.lang.Integer | Il java.lang.Integer di primo piano per il pattern. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Tile [IImage](../../com.aspose.slides/iimage).