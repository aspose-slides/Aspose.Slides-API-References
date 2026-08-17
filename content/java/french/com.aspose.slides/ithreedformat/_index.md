---
title: IThreeDFormat
second_title: Référence de l'API Aspose.Slides pour Java
description: Représente les propriétés 3-D.
type: docs
url: /fr/com.aspose.slides/ithreedformat/
---
**Toutes les interfaces implémentées :**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Représente les propriétés 3D.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Renvoie ou définit la largeur d'un contour 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Renvoie ou définit la largeur d'un contour 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Renvoie ou définit la hauteur d'un effet d'extrusion. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Renvoie ou définit la hauteur d'un effet d'extrusion. |
| [getDepth()](#getDepth--) | Renvoie ou définit la profondeur d'une forme 3D. |
| [setDepth(double value)](#setDepth-double-) | Renvoie ou définit la profondeur d'une forme 3D. |
| [getBevelTop()](#getBevelTop--) | Renvoie ou définit le type d'un chanfrein supérieur 3D. |
| [getBevelBottom()](#getBevelBottom--) | Renvoie ou définit le type d'un chanfrein inférieur 3D. |
| [getContourColor()](#getContourColor--) | Renvoie ou définit la couleur d'un contour. |
| [getExtrusionColor()](#getExtrusionColor--) | Renvoie ou définit la couleur d'une extrusion. |
| [getCamera()](#getCamera--) | Renvoie ou définit les paramètres d'une caméra. |
| [getLightRig()](#getLightRig--) | Renvoie ou définit le type d'une lumière. |
| [getMaterial()](#getMaterial--) | Renvoie ou définit le type d'un matériau. |
| [setMaterial(int value)](#setMaterial-int-) | Renvoie ou définit le type d'un matériau. |
| [getEffective()](#getEffective--) | Obtient les données de formatage 3D effectives avec l'héritage appliqué. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Renvoie ou définit la largeur d'un contour 3D. Lecture/écriture double.

**Retour :**
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```


Renvoie ou définit la largeur d'un contour 3D. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Renvoie ou définit la hauteur d'un effet d'extrusion. Lecture/écriture double.

**Retour :**
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```


Renvoie ou définit la hauteur d'un effet d'extrusion. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Renvoie ou définit la profondeur d'une forme 3D. Lecture/écriture double.

**Retour :**
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```


Renvoie ou définit la profondeur d'une forme 3D. Lecture/écriture double.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```


Renvoie ou définit le type d'un chanfrein supérieur 3D. Lecture seule [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retour :**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```


Renvoie ou définit le type d'un chanfrein inférieur 3D. Lecture seule [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retour :**
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```


Renvoie ou définit la couleur d'un contour. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```


Renvoie ou définit la couleur d'une extrusion. Lecture seule [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour :**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```


Renvoie ou définit les paramètres d'une caméra. Lecture seule [ICamera](../../com.aspose.slides/icamera).

**Retour :**
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```


Renvoie ou définit le type d'une lumière. Lecture seule [ILightRig](../../com.aspose.slides/ilightrig).

**Retour :**
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Renvoie ou définit le type d'un matériau. Lecture/écriture [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Retour :**
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```


Renvoie ou définit le type d'un matériau. Lecture/écriture [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```


Obtient les données de formatage 3D effectives avec l'héritage appliqué.

**Retour :**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - Un [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).