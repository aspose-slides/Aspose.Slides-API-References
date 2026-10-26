---
title: IThreeDFormat
second_title: Aspose.Slides dla Androida – referencja API Java
description: Reprezentuje właściwości 3-D.
type: docs
url: /pl/com.aspose.slides/ithreedformat/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Reprezentuje 3-D properties.
## Metody

| Metoda | Opis |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Zwraca lub ustawia szerokość konturu 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Zwraca lub ustawia szerokość konturu 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Zwraca lub ustawia wysokość efektu wyciągnięcia. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Zwraca lub ustawia wysokość efektu wyciągnięcia. |
| [getDepth()](#getDepth--) | Zwraca lub ustawia głębokość kształtu 3D. |
| [setDepth(double value)](#setDepth-double-) | Zwraca lub ustawia głębokość kształtu 3D. |
| [getBevelTop()](#getBevelTop--) | Zwraca lub ustawia typ górnego 3D bevel. |
| [getBevelBottom()](#getBevelBottom--) | Zwraca lub ustawia typ dolnego 3D bevel. |
| [getContourColor()](#getContourColor--) | Zwraca lub ustawia kolor konturu. |
| [getExtrusionColor()](#getExtrusionColor--) | Zwraca lub ustawia kolor wyciągnięcia. |
| [getCamera()](#getCamera--) | Zwraca lub ustawia ustawienia kamery. |
| [getLightRig()](#getLightRig--) | Zwraca lub ustawia typ światła. |
| [getMaterial()](#getMaterial--) | Zwraca lub ustawia typ materiału. |
| [setMaterial(int value)](#setMaterial-int-) | Zwraca lub ustawia typ materiału. |
| [getEffective()](#getEffective--) | Pobiera skuteczne dane formatowania 3-D z zastosowanym dziedziczeniem. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Zwraca lub ustawia szerokość konturu 3D. Odczyt/zapis double.

**Zwraca:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Zwraca lub ustawia szerokość konturu 3D. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Zwraca lub ustawia wysokość efektu wyciągnięcia. Odczyt/zapis double.

**Zwraca:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Zwraca lub ustawia wysokość efektu wyciągnięcia. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Zwraca lub ustawia głębokość kształtu 3D. Odczyt/zapis double.

**Zwraca:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Zwraca lub ustawia głębokość kształtu 3D. Odczyt/zapis double.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Zwraca lub ustawia typ górnego 3D bevel. Tylko do odczytu [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Zwraca:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Zwraca lub ustawia typ dolnego 3D bevel. Tylko do odczytu [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Zwraca:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Zwraca lub ustawia kolor konturu. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Zwraca lub ustawia kolor wyciągnięcia. Tylko do odczytu [IColorFormat](../../com.aspose.slides/icolorformat).

**Zwraca:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Zwraca lub ustawia ustawienia kamery. Tylko do odczytu [ICamera](../../com.aspose.slides/icamera).

**Zwraca:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Zwraca lub ustawia typ światła. Tylko do odczytu [ILightRig](../../com.aspose.slides/ilightrig).

**Zwraca:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Zwraca lub ustawia typ materiału. Odczyt/zapis [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Zwraca:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Zwraca lub ustawia typ materiału. Odczyt/zapis [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Pobiera skuteczne dane formatowania 3-D z zastosowanym dziedziczeniem.

**Zwraca:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).