---
title: IPatternFormatEffectiveData
second_title: Aspose.Slides for Java API Reference
description: Oggetto immutabile che contiene le proprietà di riempimento con motivo effettivo.
type: docs
url: /it/com.aspose.slides/ipatternformateffectivedata/
---```
public interface IPatternFormatEffectiveData
```

Oggetto immutabile che contiene le proprietà di riempimento con motivo effettivo.

--------------------

Questa interfaccia è usata come parte di [IFillFormatEffectiveData](../../com.aspose.slides/ifillformateffectivedata) e [ILineFillFormatEffectiveData](../../com.aspose.slides/ilinefillformateffectivedata).
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPatternStyle()](#getPatternStyle--) | Restituisce lo stile del motivo. |
| [getForeColor()](#getForeColor--) | Restituisce il colore di primo piano del motivo. |
| [getBackColor()](#getBackColor--) | Restituisce il colore di sfondo del motivo. |
| [getTileIImage(Color background, Color foreground)](#getTileIImage-java.awt.Color-java.awt.Color-) | Crea un'immagine a tasselli per il riempimento a motivo con i colori specificati. |
### getPatternStyle() {#getPatternStyle--}
```
public abstract byte getPatternStyle()
```

Restituisce lo stile del motivo. Solo lettura [PatternStyle](../../com.aspose.slides/patternstyle).

**Restituisce:**
byte
### getForeColor() {#getForeColor--}
```
public abstract Color getForeColor()
```

Restituisce il colore di primo piano del motivo. Solo lettura java.awt.Color.

**Restituisce:**
java.awt.Color
### getBackColor() {#getBackColor--}
```
public abstract Color getBackColor()
```

Restituisce il colore di sfondo del motivo. Solo lettura java.awt.Color.

**Restituisce:**
java.awt.Color
### getTileIImage(Color background, Color foreground) {#getTileIImage-java.awt.Color-java.awt.Color-}
```
public abstract IImage getTileIImage(Color background, Color foreground)
```

Crea un'immagine a tasselli per il riempimento a motivo con i colori specificati.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| background | java.awt.Color | Il java.awt.Color di sfondo per il motivo. |
| foreground | java.awt.Color | Il java.awt.Color di primo piano per il motivo. |

**Restituisce:**
[IImage](../../com.aspose.slides/iimage) - Piastrella [IImage](../../com.aspose.slides/iimage).