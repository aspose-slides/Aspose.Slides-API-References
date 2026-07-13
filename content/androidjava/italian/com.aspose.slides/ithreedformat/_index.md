---
title: IThreeDFormat
second_title: Riferimento API Java di Aspose.Slides per Android
description: Rappresenta le proprietà 3-D.
type: docs
url: /it/com.aspose.slides/ithreedformat/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IThreeDParamSource](../../com.aspose.slides/ithreedparamsource)
```
public interface IThreeDFormat extends IThreeDParamSource
```

Rappresenta le proprietà 3-D.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getContourWidth()](#getContourWidth--) | Restituisce o imposta la larghezza di un contorno 3D. |
| [setContourWidth(double value)](#setContourWidth-double-) | Restituisce o imposta la larghezza di un contorno 3D. |
| [getExtrusionHeight()](#getExtrusionHeight--) | Restituisce o imposta l'altezza di un effetto di estrusione. |
| [setExtrusionHeight(double value)](#setExtrusionHeight-double-) | Restituisce o imposta l'altezza di un effetto di estrusione. |
| [getDepth()](#getDepth--) | Restituisce o imposta la profondità di una forma 3D. |
| [setDepth(double value)](#setDepth-double-) | Restituisce o imposta la profondità di una forma 3D. |
| [getBevelTop()](#getBevelTop--) | Restituisce o imposta il tipo di un rientro 3D superiore. |
| [getBevelBottom()](#getBevelBottom--) | Restituisce o imposta il tipo di un rientro 3D inferiore. |
| [getContourColor()](#getContourColor--) | Restituisce o imposta il colore di un contorno. |
| [getExtrusionColor()](#getExtrusionColor--) | Restituisce o imposta il colore di un'estrusione. |
| [getCamera()](#getCamera--) | Restituisce o imposta le impostazioni di una fotocamera. |
| [getLightRig()](#getLightRig--) | Restituisce o imposta il tipo di una luce. |
| [getMaterial()](#getMaterial--) | Restituisce o imposta il tipo di un materiale. |
| [setMaterial(int value)](#setMaterial-int-) | Restituisce o imposta il tipo di un materiale. |
| [getEffective()](#getEffective--) | Ottiene i dati di formattazione 3-D effettivi con l'ereditarietà applicata. |

### getContourWidth() {#getContourWidth--}
```
public abstract double getContourWidth()
```

Restituisce o imposta la larghezza di un contorno 3D. Lettura/scrittura double.

**Restituisce:**
double

### setContourWidth(double value) {#setContourWidth-double-}
```
public abstract void setContourWidth(double value)
```

Restituisce o imposta la larghezza di un contorno 3D. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getExtrusionHeight() {#getExtrusionHeight--}
```
public abstract double getExtrusionHeight()
```

Restituisce o imposta l'altezza di un effetto di estrusione. Lettura/scrittura double.

**Restituisce:**
double

### setExtrusionHeight(double value) {#setExtrusionHeight-double-}
```
public abstract void setExtrusionHeight(double value)
```

Restituisce o imposta l'altezza di un effetto di estrusione. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getDepth() {#getDepth--}
```
public abstract double getDepth()
```

Restituisce o imposta la profondità di una forma 3D. Lettura/scrittura double.

**Restituisce:**
double

### setDepth(double value) {#setDepth-double-}
```
public abstract void setDepth(double value)
```

Restituisce o imposta la profondità di una forma 3D. Lettura/scrittura double.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | double |  |

### getBevelTop() {#getBevelTop--}
```
public abstract IShapeBevel getBevelTop()
```

Restituisce o imposta il tipo di un rientro 3D superiore. Solo lettura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Restituisce:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getBevelBottom() {#getBevelBottom--}
```
public abstract IShapeBevel getBevelBottom()
```

Restituisce o imposta il tipo di un rientro 3D inferiore. Solo lettura [IShapeBevel](../../com.aspose.slides/ishapebevel).

**Restituisce:**
[IShapeBevel](../../com.aspose.slides/ishapebevel)

### getContourColor() {#getContourColor--}
```
public abstract IColorFormat getContourColor()
```

Restituisce o imposta il colore di un contorno. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getExtrusionColor() {#getExtrusionColor--}
```
public abstract IColorFormat getExtrusionColor()
```

Restituisce o imposta il colore di un'estrusione. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)

### getCamera() {#getCamera--}
```
public abstract ICamera getCamera()
```

Restituisce o imposta le impostazioni di una fotocamera. Solo lettura [ICamera](../../com.aspose.slides/icamera).

**Restituisce:**
[ICamera](../../com.aspose.slides/icamera)

### getLightRig() {#getLightRig--}
```
public abstract ILightRig getLightRig()
```

Restituisce o imposta il tipo di una luce. Solo lettura [ILightRig](../../com.aspose.slides/ilightrig).

**Restituisce:**
[ILightRig](../../com.aspose.slides/ilightrig)

### getMaterial() {#getMaterial--}
```
public abstract int getMaterial()
```

Restituisce o imposta il tipo di un materiale. Lettura/scrittura [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Restituisce:**
int

### setMaterial(int value) {#setMaterial-int-}
```
public abstract void setMaterial(int value)
```

Restituisce o imposta il tipo di un materiale. Lettura/scrittura [MaterialPresetType](../../com.aspose.slides/materialpresettype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public abstract IThreeDFormatEffectiveData getEffective()
```

Ottiene i dati di formattazione 3-D effettivi con l'ereditarietà applicata.

**Restituisce:**
[IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata) - A [IThreeDFormatEffectiveData](../../com.aspose.slides/ithreedformateffectivedata).