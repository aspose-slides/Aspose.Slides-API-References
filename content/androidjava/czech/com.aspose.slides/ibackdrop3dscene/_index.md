---
title: IBackdrop3DScene
second_title: Aspose.Slides for Android via Java API Reference
description: Definuje rovinu, ve které jsou efekty jako záře a stín aplikovány vzhledem k tvaru, na který jsou aplikovány.
type: docs
url: /cs/com.aspose.slides/ibackdrop3dscene/
---
```
public interface IBackdrop3DScene
```

Definuje rovinu, ve které jsou efekty, jako záře a stín, aplikovány vzhledem k tvaru, na který jsou aplikovány.
## Metody

| Metoda | Popis |
| --- | --- |
| [getNormalVector()](#getNormalVector--) | Vrací nebo nastavuje normální vektor. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Vrací nebo nastavuje normální vektor. |
| [getAnchorPoint()](#getAnchorPoint--) | Vrací nebo nastavuje bod ve 3D prostoru. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Vrací nebo nastavuje bod ve 3D prostoru. |
| [getUpVector()](#getUpVector--) | Vrací nebo nastavuje vektor představující směr nahoru. |
| [setUpVector(float[] value)](#setUpVector-float---) | Vrací nebo nastavuje vektor představující směr nahoru. |
### getNormalVector() {#getNormalVector--}
```
public abstract float[] getNormalVector()
```

Vrací nebo nastavuje normální vektor. Přesněji řečeno, tento atribut definuje vektor kolmo na plochu pozadí. Vektor je reprezentován polem 3 hodnot typu float, které určují souřadnice X, Y a Z. Čtení/zápis float[].

**Vrací:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public abstract void setNormalVector(float[] value)
```

Vrací nebo nastavuje normální vektor. Přesněji řečeno, tento atribut definuje vektor kolmo na plochu pozadí. Vektor je reprezentován polem 3 hodnot typu float, které určují souřadnice X, Y a Z. Čtení/zápis float[].

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float[] |  |
### getAnchorPoint() {#getAnchorPoint--}
```
public abstract float[] getAnchorPoint()
```

Vrací nebo nastavuje bod ve 3D prostoru. Tento bod je bodem v prostoru, který ukotvuje rovinu pozadí. 3D bod je reprezentován polem 3 hodnot typu float, které určují souřadnice X, Y a Z. Čtení/zápis float[].

**Vrací:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public abstract void setAnchorPoint(float[] value)
```

Vrací nebo nastavuje bod ve 3D prostoru. Tento bod je bodem v prostoru, který ukotvuje rovinu pozadí. 3D bod je reprezentován polem 3 hodnot typu float, které určují souřadnice X, Y a Z. Čtení/zápis float[].

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float[] |  |
### getUpVector() {#getUpVector--}
```
public abstract float[] getUpVector()
```

Vrací nebo nastavuje vektor představující směr nahoru. Přesněji řečeno, tento atribut definuje vektor představující směr nahoru vzhledem k ploše pozadí. Vektor je reprezentován polem 3 hodnot typu float, které určují souřadnice X, Y a Z. Čtení/zápis float[].

**Vrací:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public abstract void setUpVector(float[] value)
```

Vrací nebo nastavuje vektor představující směr nahoru. Přesněji řečeno, tento atribut definuje vektor představující směr nahoru vzhledem k ploše pozadí. Vektor je reprezentován polem 3 hodnot typu float, které určují souřadnice X, Y a Z. Čtení/zápis float[].

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float[] |  |