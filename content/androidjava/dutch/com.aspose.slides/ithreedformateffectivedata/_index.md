---
title: IThreeDFormatEffectiveData
second_title: Aspose.Slides voor Android via Java API-referentie
description: Onveranderlijk object dat de effectieve 3-D-opmaak eigenschappen vertegenwoordigt.
type: docs
url: /nl/com.aspose.slides/ithreedformateffectivedata/
---
**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Onveranderlijk object dat de effectieve 3-D-opmaak eigenschappen vertegenwoordigt.

--------------------

Deze interface wordt samen met de [IThreeDFormat](../../com.aspose.slides/ithreedformat) interface gebruikt om effectieve opmaakwaarden met toegepaste overerving te retourneren.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Retourneert de breedte van een 3D-contour. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Retourneert de hoogte van een extrusie-effect. |
| [getDepth()](#getDepth--) | Retourneert de diepte van een 3D-vorm. |
| [getBevelTop()](#getBevelTop--) | Retourneert het type van een bovenste 3D-afschuining. |
| [getBevelBottom()](#getBevelBottom--) | Retourneert het type van een onderste 3D-afschuining. |
| [getContourColor()](#getContourColor--) | Retourneert de kleur van een contour. |
| [getExtrusionColor()](#getExtrusionColor--) | Retourneert de kleur van een extrusie. |
| [getCamera()](#getCamera--) | Retourneert de instellingen van een camera. |
| [getLightRig()](#getLightRig--) | Retourneert het type van een licht. |
| [getMaterial()](#getMaterial--) | Retourneert het type van een materiaal. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Retourneert de breedte van een 3D-contour. Alleen-lezen double.

**Retour:**  
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Retourneert de hoogte van een extrusie-effect. Alleen-lezen double.

**Retour:**  
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Retourneert de diepte van een 3D-vorm. Alleen-lezen double.

**Retour:**  
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```

Retourneert het type van een bovenste 3D-afschuining. Alleen-lezen [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Retour:**  
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```

Retourneert het type van een onderste 3D-afschuining. Alleen-lezen [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Retour:**  
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```

Retourneert de kleur van een contour. Alleen-lezen java.lang.Integer.

**Retour:**  
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```

Retourneert de kleur van een extrusie. Alleen-lezen java.lang.Integer.

**Retour:**  
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```

Retourneert de instellingen van een camera. Alleen-lezen [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Retour:**  
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```

Retourneert het type van een licht. Alleen-lezen [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Retour:**  
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Retourneert het type van een materiaal. Alleen-lezen [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Retour:**  
int