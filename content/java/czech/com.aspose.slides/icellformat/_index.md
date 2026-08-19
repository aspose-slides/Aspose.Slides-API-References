---
title: ICellFormat
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje formát buňky tabulky.
type: docs
url: /cs/com.aspose.slides/icellformat/
---```
public interface ICellFormat
```

Reprezentuje formát buňky tabulky.
## Metody

| Metoda | Popis |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Vrací objekt vlastností výplně buňky. |
| [getBorderLeft()](#getBorderLeft--) | Vrací objekt vlastností linky levého okraje. |
| [getBorderTop()](#getBorderTop--) | Vrací objekt vlastností linky horního okraje. |
| [getBorderRight()](#getBorderRight--) | Vrací objekt vlastností linky pravého okraje. |
| [getBorderBottom()](#getBorderBottom--) | Vrací objekt vlastností linky dolního okraje. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Vrací objekt vlastností úhlopříčky z levého horního do pravého dolního rohu. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Vrací objekt vlastností úhlopříčky z levého dolního do pravého horního rohu. |
| [getTransparency()](#getTransparency--) | Získá nebo nastaví průhlednost výplňové barvy. |
| [setTransparency(float value)](#setTransparency-float-) | Získá nebo nastaví průhlednost výplňové barvy. |
| [getEffective()](#getEffective--) | Získá efektivní vlastnosti formátování buňky tabulky s aplikovaným děděním a styly tabulky. |
### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```


Vrací objekt vlastností výplně buňky. Pouze ke čtení [IFillFormat](../../com.aspose.slides/ifillformat).

**Vrací:**
[IFillFormat](../../com.aspose.slides/ifillformat)
### getBorderLeft() {#getBorderLeft--}
```
public abstract ILineFormat getBorderLeft()
```


Vrací objekt vlastností linky levého okraje. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Vrací objekt vlastností linky horního okraje. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Vrací objekt vlastností linky pravého okraje. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Vrací objekt vlastností linky dolního okraje. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Vrací objekt vlastností úhlopříčky z levého horního do pravého dolního rohu. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Vrací objekt vlastností úhlopříčky z levého dolního do pravého horního rohu. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Získá nebo nastaví průhlednost výplňové barvy. Číst/Zapisovat  float .

**Vrací:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Získá nebo nastaví průhlednost výplňové barvy. Číst/Zapisovat  float .

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |
### getEffective() {#getEffective--}
```
public abstract ICellFormatEffectiveData getEffective()
```


Získá efektivní vlastnosti formátování buňky tabulky s aplikovaným děděním a styly tabulky.

**Vrací:**
[ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata) - A [ICellFormatEffectiveData](../../com.aspose.slides/icellformateffectivedata).