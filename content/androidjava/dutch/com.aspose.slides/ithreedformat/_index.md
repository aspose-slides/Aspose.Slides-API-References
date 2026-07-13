---
title: IThreeDFormat
second_title: Aspose.Slides voor Android via Java API-referentie
description: Stelt 3-D-eigenschappen voor.
type: docs
url: /nl/com.aspose.slides/ithreedformat/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Representeert 3-D-eigenschappen.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Geeft de breedte van een 3D-contour terug of stelt deze in. |
| [setContourWidth(double value)](#setContourWidth-double-) | Geeft de breedte van een 3D-contour terug of stelt deze in. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Geeft de hoogte van een extrusie-effect terug of stelt deze in. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Geeft de hoogte van een extrusie-effect terug of stelt deze in. |
| [getDepth()](#getDepth--) | Geeft de diepte van een 3D-vorm terug of stelt deze in. |
| [setDepth(double value)](#setDepth-double-) | Geeft de diepte van een 3D-vorm terug of stelt deze in. |
| [getBevelTop()](#getBevelTop--) | Geeft het type van een bovenste 3D-afschuining terug of stelt dit in. |
| [getBevelBottom()](#getBevelBottom--) | Geeft het type van een onderste 3D-afschuining terug of stelt dit in. |
| [getContourColor()](#getContourColor--) | Geeft de kleur van een contour terug of stelt deze in. |
| [getExtrusionColor()](#getExtrusionColor--) | Geeft de kleur van een extrusie terug of stelt deze in. |
| [getCamera()](#getCamera--) | Geeft de instellingen van een camera terug of stelt deze in. |
| [getLightRig()](#getLightRig--) | Geeft het type van een licht terug of stelt dit in. |
| [getMaterial()](#getMaterial--) | Geeft het type van een materiaal terug of stelt dit in. |
| [setMaterial(int value)](#setMaterial-int-) | Geeft het type van een materiaal terug of stelt dit in. |
| [getEffective()](#getEffective--) | Haalt effectieve 3-D-opmaakgegevens op met de overerving toegepast. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Geeft de breedte van een 3D-contour terug of stelt deze in. Lezen/schrijven double.

**Retour:**  
double
### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```


Stelt de breedte van een 3D-contour in of geeft deze terug. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Geeft de hoogte van een extrusie-effect terug of stelt deze in. Lezen/schrijven double.

**Retour:**  
double
### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```


Stelt de hoogte van een extrusie-effect in of geeft deze terug. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Geeft de diepte van een 3D-vorm terug of stelt deze in. Lezen/schrijven double.

**Retour:**  
double
### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```


Stelt de diepte van een 3D-vorm in of geeft deze terug. Lezen/schrijven double.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | double |  |
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```


Geeft het type van een bovenste 3D-afschuining terug. Alleen-lezen [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retour:**  
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```


Geeft het type van een onderste 3D-afschuining terug. Alleen-lezen [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Retour:**  
[IShapeBevel](../../com.aspose.slides/ishapebevel)
### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```


Geeft de kleur van een contour terug. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```


Geeft de kleur van een extrusie terug. Alleen-lezen [IColorFormat](../../com.aspose.slides/icolorformat).

**Retour:**  
[IColorFormat](../../com.aspose.slides/icolorformat)
### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```


Geeft de instellingen van een camera terug. Alleen-lezen [ICamera](../../com.aspose.slides/icamera).

**Retour:**  
[ICamera](../../com.aspose.slides/icamera)
### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```


Geeft het type van een licht terug. Alleen-lezen [ILightRig](../../com.aspose.slides/ilightrig).

**Retour:**  
[ILightRig](../../com.aspose.slides/ilightrig)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Geeft het type van een materiaal terug of stelt dit in. Lezen/schrijven [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Retour:**  
int
### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```


Stelt het type van een materiaal in of geeft dit terug. Lezen/schrijven [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | int |  |
### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```


Haalt effectieve 3-D-opmaakgegevens op met de overerving toegepast.

**Retour:**  
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - Een [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).