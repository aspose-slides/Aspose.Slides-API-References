---
title: IThreeDFormatEffectiveData
second_title: Référence de l'API Aspose.Slides pour Java
description: Objet immuable qui représente les propriétés de formatage 3-D effectives.
type: docs
url: /fr/com.aspose.slides/ithreedformateffectivedata/
---
**Toutes les interfaces implémentées:**  
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Objet immuable qui représente les propriétés de formatage 3-D effectives.

--------------------

Cette interface est utilisée avec l'interface [IThreeDFormat](../../com.aspose.slides/ithreedformat) pour retourner les valeurs de formatage effectives avec l'héritage appliqué.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Renvoie la largeur d'un contour 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Renvoie la hauteur d'un effet d'extrusion. |
| [getDepth()](#getDepth--) | Renvoie la profondeur d'une forme 3D. |
| [getBevelTop()](#getBevelTop--) | Renvoie le type d'un biseau 3D supérieur. |
| [getBevelBottom()](#getBevelBottom--) | Renvoie le type d'un biseau 3D inférieur. |
| [getContourColor()](#getContourColor--) | Renvoie la couleur d'un contour. |
| [getExtrusionColor()](#getExtrusionColor--) | Renvoie la couleur d'une extrusion. |
| [getCamera()](#getCamera--) | Renvoie les paramètres d'une caméra. |
| [getLightRig()](#getLightRig--) | Renvoie le type d'une lumière. |
| [getMaterial()](#getMaterial--) | Renvoie le type d'un matériau. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Renvoie la largeur d'un contour 3D. Lecture seule double.

**Renvoie:**  
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Renvoie la hauteur d'un effet d'extrusion. Lecture seule double.

**Renvoie:**  
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Renvoie la profondeur d'une forme 3D. Lecture seule double.

**Renvoie:**  
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Renvoie le type d'un biseau 3D supérieur. Lecture seule [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Renvoie:**  
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Renvoie le type d'un biseau 3D inférieur. Lecture seule [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Renvoie:**  
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Color getContourColor()
```

Renvoie la couleur d'un contour. Lecture seule java.awt.Color.

**Renvoie:**  
java.awt.Color
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Color getExtrusionColor()
```

Renvoie la couleur d'une extrusion. Lecture seule java.awt.Color.

**Renvoie:**  
java.awt.Color
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

Renvoie les paramètres d'une caméra. Lecture seule [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Renvoie:**  
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

Renvoie le type d'une lumière. Lecture seule [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Renvoie:**  
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Renvoie le type d'un matériau. Lecture seule [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Renvoie:**  
int