---
title: Backdrop3DScene
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Definisce un piano in cui gli effetti, come bagliore e ombra, vengono applicati in relazione alla forma a cui sono applicati.
type: docs
url: /it/com.aspose.slides/backdrop3dscene/
---
**Eredità:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Tutte le interfacce implementate:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Definisce un piano in cui gli effetti, come bagliore e ombra, vengono applicati in relazione alla forma a cui sono applicati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Restituisce o imposta un vettore normale. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Restituisce o imposta un vettore normale. |
| [getAnchorPoint()](#getAnchorPoint--) | Restituisce o imposta un punto nello spazio 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Restituisce o imposta un punto nello spazio 3D. |
| [getUpVector()](#getUpVector--) | Restituisce o imposta un vettore che rappresenta l'alto. |
| [setUpVector(float[] value)](#setUpVector-float---) | Restituisce o imposta un vettore che rappresenta l'alto. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Versione. Solo lettura long.

**Restituisce:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Restituisce o imposta un vettore normale. Per essere più precisi, questo attributo definisce un vettore normale alla faccia del piano di sfondo. Vettore rappresentato da un array di 3 valori float che definiscono le coordinate X, Y e Z. Lettura/scrittura float[].

**Restituisce:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Restituisce o imposta un vettore normale. Per essere più precisi, questo attributo definisce un vettore normale alla faccia del piano di sfondo. Vettore rappresentato da un array di 3 valori float che definiscono le coordinate X, Y e Z. Lettura/scrittura float[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Restituisce o imposta un punto nello spazio 3D. Questo punto è il punto nello spazio che ancorra il piano di sfondo. Punto 3D rappresentato da un array di 3 valori float che definiscono le coordinate X, Y e Z. Lettura/scrittura float[].

**Restituisce:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Restituisce o imposta un punto nello spazio 3D. Questo punto è il punto nello spazio che ancorra il piano di sfondo. Punto 3D rappresentato da un array di 3 valori float che definiscono le coordinate X, Y e Z. Lettura/scrittura float[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Restituisce o imposta un vettore che rappresenta l'alto. Per essere più precisi, questo attributo definisce un vettore che rappresenta l'alto in relazione alla faccia del piano di sfondo. Vettore rappresentato da un array di 3 valori float che definiscono le coordinate X, Y e Z. Lettura/scrittura float[].

**Restituisce:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Restituisce o imposta un vettore che rappresenta l'alto. Per essere più precisi, questo attributo definisce un vettore che rappresenta l'alto in relazione alla faccia del piano di sfondo. Vettore rappresentato da un array di 3 valori float che definiscono le coordinate X, Y e Z. Lettura/scrittura float[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float[] |  |