---
title: IBackdrop3DScene
second_title: Aspose.Slides per Android tramite Riferimento API Java
description: Definisce un piano in cui effetti come bagliore e ombra vengono applicati in relazione alla forma a cui sono applicati.
type: docs
url: /it/com.aspose.slides/ibackdrop3dscene/
---```
public interface IBackdrop3DScene
```

Definisce un piano in cui effetti, come bagliore e ombra, vengono applicati in relazione alla forma a cui sono applicati.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Restituisce o imposta un vettore normale. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Restituisce o imposta un vettore normale. |
| [getAnchorPoint()](#getAnchorPoint--) | Restituisce o imposta un punto nello spazio 3D. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Restituisce o imposta un punto nello spazio 3D. |
| [getUpVector()](#getUpVector--) | Restituisce o imposta un vettore che rappresenta l'alto. |
| [setUpVector(float[] value)](#setUpVector-float---) | Restituisce o imposta un vettore che rappresenta l'alto. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```


Restituisce o imposta un vettore normale. Per essere più precisi, questo attributo definisce un vettore normale alla faccia del piano di sfondo. Vettore rappresentato da un array di 3 valori float che definiscono le coordinate X, Y e Z. Lettura/scrittura float[].

**Restituisce:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```


Restituisce o imposta un vettore normale. Per essere più precisi, questo attributo definisce un vettore normale alla faccia del piano di sfondo. Vettore rappresentato da un array di 3 valori float che definiscono le coordinate X, Y e Z. Lettura/scrittura float[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```


Restituisce o imposta un punto nello spazio 3D. Questo punto è il punto nello spazio che fissa il piano di sfondo. Punto 3D rappresentato da un array di 3 valori float che definiscono le coordinate X, Y e Z. Lettura/scrittura float[].

**Restituisce:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```


Restituisce o imposta un punto nello spazio 3D. Questo punto è il punto nello spazio che fissa il piano di sfondo. Punto 3D rappresentato da un array di 3 valori float che definiscono le coordinate X, Y e Z. Lettura/scrittura float[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```


Restituisce o imposta un vettore che rappresenta l'alto. Per essere più precisi, questo attributo definisce un vettore che rappresenta l'alto in relazione alla faccia del piano di sfondo. Vettore rappresentato da un array di 3 valori float che definiscono le coordinate X, Y e Z. Lettura/scrittura float[].

**Restituisce:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```


Restituisce o imposta un vettore che rappresenta l'alto. Per essere più precisi, questo attributo definisce un vettore che rappresenta l'alto in relazione alla faccia del piano di sfondo. Vettore rappresentato da un array di 3 valori float che definiscono le coordinate X, Y e Z. Lettura/scrittura float[].

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | float[] |  |