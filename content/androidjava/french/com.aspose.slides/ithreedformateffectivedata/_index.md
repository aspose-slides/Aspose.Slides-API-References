---
title: IThreeDFormatEffectiveData
second_title: Référence de l'API Java Aspose.Slides pour Android
description: Objet immuable qui représente les propriétés de formatage 3-D effectives.
type: docs
url: /fr/com.aspose.slides/ithreedformateffectivedata/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Objet immuable qui représente les propriétés de formatage 3-D effectives.

--------------------

Cette interface est utilisée avec l'interface [IThreeDFormat](../../com.aspose.slides/ithreedformat) pour renvoyer les valeurs de formatage effectives avec l'héritage appliqué.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Renvoie la largeur d'un contour 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Renvoie la hauteur d'un effet d'extrusion. |
| [getDepth()](#getDepth--) | Renvoie la profondeur d'une forme 3D. |
| [getBevelTop()](#getBevelTop--) | Renvoie le type d'un chanfrein supérieur 3D. |
| [getBevelBottom()](#getBevelBottom--) | Renvoie le type d'un chanfrein inférieur 3D. |
| [getContourColor()](#getContourColor--) | Renvoie la couleur d'un contour. |
| [getExtrusionColor()](#getExtrusionColor--) | Renvoie la couleur d'une extrusion. |
| [getCamera()](#getCamera--) | Renvoie les paramètres d'une caméra. |
| [getLightRig()](#getLightRig--) | Renvoie le type d'un éclairage. |
| [getMaterial()](#getMaterial--) | Renvoie le type d'un matériau. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Renvoie la largeur d'un contour 3D. Lecture seule double.

**Retourne :**  
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Renvoie la hauteur d'un effet d'extrusion. Lecture seule double.

**Retourne :**  
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Renvoie la profondeur d'une forme 3D. Lecture seule double.

**Retourne :**  
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Renvoie le type d'un chanfrein supérieur 3D. Lecture seule [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Retourne :**  
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Renvoie le type d'un chanfrein inférieur 3D. Lecture seule [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Retourne :**  
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```

Renvoie la couleur d'un contour. Lecture seule java.lang.Integer.

**Retourne :**  
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```

Renvoie la couleur d'une extrusion. Lecture seule java.lang.Integer.

**Retourne :**  
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

Renvoie les paramètres d'une caméra. Lecture seule [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Retourne :**  
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

Renvoie le type d'un éclairage. Lecture seule [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Retourne :**  
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Renvoie le type d'un matériau. Lecture seule [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Retourne :**  
int