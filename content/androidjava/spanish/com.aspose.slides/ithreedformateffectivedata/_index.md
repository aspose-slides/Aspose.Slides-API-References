---
title: IThreeDFormatEffectiveData
second_title: Referencia de la API Java de Aspose.Slides para Android
description: Objeto inmutable que representa las propiedades de formato 3-D efectivas.
type: docs
url: /es/com.aspose.slides/ithreedformateffectivedata/
---
**Todas las interfaces implementadas:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Objeto inmutable que representa las propiedades de formato 3-D efectivas.

--------------------

Esta interfaz se usa junto con la interfaz [IThreeDFormat](../../com.aspose.slides/ithreedformat) para devolver valores de formato efectivos con herencia aplicada.
## Métodos

| Método | Descripción |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Devuelve el ancho de un contorno 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Devuelve la altura de un efecto de extrusión. |
| [getDepth()](#getDepth--) | Devuelve la profundidad de una forma 3D. |
| [getBevelTop()](#getBevelTop--) | Devuelve el tipo de un bisel superior 3D. |
| [getBevelBottom()](#getBevelBottom--) | Devuelve el tipo de un bisel inferior 3D. |
| [getContourColor()](#getContourColor--) | Devuelve el color de un contorno. |
| [getExtrusionColor()](#getExtrusionColor--) | Devuelve el color de una extrusión. |
| [getCamera()](#getCamera--) | Devuelve la configuración de una cámara. |
| [getLightRig()](#getLightRig--) | Devuelve el tipo de una luz. |
| [getMaterial()](#getMaterial--) | Devuelve el tipo de un material. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Devuelve el ancho de un contorno 3D. Sólo lectura double.

**Devuelve:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Devuelve la altura de un efecto de extrusión. Sólo lectura double.

**Devuelve:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Devuelve la profundidad de una forma 3D. Sólo lectura double.

**Devuelve:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Devuelve el tipo de un bisel superior 3D. Sólo lectura [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Devuelve:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Devuelve el tipo de un bisel inferior 3D. Sólo lectura [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Devuelve:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```

Devuelve el color de un contorno. Sólo lectura java.lang.Integer.

**Devuelve:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```

Devuelve el color de una extrusión. Sólo lectura java.lang.Integer.

**Devuelve:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

Devuelve la configuración de una cámara. Sólo lectura [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Devuelve:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

Devuelve el tipo de una luz. Sólo lectura [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Devuelve:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Devuelve el tipo de un material. Sólo lectura [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Devuelve:**
int