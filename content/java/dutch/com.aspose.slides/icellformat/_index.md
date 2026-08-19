---
title: ICellFormat
second_title: Aspose.Slides for Java API Reference
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
| [getFillFormat()](#getFillFormat--) | Retourneert een object met vul-eigenschappen van een cel. |
| [getBorderLeft()](#getBorderLeft--) | Retourneert een object met eigenschappen van de linkerrandlijn. |
| [getBorderTop()](#getBorderTop--) | Retourneert een object met eigenschappen van de bovenrandlijn. |
| [getBorderRight()](#getBorderRight--) | Retourneert een object met eigenschappen van de rechterrandlijn. |
| [getBorderBottom()](#getBorderBottom--) | Retourneert een object met eigenschappen van de onderrandlijn. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Retourneert een object met eigenschappen van de diagonaal van linksboven naar rechtsonder. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Retourneert een object met eigenschappen van de diagonaal van linksonder naar rechtsboven. |
| [getTransparency()](#getTransparency--) | Haalt de transparantie van de vulkleur op of stelt deze in. |
| [setTransparency(float value)](#setTransparency-float-) | Haalt de transparantie van de vulkleur op of stelt deze in. |
| [getEffective()](#getEffective--) | Haalt de effectieve opmaak-eigenschappen van een tabelcel op met overerving en toegepaste tabelstijlen. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Retourneert een object met vul-eigenschappen van een cel. Alleen-lezen [IFillFormat](../../com.aspose.slides/ifillformat).

**Retour:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```

Retourneert een object met eigenschappen van de linkerrandlijn. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```

Retourneert een object met eigenschappen van de bovenrandlijn. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```

Retourneert een object met eigenschappen van de rechterrandlijn. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

**Retour:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```

Retourneert een object met eigenschappen van de onderrandlijn. Alleen-lezen [ILineFormat](../../com.aspose.slides/ilineformat).

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

Haalt de transparantie van de vulkleur op of stelt deze in. Lezen/Schrijven  float .

**Retour:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```

Haalt de transparantie van de vulkleur op of stelt deze in. Lezen/Schrijven  float .

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```

Haalt de effectieve opmaak-eigenschappen van een tabelcel op met overerving en toegepaste tabelstijlen.

**Retour:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).