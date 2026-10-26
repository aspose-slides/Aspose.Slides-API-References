---
title: IOuterShadow
second_title: Aspose.Slides dla Androida - odwołanie API Java
description: Reprezentuje efekt zewnętrznego cienia.
type: docs
url: /pl/com.aspose.slides/ioutershadow/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IOuterShadow extends IImageTransformOperation, IAccessiblePVIObject<IOuterShadowEffectiveData>
```

Reprezentuje efekt zewnętrznego cienia.
## Metody

| Metoda | Opis |
| --- | --- |
| [getBlurRadius()](#getBlurRadius--) | Promień rozmycia w punktach. |
| [setBlurRadius(double value)](#setBlurRadius-double-) | Promień rozmycia w punktach. |
| [getDirection()](#getDirection--) | Kierunek cienia, w stopniach. |
| [setDirection(float value)](#setDirection-float-) | Kierunek cienia, w stopniach. |
| [getDistance()](#getDistance--) | Odległość cienia od obiektu, w punktach. |
| [setDistance(double value)](#setDistance-double-) | Odległość cienia od obiektu, w punktach. |
| [getShadowColor()](#getShadowColor--) | Kolor cienia. |
| [getRectangleAlign()](#getRectangleAlign--) | Wyrównanie prostokąta. |
| [setRectangleAlign(byte value)](#setRectangleAlign-byte-) | Wyrównanie prostokąta. |
| [getSkewHorizontal()](#getSkewHorizontal--) | Kąt skośności poziomej, w stopniach. |
| [setSkewHorizontal(double value)](#setSkewHorizontal-double-) | Kąt skośności poziomej, w stopniach. |
| [getSkewVertical()](#getSkewVertical--) | Kąt skośności pionowej, w stopniach. |
| [setSkewVertical(double value)](#setSkewVertical-double-) | Kąt skośności pionowej, w stopniach. |
| [getRotateShadowWithShape()](#getRotateShadowWithShape--) | Wskazuje, czy cień obraca się razem z kształtem. |
| [setRotateShadowWithShape(boolean value)](#setRotateShadowWithShape-boolean-) | Wskazuje, czy cień obraca się razem z kształtem. |
| [getScaleHorizontal()](#getScaleHorizontal--) | Poziomy współczynnik skalowania, w procentach oryginalnego rozmiaru. |
| [setScaleHorizontal(double value)](#setScaleHorizontal-double-) | Poziomy współczynnik skalowania, w procentach oryginalnego rozmiaru. |
| [getScaleVertical()](#getScaleVertical--) | Pionowy współczynnik skalowania, w procentach oryginalnego rozmiaru. |
| [setScaleVertical(double value)](#setScaleVertical-double-) | Pionowy współczynnik skalowania, w procentach oryginalnego rozmiaru. |
### getBlurRadius() {#getBlurRadius--}
```
public abstract double getBlurRadius()
```


Promień rozmycia w punktach. Domyślna wartość - 0 pt. Odczyt/zapis double.

**Zwraca:**
double
### setBlurRadius(double value) {#setBlurRadius-double-}
```
public abstract void setBlurRadius(double value)
```


Promień rozmycia w punktach. Domyślna wartość - 0 pt. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getDirection() {#getDirection--}
```
public abstract float getDirection()
```


Kierunek cienia, w stopniach. Domyślna wartość - 0 � (od lewego do prawego). Odczyt/zapis float.

**Zwraca:**
float
### setDirection(float value) {#setDirection-float-}
```
public abstract void setDirection(float value)
```


Kierunek cienia, w stopniach. Domyślna wartość - 0 � (od lewego do prawego). Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |

### getDistance() {#getDistance--}
```
public abstract double getDistance()
```


Odległość cienia od obiektu, w punktach. Domyślna wartość - 0 pt. Odczyt/zapis double.

**Zwraca:**
double
### setDistance(double value) {#setDistance-double-}
```
public abstract void setDistance(double value)
```


Odległość cienia od obiektu, w punktach. Domyślna wartość - 0 pt. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getShadowColor() {#getShadowColor--}
```
public abstract IColorFormat getShadowColor()
```


Kolor cienia. Domyślna wartość - automatyczny czarny (zależny od motywu). Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getRectangleAlign() {#getRectangleAlign--}
```
public abstract byte getRectangleAlign()
```


Wyrównanie prostokąta. Domyślna wartość - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Odczyt/zapis [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Zwraca:**
byte
### setRectangleAlign(byte value) {#setRectangleAlign-byte-}
```
public abstract void setRectangleAlign(byte value)
```


Wyrównanie prostokąta. Domyślna wartość - [RectangleAlignment.Bottom](../../com.aspose.slides/rectanglealignment\#Bottom). Odczyt/zapis [RectangleAlignment](../../com.aspose.slides/rectanglealignment).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | byte |  |

### getSkewHorizontal() {#getSkewHorizontal--}
```
public abstract double getSkewHorizontal()
```


Kąt skośności poziomej, w stopniach. Domyślna wartość - 0 �. Odczyt/zapis double.

**Zwraca:**
double
### setSkewHorizontal(double value) {#setSkewHorizontal-double-}
```
public abstract void setSkewHorizontal(double value)
```


Kąt skośności poziomej, w stopniach. Domyślna wartość - 0 �. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getSkewVertical() {#getSkewVertical--}
```
public abstract double getSkewVertical()
```


Kąt skośności pionowej, w stopniach. Domyślna wartość - 0 �. Odczyt/zapis double.

**Zwraca:**
double
### setSkewVertical(double value) {#setSkewVertical-double-}
```
public abstract void setSkewVertical(double value)
```


Kąt skośności pionowej, w stopniach. Domyślna wartość - 0 �. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getRotateShadowWithShape() {#getRotateShadowWithShape--}
```
public abstract boolean getRotateShadowWithShape()
```


Wskazuje, czy cień obraca się razem z kształtem. Domyślna wartość - true. Odczyt/zapis boolean.

**Zwraca:**
boolean
### setRotateShadowWithShape(boolean value) {#setRotateShadowWithShape-boolean-}
```
public abstract void setRotateShadowWithShape(boolean value)
```


Wskazuje, czy cień obraca się razem z kształtem. Domyślna wartość - true. Odczyt/zapis boolean.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | boolean |  |

### getScaleHorizontal() {#getScaleHorizontal--}
```
public abstract double getScaleHorizontal()
```


Poziomy współczynnik skalowania, w procentach oryginalnego rozmiaru. Ujemne skalowanie powoduje odbicie. Domyślna wartość - 100 %. Odczyt/zapis double.

**Zwraca:**
double
### setScaleHorizontal(double value) {#setScaleHorizontal-double-}
```
public abstract void setScaleHorizontal(double value)
```


Poziomy współczynnik skalowania, w procentach oryginalnego rozmiaru. Ujemne skalowanie powoduje odbicie. Domyślna wartość - 100 %. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |

### getScaleVertical() {#getScaleVertical--}
```
public abstract double getScaleVertical()
```


Pionowy współczynnik skalowania, w procentach oryginalnego rozmiaru. Ujemne skalowanie powoduje odbicie. Domyślna wartość - 100 %. Odczyt/zapis double.

**Zwraca:**
double
### setScaleVertical(double value) {#setScaleVertical-double-}
```
public abstract void setScaleVertical(double value)
```


Pionowy współczynnik skalowania, w procentach oryginalnego rozmiaru. Ujemne skalowanie powoduje odbicie. Domyślna wartość - 100 %. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |