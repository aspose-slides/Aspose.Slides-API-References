---
title: Rotation3D
second_title: Aspose.Slides Java API Referansı
description: Bir grafiğin 3B rotasyonunu temsil eder.
type: docs
url: /tr/com.aspose.slides/rotation3d/
---
**Kalıtım:**
java.lang.Object

**Tüm Uygulanan Arabirimler:**
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Bir grafiğin 3B rotasyonunu temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRotationX()](#getRotationX--) | X ekseni etrafındaki dönüş açısını döndürür veya ayarlar, yani |
| [setRotationX(byte value)](#setRotationX-byte-) | X ekseni etrafındaki dönüş açısını döndürür veya ayarlar, yani |
| [getRotationY()](#getRotationY--) | Y ekseni etrafındaki dönüş açısını döndürür veya ayarlar, yani |
| [setRotationY(int value)](#setRotationY-int-) | Y ekseni etrafındaki dönüş açısını döndürür veya ayarlar, yani |
| [getPerspective()](#getPerspective--) | 3B grafikler için perspektif değerini (görüş alanı açısı) döndürür veya ayarlar (0 ile 240 arasında). |
| [setPerspective(byte value)](#setPerspective-byte-) | 3B grafikler için perspektif değerini (görüş alanı açısı) döndürür veya ayarlar (0 ile 240 arasında). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Grafik eksenlerinin perspektif yerine dik açıyla çizilip çizilmediğini belirler. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Grafik eksenlerinin perspektif yerine dik açıyla çizilip çizilmediğini belirler. |
| [getDepthPercents()](#getDepthPercents--) | 3B grafiğin derinliğini grafik genişliğinin yüzde olarak (20 ile 2000 yüzde arasında) döndürür veya ayarlar. |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 3B grafiğin derinliğini grafik genişliğinin yüzde olarak (20 ile 2000 yüzde arasında) döndürür veya ayarlar. |
| [getHeightPercents()](#getHeightPercents--) | 3-D grafiğin yüksekliğini grafik genişliğinin yüzde olarak (5 ile 500 yüzde arasında) belirtir. |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 3-D grafiğin yüksekliğini grafik genişliğinin yüzde olarak (5 ile 500 yüzde arasında) belirtir. |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

X ekseni etrafındaki dönüş açısını döndürür veya ayarlar, yani 3B grafikler için Y yönünde (-90 ile 90 derece arasında). Özellik, ECMA-376'deki 21.2.2.157 rotX (X Rotation) öğesi ve PowerPoint 2007+ "Y Rotation" seçeneği ile eşleşir. Okunur/Yazılır byte.

**Döndürür:**
byte

### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

X ekseni etrafındaki dönüş açısını döndürür veya ayarlar, yani 3B grafikler için Y yönünde (-90 ile 90 derece arasında). Özellik, ECMA-376'deki 21.2.2.157 rotX (X Rotation) öğesi ve PowerPoint 2007+ "Y Rotation" seçeneği ile eşleşir. Okunur/Yazılır byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Y ekseni etrafındaki dönüş açısını döndürür veya ayarlar, yani 3B grafikler için X yönünde (0 ile 360 derece arasında). Özellik, ECMA-376'deki 21.2.2.158 rotY (Y Rotation) öğesi ve PowerPoint 2007+ "X Rotation" seçeneği ile eşleşir. Okunur/Yazılır int.

**Döndürür:**
int

### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Y ekseni etrafındaki dönüş açısını döndürür veya ayarlar, yani 3B grafikler için X yönünde (0 ile 360 derece arasında). Özellik, ECMA-376'deki 21.2.2.158 rotY (Y Rotation) öğesi ve PowerPoint 2007+ "X Rotation" seçeneği ile eşleşir. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

3B grafikler için perspektif değerini (görüş alanı açısı) döndürür veya ayarlar (0 ile 240 arasında). RightAngleAxes özelliği true ise yok sayılır. Okunur/Yazılır byte.

**Döndürür:**
byte

### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

3B grafikler için perspektif değerini (görüş alanı açısı) döndürür veya ayarlar (0 ile 240 arasında). RightAngleAxes özelliği true ise yok sayılır. Okunur/Yazılır byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Grafik eksenlerinin perspektif yerine dik açıyla çizilip çizilmediğini belirler. Başka bir deyişle, eksen açıları grafik dönüşünden veya yüksekliğinden bağımsızdır. Okunur/Yazılır boolean.

**Döndürür:**
boolean

### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Grafik eksenlerinin perspektif yerine dik açıyla çizilip çizilmediğini belirler. Başka bir deyişle, eksen açıları grafik dönüşünden veya yüksekliğinden bağımsızdır. Okunur/Yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

3B grafiğin derinliğini grafik genişliğinin yüzde olarak (20 ile 2000 yüzde arasında) döndürür veya ayarlar. Okunur/Yazılır int.

**Döndürür:**
int

### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

3B grafiğin derinliğini grafik genişliğinin yüzde olarak (20 ile 2000 yüzde arasında) döndürür veya ayarlar. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

3-D grafiğin yüksekliğini grafik genişliğinin yüzde olarak (5 ile 500 yüzde arasında) belirtir. Okunur/Yazılır int.

**Döndürür:**
int

### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

3-D grafiğin yüksekliğini grafik genişliğinin yüzde olarak (5 ile 500 yüzde arasında) belirtir. Okunur/Yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt okunur IDOMObject.

**Döndürür:**
com.aspose.slides.IDOMObject