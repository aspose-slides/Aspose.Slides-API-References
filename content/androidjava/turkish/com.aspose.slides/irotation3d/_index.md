---
title: IRotation3D
second_title: Aspose.Slides for Android via Java API Reference
description: Bir grafiğin 3B döndürülmesini temsil eder.
type: docs
url: /tr/com.aspose.slides/irotation3d/
---```
public interface IRotation3D
```

Bir grafiğin 3B döndürülmesini temsil eder.
## Yöntemler

| Method | Description |
| --- | --- |
| [getRotationX()](#getRotationX--) | X ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani |
| [setRotationX(byte value)](#setRotationX-byte-) | X ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani |
| [getRotationY()](#getRotationY--) | Y ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani |
| [setRotationY(int value)](#setRotationY-int-) | Y ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani |
| [getPerspective()](#getPerspective--) | 3B grafikler için perspektif değerini (görüş alanı açısı) döndürür veya ayarlar (0 ile 100 arasında). |
| [setPerspective(byte value)](#setPerspective-byte-) | 3B grafikler için perspektif değerini (görüş alanı açısı) döndürür veya ayarlar (0 ile 100 arasında). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Grafik eksenlerinin perspektif yerine dik açıda olup olmadığını belirler. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Grafik eksenlerinin perspektif yerine dik açıda olup olmadığını belirler. |
| [getDepthPercents()](#getDepthPercents--) | 3B grafiğin derinliğini grafik genişliğinin yüzde olarak döndürür veya ayarlar (20 ile 2000 yüzde arasında). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 3B grafiğin derinliğini grafik genişliğinin yüzde olarak döndürür veya ayarlar (20 ile 2000 yüzde arasında). |
| [getHeightPercents()](#getHeightPercents--) | 3D grafiğin yüksekliğini grafik genişliğinin yüzde olarak belirler (5 ile 500 yüzde arasında). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 3D grafiğin yüksekliğini grafik genişliğinin yüzde olarak belirler (5 ile 500 yüzde arasında). |
### getRotationX() {#getRotationX--}
```
public abstract byte getRotationX()
```

X ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani 3B grafikler için Y yönünde (-90 ile 90 derece arasında). Özellik, ECMA-376'da 21.2.2.157 rotX (X Rotation) öğesiyle ve PowerPoint 2007+’deki "Y Rotation" seçeneğiyle eşleşir. Okuma/yazma byte.

**Döndürür:**
byte
### setRotationX(byte value) {#setRotationX-byte-}
```
public abstract void setRotationX(byte value)
```

X ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani 3B grafikler için Y yönünde (-90 ile 90 derece arasında). Özellik, ECMA-376'da 21.2.157 rotX (X Rotation) öğesiyle ve PowerPoint 2007+’deki "Y Rotation" seçeneğiyle eşleşir. Okuma/yazma byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getRotationY() {#getRotationY--}
```
public abstract int getRotationY()
```

Y ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani 3B grafikler için X yönünde (0 ile 360 derece arasında). Özellik, ECMA-376'da 21.2.2.158 rotY (Y Rotation) öğesiyle ve PowerPoint 2007+’deki "X Rotation" seçeneğiyle eşleşir. Okuma/yazma int.

**Döndürür:**
int
### setRotationY(int value) {#setRotationY-int-}
```
public abstract void setRotationY(int value)
```

Y ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani 3B grafikler için X yönünde (0 ile 360 derece arasında). Özellik, ECMA-376'da 21.2.2.158 rotY (Y Rotation) öğesiyle ve PowerPoint 2007+’deki "X Rotation" seçeneğiyle eşleşir. Okuma/yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getPerspective() {#getPerspective--}
```
public abstract byte getPerspective()
```

3B grafikler için perspektif değerini (görüş alanı açısı) döndürür veya ayarlar (0 ile 100 arasında). RightAngleAxes özelliği true ise yoksayılır. Okuma/yazma byte.

**Döndürür:**
byte
### setPerspective(byte value) {#setPerspective-byte-}
```
public abstract void setPerspective(byte value)
```

3B grafikler için perspektif değerini (görüş alanı açısı) döndürür veya ayarlar (0 ile 100 arasında). RightAngleAxes özelliği true ise yoksayılır. Okuma/yazma byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getRightAngleAxes() {#getRightAngleAxes--}
```
public abstract boolean getRightAngleAxes()
```

Grafik eksenlerinin perspektif yerine dik açıda olup olmadığını belirler. Başka bir deyişle, eksen açıları grafik döndürülmesi veya eğiminden bağımsız olup olmadığını belirler. Okuma/yazma boolean.

**Döndürür:**
boolean
### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public abstract void setRightAngleAxes(boolean value)
```

Grafik eksenlerinin perspektif yerine dik açıda olup olmadığını belirler. Başka bir deyişle, eksen açıları grafik döndürülmesi veya eğiminden bağımsız olup olmadığını belirler. Okuma/yazma boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |
### getDepthPercents() {#getDepthPercents--}
```
public abstract int getDepthPercents()
```

3B grafiğin derinliğini grafik genişliğinin yüzde olarak döndürür veya ayarlar (20 ile 2000 yüzde arasında). Okuma/yazma int.

**Döndürür:**
int
### setDepthPercents(int value) {#setDepthPercents-int-}
```
public abstract void setDepthPercents(int value)
```

3B grafiğin derinliğini grafik genişliğinin yüzde olarak döndürür veya ayarlar (20 ile 2000 yüzde arasında). Okuma/yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |
### getHeightPercents() {#getHeightPercents--}
```
public abstract int getHeightPercents()
```

3-D grafiğin yüksekliğini grafik genişliğinin yüzde olarak belirler (5 ile 500 yüzde arasında). Okuma/yazma int.

**Döndürür:**
int
### setHeightPercents(int value) {#setHeightPercents-int-}
```
public abstract void setHeightPercents(int value)
```

3-D grafiğin yüksekliğini grafik genişliğinin yüzde olarak belirler (5 ile 500 yüzde arasında). Okuma/yazma int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |