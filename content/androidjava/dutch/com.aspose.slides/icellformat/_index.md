---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Stelt het formaat van een tabelcel voor.
type: docs
url: /nl/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Stelt het formaat van een tabelcel voor.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Retourneert een object met celvullingseigenschappen. |
| [getBorderLeft()](#getBorderLeft--) | Retourneert een object met eigenschappen van de linkerrand. |
| [getBorderTop()](#getBorderTop--) | Retourneert een object met eigenschappen van de bovenrand. |
| [getBorderRight()](#getBorderRight--) | Retourneert een object met eigenschappen van de rechterrand. |
| [getBorderBottom()](#getBorderBottom--) | Retourneert een object met eigenschappen van de onderrand. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Retourneert een object met eigenschappen van de diagonaal van linksboven naar rechtsonder. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Retourneert een object met eigenschappen van de diagonaal van linksonder naar rechtsboven. |
| [getTransparency()](#getTransparency--) | Haalt of stelt de transparantie van de vulkleur in. |
| [setTransparency(float value)](#setTransparency-float-) | Haalt of stelt de transparantie van de vulkleur in. |
| [getEffective()](#getEffective--) | Haalt effectieve opmaak-eigenschappen van de tabelcel op met overerving en toegepaste tabelstijlen. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Retourneert een object met celvullingseigenschappen. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


Retourneert een object met eigenschappen van de linkerrand. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Retourneert een object met eigenschappen van de bovenrand. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Retourneert een object met eigenschappen van de rechterrand. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Retourneert een object met eigenschappen van de onderrand. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Retourneert een object met eigenschappen van de diagonaal van linksboven naar rechtsonder. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Retourneert een object met eigenschappen van de diagonaal van linksonder naar rechtsboven. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Haalt of stelt de transparantie van de vulkleur in. Lezen/schrijven  float .

**Retour:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Haalt of stelt de transparantie van de vulkleur in. Lezen/schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


Haalt effectieve opmaak-eigenschappen van de tabelcel op met overerving en toegepaste tabelstijlen.

**Retour:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).