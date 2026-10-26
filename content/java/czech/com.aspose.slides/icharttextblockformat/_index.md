---
title: IChartTextBlockFormat
second_title: Aspose.Slides pro Java – reference API
description: Reprezentuje vlastnosti formátování pro textové prvky grafu.
type: docs
url: /cs/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Reprezentuje vlastnosti formátování pro textové prvky grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Returns or sets vertical anchor text in a TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Returns or sets vertical anchor text in a TextFrame. |
| [getCenterText()](#getCenterText--) | If NullableBool.True then text should be centered in box horizontally. |
| [setCenterText(byte value)](#setCenterText-byte-) | If NullableBool.True then text should be centered in box horizontally. |
| [getTextVerticalType()](#getTextVerticalType--) | Determines text orientation. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Determines text orientation. |
| [getMarginLeft()](#getMarginLeft--) | Returns or sets the left margin (points) in a TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Returns or sets the left margin (points) in a TextFrame. |
| [getMarginRight()](#getMarginRight--) | Returns or sets the right margin (points) in a TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Returns or sets the right margin (points) in a TextFrame. |
| [getMarginTop()](#getMarginTop--) | Returns or sets the top margin (points) in a TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Returns or sets the top margin (points) in a TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Returns or sets the bottom margin (points) in a TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Returns or sets the bottom margin (points) in a TextFrame. |
| [getWrapText()](#getWrapText--) | True if text is wrapped at TextFrame's margins. |
| [setWrapText(byte value)](#setWrapText-byte-) | True if text is wrapped at TextFrame's margins. |
| [getAutofitType()](#getAutofitType--) | Returns or sets text's autofit mode. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Returns or sets text's autofit mode. |
| [getRotationAngle()](#getRotationAngle--) | Specifies the custom rotation that is being applied to the text within the bounding box. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Specifies the custom rotation that is being applied to the text within the bounding box. |
### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. Číst/Zapisovat [TextAnchorType](../../com.aspose.slides/textanchortype).

**Vrací:**
byte
### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Vrací nebo nastavuje vertikální ukotvení textu v TextFrame. Číst/Zapisovat [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Pokud NullableBool.True, text by měl být vodorovně centrován v rámečku. Číst/Zapisovat [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Pokud NullableBool.True, text by měl být vodorovně centrován v rámečku. Číst/Zapisovat [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Určuje orientaci textu. Výsledná hodnota vizuální rotace textu je shrnuta z této vlastnosti a vlastnosti RotationAngle. Číst/Zapisovat [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Vrací:**
byte
### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Určuje orientaci textu. Výsledná hodnota vizuální rotace textu je shrnuta z této vlastnosti a vlastnosti RotationAngle. Číst/Zapisovat [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Vrací nebo nastavuje levý okraj (body) v TextFrame. Změna této vlastnosti může mít vliv pouze na následující části grafu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá vliv na vykreslování). Číst/Zapisovat double.

**Vrací:**
double
### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Vrací nebo nastavuje levý okraj (body) v TextFrame. Změna této vlastnosti může mít vliv pouze na následující části grafu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá vliv na vykreslování). Číst/Zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Vrací nebo nastavuje pravý okraj (body) v TextFrame. Změna této vlastnosti může mít vliv pouze na následující části grafu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá vliv na vykreslování). Číst/Zapisovat double.

**Vrací:**
double
### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Vrací nebo nastavuje pravý okraj (body) v TextFrame. Změna této vlastnosti může mít vliv pouze na následující části grafu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá vliv na vykreslování). Číst/Zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Vrací nebo nastavuje horní okraj (body) v TextFrame. Změna této vlastnosti může mít vliv pouze na následující části grafu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá vliv na vykreslování). Číst/Zapisovat double.

**Vrací:**
double
### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Vrací nebo nastavuje horní okraj (body) v TextFrame. Změna této vlastnosti může mít vliv pouze na následující části grafu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá vliv na vykreslování). Číst/Zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Vrací nebo nastavuje spodní okraj (body) v TextFrame. Změna této vlastnosti může mít vliv pouze na následující části grafu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá vliv na vykreslování). Číst/Zapisovat double.

**Vrací:**
double
### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Vrací nebo nastavuje spodní okraj (body) v TextFrame. Změna této vlastnosti může mít vliv pouze na následující části grafu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá vliv na vykreslování). Číst/Zapisovat double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

True, pokud je text zalamován na okrajích TextFrame. Změna této vlastnosti může mít vliv pouze na následující části grafu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2007/2013). Číst/Zapisovat [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte
### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

True, pokud je text zalamován na okrajích TextFrame. Změna této vlastnosti může mít vliv pouze na následující části grafu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2007/2013). Číst/Zapisovat [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Vrací nebo nastavuje režim automatického přizpůsobení textu. Změna této vlastnosti může mít vliv pouze na následující části grafu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá vliv na vykreslování). Číst/Zapisovat [TextAutofitType](../../com.aspose.slides/textautofittype).

**Vrací:**
byte
### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Vrací nebo nastavuje režim automatického přizpůsobení textu. Změna této vlastnosti může mít vliv pouze na následující části grafu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá vliv na vykreslování). Číst/Zapisovat [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Určuje vlastní rotaci, která se použije na text uvnitř ohraničujícího rámečku. Pokud není specifikována, použije se rotace přidruženého tvaru. Pokud je specifikována, použije se nezávisle na tvaru. To znamená, že tvar může mít rotaci navíc k rotaci samotného textu. Výsledná hodnota vizuální rotace textu je shrnuta z této vlastnosti a předdefinovaného vertikálního typu v vlastnosti TextVerticalType. Číst/Zapisovat float.

--------------------

> ```
> Uvažujme případ, kdy má tvar na sebe aplikovanou rotaci o 90 stupňů ve směru hodinových ručiček. 
>  K tomu má tělo textu samotné rotaci -90 stupňů 
>  proti směru hodinových ručiček aplikovanou na něj. Pak by výsledný tvar vypadal, že
>  bude otočen, ale text uvnitř něj by se jevil, jako by vůbec nebyl otočen.
> ```

**Vrací:**
float
### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Určuje vlastní rotaci, která se použije na text uvnitř ohraničujícího rámečku. Pokud není specifikována, použije se rotace přidruženého tvaru. Pokud je specifikována, použije se nezávisle na tvaru. To znamená, že tvar může mít rotaci navíc k rotaci samotného textu. Výsledná hodnota vizuální rotace textu je shrnuta z této vlastnosti a předdefinovaného vertikálního typu v vlastnosti TextVerticalType. Číst/Zapisovat float.

--------------------

> ```
> Uvažujme případ, kdy má tvar na sebe aplikovanou rotaci o 90 stupňů ve směru hodinových ručiček. 
>  K tomu má tělo textu samotné rotaci -90 stupňů 
>  proti směru hodinových ručiček aplikovanou na něj. Pak by výsledný tvar vypadal, že
>  bude otočen, ale text uvnitř něj by se jevil, jako by vůbec nebyl otočen.
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |