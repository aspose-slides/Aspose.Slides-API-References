---
title: IThreeDFormat
second_title: Referencia API de Aspose.Slides para Java
description: Representa propiedades 3-D.
type: docs
url: /es/com.aspose.slides/ithreedformat/
---
**Todas las Interfaces Implementadas:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Representa propiedades 3D.
## Métodos

| Método | Descripción |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Devuelve o establece el ancho de un contorno 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Devuelve o establece el ancho de un contorno 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Devuelve o establece la altura de un efecto de extrusión. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Devuelve o establece la altura de un efecto de extrusión. |
| [getDepth()](#getDepth--) | Devuelve o establece la profundidad de una forma 3D. |
| [setDepth(double value)](#setDepth-double-) | Devuelve o establece la profundidad de una forma 3D. |
| [getBevelTop()](#getBevelTop--) | Devuelve o establece el tipo de una bisel superior 3D. |
| [getBevelBottom()](#getBevelBottom--) | Devuelve o establece el tipo de una bisel inferior 3D. |
| [getContourColor()](#getContourColor--) | Devuelve o establece el color de un contorno. |
| [getExtrusionColor()](#getExtrusionColor--) | Devuelve o establece el color de una extrusión. |
| [getCamera()](#getCamera--) | Devuelve o establece la configuración de una cámara. |
| [getLightRig()](#getLightRig--) | Devuelve o establece el tipo de una luz. |
| [getMaterial()](#getMaterial--) | Devuelve o establece el tipo de un material. |
| [setMaterial(int value)](#setMaterial-int-) | Devuelve o establece el tipo de un material. |
| [getEffective()](#getEffective--) | Obtiene los datos de formato 3D efectivos con la herencia aplicada. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Devuelve o establece el ancho de un contorno 3D. Lectura/escritura double.

**Devuelve:**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Devuelve o establece el ancho de un contorno 3D. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Devuelve o establece la altura de un efecto de extrusión. Lectura/escritura double.

**Devuelve:**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Devuelve o establece la altura de un efecto de extrusión. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Devuelve o establece la profundidad de una forma 3D. Lectura/escritura double.

**Devuelve:**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Devuelve o establece la profundidad de una forma 3D. Lectura/escritura double.

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Devuelve o establece el tipo de una bisel superior 3D. Solo lectura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Devuelve:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Devuelve o establece el tipo de una bisel inferior 3D. Solo lectura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Devuelve:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Devuelve o establece el color de un contorno. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Devuelve o establece el color de una extrusión. Solo lectura [IColorFormat](../../com.aspose.slides/icolorformat).

**Devuelve:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Devuelve o establece la configuración de una cámara. Solo lectura [ICamera](../../com.aspose.slides/icamera).

**Devuelve:**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Devuelve o establece el tipo de una luz. Solo lectura [ILightRig](../../com.aspose.slides/ilightrig).

**Devuelve:**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Devuelve o establece el tipo de un material. Lectura/escritura [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Devuelve:**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Devuelve o establece el tipo de un material. Lectura/escritura [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parámetros:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Obtiene los datos de formato 3D efectivos con la herencia aplicada.

**Devuelve:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).