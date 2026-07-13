---
title: ICellFormat
second_title: Aspose.Slides for Android via Java API Reference
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
| [getBorderLeft()](#getBorderLeft--) | Vrací objekt vlastností levého ohraničení. |
| [getBorderTop()](#getBorderTop--) | Vrací objekt vlastností horního ohraničení. |
| [getBorderRight()](#getBorderRight--) | Vrací objekt vlastností pravého ohraničení. |
| [getBorderBottom()](#getBorderBottom--) | Vrací objekt vlastností spodního ohraničení. |
| [getBorderDiagonalDown()](#getBorderDiagonalDown--) | Vrací objekt vlastností úhlopříčky zleva nahoře doprava. |
| [getBorderDiagonalUp()](#getBorderDiagonalUp--) | Vrací objekt vlastností úhlopříčky ze spodního levého rohu nahoru doprava. |
| [getTransparency()](#getTransparency--) | Získá nebo nastaví průhlednost barvy výplně. |
| [setTransparency(float value)](#setTransparency-float-) | Získá nebo nastaví průhlednost barvy výplně. |
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


Vrací objekt vlastností levého ohraničení. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderTop() {#getBorderTop--}
```
public abstract ILineFormat getBorderTop()
```


Vrací objekt vlastností horního ohraničení. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderRight() {#getBorderRight--}
```
public abstract ILineFormat getBorderRight()
```


Vrací objekt vlastností pravého ohraničení. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderBottom() {#getBorderBottom--}
```
public abstract ILineFormat getBorderBottom()
```


Vrací objekt vlastností spodního ohraničení. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalDown() {#getBorderDiagonalDown--}
```
public abstract ILineFormat getBorderDiagonalDown()
```


Vrací objekt vlastností úhlopříčky zleva nahoře doprava. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getBorderDiagonalUp() {#getBorderDiagonalUp--}
```
public abstract ILineFormat getBorderDiagonalUp()
```


Vrací objekt vlastností úhlopříčky ze spodního levého rohu nahoru doprava. Pouze ke čtení [ILineFormat](../../com.aspose.slides/ilineformat).

**Vrací:**
[ILineFormat](../../com.aspose.slides/ilineformat)
### getTransparency() {#getTransparency--}
```
public abstract float getTransparency()
```


Získá nebo nastaví průhlednost barvy výplně. Čtení/zápis  float .

**Vrací:**
float
### setTransparency(float value) {#setTransparency-float-}
```
public abstract void setTransparency(float value)
```


Získá nebo nastaví průhlednost barvy výplně. Čtení/zápis  float .

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