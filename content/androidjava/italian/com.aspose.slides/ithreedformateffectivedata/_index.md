---
title: IThreeDFormatEffectiveData
second_title: Riferimento API Java di Aspose.Slides per Android
description: Oggetto immutabile che rappresenta le proprietà di formattazione 3-D effettive.
type: docs
url: /it/com.aspose.slides/ithreedformateffectivedata/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormatEffectiveData extends IThreeDParamSource
```

Oggetto immutabile che rappresenta le proprietà di formattazione 3-D effettive.

--------------------

Questa interfaccia è utilizzata insieme all'interfaccia [IThreeDFormat](../../com.aspose.slides/ithreedformat) per restituire i valori di formattazione effettivi con ereditarietà applicata.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Restituisce la larghezza di un contorno 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Restituisce l'altezza di un effetto di estrusione. |
| [getDepth()](#getDepth--) | Restituisce la profondità di una forma 3D. |
| [getBevelTop()](#getBevelTop--) | Restituisce il tipo di smussatura 3D superiore. |
| [getBevelBottom()](#getBevelBottom--) | Restituisce il tipo di smussatura 3D inferiore. |
| [getContourColor()](#getContourColor--) | Restituisce il colore di un contorno. |
| [getExtrusionColor()](#getExtrusionColor--) | Restituisce il colore di un'estrusione. |
| [getCamera()](#getCamera--) | Restituisce le impostazioni di una fotocamera. |
| [getLightRig()](#getLightRig--) | Restituisce il tipo di luce. |
| [getMaterial()](#getMaterial--) | Restituisce il tipo di materiale. |
### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```


Restituisce la larghezza di un contorno 3D. sola lettura double.

**Restituisce:**
double
### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```


Restituisce l'altezza di un effetto di estrusione. sola lettura double.

**Restituisce:**
double
### getDepth() {#getDepth--}
```
public abstract double getDepth()
```


Restituisce la profondità di una forma 3D. sola lettura double.

**Restituisce:**
double
### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevelEffectiveData getBevelTop()
```


Restituisce il tipo di smussatura 3D superiore. sola lettura [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Restituisce:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevelEffectiveData getBevelBottom()
```


Restituisce il tipo di smussatura 3D inferiore. sola lettura [IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata).

**Restituisce:**
[IShapeBevelEffectiveData](../../com.aspose.slides/ishapebeveleffectivedata)
### getContourColor() {#getContourColor--}
```
public abstract Integer getContourColor()
```


Restituisce il colore di un contorno. sola lettura java.lang.Integer.

**Restituisce:**
java.lang.Integer
### getExtrusionColor() {#getExtrusionColor--}
```
public abstract Integer getExtrusionColor()
```


Restituisce il colore di un'estrusione. sola lettura java.lang.Integer.

**Restituisce:**
java.lang.Integer
### getCamera() {#getCamera--}
```
public abstract ICameraEffectiveData getCamera()
```


Restituisce le impostazioni di una fotocamera. sola lettura [ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata).

**Restituisce:**
[ICameraEffectiveData](../../com.aspose.slides/icameraeffectivedata)
### getLightRig() {#getLightRig--}
```
public abstract ILightRigEffectiveData getLightRig()
```


Restituisce il tipo di luce. sola lettura [ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata).

**Restituisce:**
[ILightRigEffectiveData](../../com.aspose.slides/ilightrigeffectivedata)
### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```


Restituisce il tipo di materiale. sola lettura [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Restituisce:**
int