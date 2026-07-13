---
title: IChartTextBlockFormat
second_title: Aspose.Slides for Android via Java API Reference
description: Represents formatting properties for chart text elements.
type: docs
url: /cs/com.aspose.slides/icharttextblockformat/
---```
public interface IChartTextBlockFormat
```

Reprezentuje vlastnosti formátování pro textové prvky grafu.
## Metody

| Metoda | Popis |
| --- | --- |
| [getAnchoringType()](#getAnchoringType--) | Vrací nebo nastavuje svislé ukotvení textu v TextFrame. |
| [setAnchoringType(byte value)](#setAnchoringType-byte-) | Vrací nebo nastavuje svislé ukotvení textu v TextFrame. |
| [getCenterText()](#getCenterText--) | Pokud NullableBool.True, má být text vodorovně vycentrován v rámečku. |
| [setCenterText(byte value)](#setCenterText-byte-) | Pokud NullableBool.True, má být text vodorovně vycentrován v rámečku. |
| [getTextVerticalType()](#getTextVerticalType--) | Určuje orientaci textu. |
| [setTextVerticalType(byte value)](#setTextVerticalType-byte-) | Určuje orientaci textu. |
| [getMarginLeft()](#getMarginLeft--) | Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. |
| [setMarginLeft(double value)](#setMarginLeft-double-) | Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. |
| [getMarginRight()](#getMarginRight--) | Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. |
| [setMarginRight(double value)](#setMarginRight-double-) | Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. |
| [getMarginTop()](#getMarginTop--) | Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. |
| [setMarginTop(double value)](#setMarginTop-double-) | Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. |
| [getMarginBottom()](#getMarginBottom--) | Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. |
| [setMarginBottom(double value)](#setMarginBottom-double-) | Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. |
| [getWrapText()](#getWrapText--) | True, pokud je text zalomený na okrajích TextFrame. |
| [setWrapText(byte value)](#setWrapText-byte-) | True, pokud je text zalomený na okrajích TextFrame. |
| [getAutofitType()](#getAutofitType--) | Vrací nebo nastavuje režim automatického přizpůsobení textu. |
| [setAutofitType(byte value)](#setAutofitType-byte-) | Vrací nebo nastavuje režim automatického přizpůsobení textu. |
| [getRotationAngle()](#getRotationAngle--) | Určuje vlastní otočení, které se použije na text v ohraničujícím rámečku. |
| [setRotationAngle(float value)](#setRotationAngle-float-) | Určuje vlastní otočení, které se použije na text v ohraničujícím rámečku. |

### getAnchoringType() {#getAnchoringType--}
```
public abstract byte getAnchoringType()
```

Vrací nebo nastavuje svislé ukotvení textu v TextFrame. Čtení/Zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Vrací:**
byte

### setAnchoringType(byte value) {#setAnchoringType-byte-}
```
public abstract void setAnchoringType(byte value)
```

Vrací nebo nastavuje svislé ukotvení textu v TextFrame. Čtení/Zápis [TextAnchorType](../../com.aspose.slides/textanchortype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getCenterText() {#getCenterText--}
```
public abstract byte getCenterText()
```

Pokud NullableBool.True, má být text vodorovně vycentrován v rámečku. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setCenterText(byte value) {#setCenterText-byte-}
```
public abstract void setCenterText(byte value)
```

Pokud NullableBool.True, má být text vodorovně vycentrován v rámečku. Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getTextVerticalType() {#getTextVerticalType--}
```
public abstract byte getTextVerticalType()
```

Určuje orientaci textu. Výsledná hodnota vizuálního otočení textu je součtem této vlastnosti a vlastního úhlu v vlastnosti RotationAngle. Čtení/Zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Vrací:**
byte

### setTextVerticalType(byte value) {#setTextVerticalType-byte-}
```
public abstract void setTextVerticalType(byte value)
```

Určuje orientaci textu. Výsledná hodnota vizuálního otočení textu je součtem této vlastnosti a vlastního úhlu v vlastnosti RotationAngle. Čtení/Zápis [TextVerticalType](../../com.aspose.slides/textverticaltype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getMarginLeft() {#getMarginLeft--}
```
public abstract double getMarginLeft()
```

Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. Změna této vlastnosti může mít určitý vliv jen na tyto části diagramu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Čtení/Zápis double.

**Vrací:**
double

### setMarginLeft(double value) {#setMarginLeft-double-}
```
public abstract void setMarginLeft(double value)
```

Vrací nebo nastavuje levý okraj (v bodech) v TextFrame. Změna této vlastnosti může mít určitý vliv jen na tyto části diagramu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginRight() {#getMarginRight--}
```
public abstract double getMarginRight()
```

Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. Změna této vlastnosti může mít určitý vliv jen na tyto části diagramu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Čtení/Zápis double.

**Vrací:**
double

### setMarginRight(double value) {#setMarginRight-double-}
```
public abstract void setMarginRight(double value)
```

Vrací nebo nastavuje pravý okraj (v bodech) v TextFrame. Změna této vlastnosti může mít určitý vliv jen na tyto části diagramu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginTop() {#getMarginTop--}
```
public abstract double getMarginTop()
```

Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. Změna této vlastnosti může mít určitý vliv jen na tyto části diagramu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Čtení/Zápis double.

**Vrací:**
double

### setMarginTop(double value) {#setMarginTop-double-}
```
public abstract void setMarginTop(double value)
```

Vrací nebo nastavuje horní okraj (v bodech) v TextFrame. Změna této vlastnosti může mít určitý vliv jen na tyto části diagramu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getMarginBottom() {#getMarginBottom--}
```
public abstract double getMarginBottom()
```

Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. Změna této vlastnosti může mít určitý vliv jen na tyto části diagramu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Čtení/Zápis double.

**Vrací:**
double

### setMarginBottom(double value) {#setMarginBottom-double-}
```
public abstract void setMarginBottom(double value)
```

Vrací nebo nastavuje spodní okraj (v bodech) v TextFrame. Změna této vlastnosti může mít určitý vliv jen na tyto části diagramu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Čtení/Zápis double.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | double |  |

### getWrapText() {#getWrapText--}
```
public abstract byte getWrapText()
```

True, pokud je text zalomený na okrajích TextFrame. Změna této vlastnosti může mít určitý vliv jen na tyto části diagramu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2007/2013). Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Vrací:**
byte

### setWrapText(byte value) {#setWrapText-byte-}
```
public abstract void setWrapText(byte value)
```

True, pokud je text zalomený na okrajích TextFrame. Změna této vlastnosti může mít určitý vliv jen na tyto části diagramu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2007/2013). Čtení/Zápis [NullableBool](../../com.aspose.slides/nullablebool).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getAutofitType() {#getAutofitType--}
```
public abstract byte getAutofitType()
```

Vrací nebo nastavuje režim automatického přizpůsobení textu. Změna této vlastnosti může mít určitý vliv jen na tyto části diagramu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Čtení/Zápis [TextAutofitType](../../com.aspose.slides/textautofittype).

**Vrací:**
byte

### setAutofitType(byte value) {#setAutofitType-byte-}
```
public abstract void setAutofitType(byte value)
```

Vrací nebo nastavuje režim automatického přizpůsobení textu. Změna této vlastnosti může mít určitý vliv jen na tyto části diagramu: DataLabel a DataLabelFormat (plná podpora v PowerPoint 2013; v PowerPoint 2007 nemá žádný vliv na vykreslování). Čtení/Zápis [TextAutofitType](../../com.aspose.slides/textautofittype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getRotationAngle() {#getRotationAngle--}
```
public abstract float getRotationAngle()
```

Určuje vlastní otočení, které se použije na text v ohraničujícím rámečku. Pokud není specifikováno, použije se otočení přidruženého tvaru. Pokud je specifikováno, použije se nezávisle na tvaru. Tzn., že tvar může mít aplikováno otočení navíc k otočení, které má text. Výsledná hodnota vizuálního otočení textu je součtem této vlastnosti a předdefinovaného svislého typu v vlastnosti TextVerticalType. Čtení/Zápis float.

--------------------

> ```
> Consider the case where a shape has a rotation of 90 degrees clockwise applied to it. 
>  In addition to this, the text body itself has a rotation of -90 degrees 
>  counter-clockwise applied to it. Then the resulting shape would appear to
>  be rotated but the text within it would appear as though it had not been rotated at all.
> ```

**Vrací:**
float

### setRotationAngle(float value) {#setRotationAngle-float-}
```
public abstract void setRotationAngle(float value)
```

Určuje vlastní otočení, které se použije na text v ohraničujícím rámečku. Pokud není specifikováno, použije se otočení přidruženého tvaru. Pokud je specifikováno, použije se nezávisle na tvaru. Tzn., že tvar může mít aplikováno otočení navíc k otočení, které má text. Výsledná hodnota vizuálního otočení textu je součtem této vlastnosti a předdefinovaného svislého typu v vlastnosti TextVerticalType. Čtení/Zápis float.

--------------------

> ```
> Zvažte případ, kdy má tvar aplikované otočení o 90 stupňů ve směru hodinových ručiček. 
>  K tomu má samotné tělo textu otočení o -90 stupňů 
>  proti směru hodinových ručiček. Pak by výsledný tvar vypadal, že
>  je otočen, ale text v něm by vypadal, jako by vůbec nebyl otočen.
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |