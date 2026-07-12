---
title: Rotation3D
second_title: Aspose.Slides Android için Java API Referansı
description: Bir çizelgenin 3B dönüşünü temsil eder.
type: docs
url: /tr/com.aspose.slides/rotation3d/
---
**Inheritance:**  
java.lang.Object

**All Implemented Interfaces:**  
[com.aspose.slides.IRotation3D](../../com.aspose.slides/irotation3d), com.aspose.slides.IDOMObject  
```
public class Rotation3D implements IRotation3D, IDOMObject
```

Bir çizelgenin 3B dönüşünü temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRotationX()](#getRotationX--) | X ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani |
| [setRotationX(byte value)](#setRotationX-byte-) | X ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani |
| [getRotationY()](#getRotationY--) | Y ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani |
| [setRotationY(int value)](#setRotationY-int-) | Y ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani |
| [getPerspective()](#getPerspective--) | 3B çizelgeler için perspektif değerini (görüş açısı) döndürür veya ayarlar (0 ile 240 arasında). |
| [setPerspective(byte value)](#setPerspective-byte-) | 3B çizelgeler için perspektif değerini (görüş açısı) döndürür veya ayarlar (0 ile 240 arasında). |
| [getRightAngleAxes()](#getRightAngleAxes--) | Çizelge eksenlerinin perspektif yerine dik açılarda olup olmadığını belirler. |
| [setRightAngleAxes(boolean value)](#setRightAngleAxes-boolean-) | Çizelge eksenlerinin perspektif yerine dik açılarda olup olmadığını belirler. |
| [getDepthPercents()](#getDepthPercents--) | 3B çizelgenin derinliğini çizelge genişliğinin yüzdesi olarak döndürür veya ayarlar (20 ile 2000 yüzde arasında). |
| [setDepthPercents(int value)](#setDepthPercents-int-) | 3B çizelgenin derinliğini çizelge genişliğinin yüzdesi olarak döndürür veya ayarlar (20 ile 2000 yüzde arasında). |
| [getHeightPercents()](#getHeightPercents--) | 3-B çizelgenin yüksekliğini çizelge genişliğinin yüzdesi olarak belirtir (5 ile 500 yüzde arasında). |
| [setHeightPercents(int value)](#setHeightPercents-int-) | 3-B çizelgenin yüksekliğini çizelge genişliğinin yüzdesi olarak belirtir (5 ile 500 yüzde arasında). |
| [getParent_Immediate()](#getParent-Immediate--) |  |

### getRotationX() {#getRotationX--}
```
public final byte getRotationX()
```

X ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani 3B çizelgeler için Y yönünde (-90 ile 90 derece arasında). Özellik, ECMA-376’da 21.2.2.157 rotX (X Rotation) öğesi ve PowerPoint 2007+’de “Y Rotation” seçeneği ile eşleşir. Okunur/yazılır byte.

**Döndürür:**  
byte

### setRotationX(byte value) {#setRotationX-byte-}
```
public final void setRotationX(byte value)
```

X ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani 3B çizelgeler için Y yönünde (-90 ile 90 derece arasında). Özellik, ECMA-376’da 21.2.2.157 rotX (X Rotation) öğesi ve PowerPoint 2007+’de “Y Rotation” seçeneği ile eşleşir. Okunur/yazılır byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getRotationY() {#getRotationY--}
```
public final int getRotationY()
```

Y ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani 3B çizelgeler için X yönünde (0 ile 360 derece arasında). Özellik, ECMA-376’da 21.2.2.158 rotY (Y Rotation) öğesi ve PowerPoint 2007+’de “X Rotation” seçeneği ile eşleşir. Okunur/yazılır int.

**Döndürür:**  
int

### setRotationY(int value) {#setRotationY-int-}
```
public final void setRotationY(int value)
```

Y ekseni etrafındaki dönüş derecesini döndürür veya ayarlar, yani 3B çizelgeler için X yönünde (0 ile 360 derece arasında). Özellik, ECMA-376’da 21.2.2.158 rotY (Y Rotation) öğesi ve PowerPoint 2007+’de “X Rotation” seçeneği ile eşleşir. Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getPerspective() {#getPerspective--}
```
public final byte getPerspective()
```

3B çizelgeler için perspektif değerini (görüş açısı) döndürür veya ayarlar (0 ile 240 arasında). RightAngleAxes özelliği true ise yok sayılır. Okunur/yazılır byte.

**Döndürür:**  
byte

### setPerspective(byte value) {#setPerspective-byte-}
```
public final void setPerspective(byte value)
```

3B çizelgeler için perspektif değerini (görüş açısı) döndürür veya ayarlar (0 ile 240 arasında). RightAngleAxes özelliği true ise yok sayılır. Okunur/yazılır byte.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |

### getRightAngleAxes() {#getRightAngleAxes--}
```
public final boolean getRightAngleAxes()
```

Çizelge eksenlerinin perspektif yerine dik açılarda olup olmadığını belirler. Başka bir deyişle, eksenlerin açıları çizelge dönüşünden veya eğiminden bağımsızdır. Okunur/yazılır boolean.

**Döndürür:**  
boolean

### setRightAngleAxes(boolean value) {#setRightAngleAxes-boolean-}
```
public final void setRightAngleAxes(boolean value)
```

Çizelge eksenlerinin perspektif yerine dik açılarda olup olmadığını belirler. Başka bir deyişle, eksenlerin açıları çizelge dönüşünden veya eğiminden bağımsızdır. Okunur/yazılır boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getDepthPercents() {#getDepthPercents--}
```
public final int getDepthPercents()
```

3B çizelgenin derinliğini çizelge genişliğinin yüzdesi olarak döndürür veya ayarlar (20 ile 2000 yüzde arasında). Okunur/yazılır int.

**Döndürür:**  
int

### setDepthPercents(int value) {#setDepthPercents-int-}
```
public final void setDepthPercents(int value)
```

3B çizelgenin derinliğini çizelge genişliğinin yüzdesi olarak döndürür veya ayarlar (20 ile 2000 yüzde arasında). Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getHeightPercents() {#getHeightPercents--}
```
public final int getHeightPercents()
```

3-B çizelgenin yüksekliğini çizelge genişliğinin yüzdesi olarak belirtir (5 ile 500 yüzde arasında). Okunur/yazılır int.

**Döndürür:**  
int

### setHeightPercents(int value) {#setHeightPercents-int-}
```
public final void setHeightPercents(int value)
```

3-B çizelgenin yüksekliğini çizelge genişliğinin yüzdesi olarak belirtir (5 ile 500 yüzde arasında). Okunur/yazılır int.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Parent_Immediate nesnesini döndürür. Salt-okunur IDOMObject.

**Döndürür:**  
com.aspose.slides.IDOMObject