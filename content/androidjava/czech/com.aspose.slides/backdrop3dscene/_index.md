---
title: Backdrop3DScene
second_title: Aspose.Slides pro Android přes referenci Java API
description: Definuje rovinu, ve které jsou efekty, jako je záře a stín, aplikovány ve vztahu k tvaru, na který jsou aplikovány.
type: docs
url: /cs/com.aspose.slides/backdrop3dscene/
---
**Dědičnost:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Všechna implementovaná rozhraní:**
[com.aspose.slides.IBackdrop3DScene](../../com.aspose.slides/ibackdrop3dscene)
```
public final class Backdrop3DScene extends PVIObject implements IBackdrop3DScene
```

Definuje rovinu, ve které jsou efekty, jako je záře a stín, aplikovány ve vztahu k tvaru, na který jsou aplikovány.
## Metody

| Metoda | Popis |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNormalVector()](#getNormalVector--) | Vrací nebo nastavuje normálový vektor. |
| [setNormalVector(float[] value)](#setNormalVector-float---) | Vrací nebo nastavuje normálový vektor. |
| [getAnchorPoint()](#getAnchorPoint--) | Vrací nebo nastavuje bod ve 3D prostoru. |
| [setAnchorPoint(float[] value)](#setAnchorPoint-float---) | Vrací nebo nastavuje bod ve 3D prostoru. |
| [getUpVector()](#getUpVector--) | Vrací nebo nastavuje vektor představující směr nahoru. |
| [setUpVector(float[] value)](#setUpVector-float---) | Vrací nebo nastavuje vektor představující směr nahoru. |
### getVersion() {#getVersion--}
```
public long getVersion()
```

Verze. Pouze pro čtení, long.

**Vrací:**
long
### getNormalVector() {#getNormalVector--}
```
public final float[] getNormalVector()
```

Vrací nebo nastavuje normálový vektor. Přesněji řečeno, tento atribut definuje vektor kolmo na plochu pozadí. Vektor je reprezentován polem 3 hodnot typu float, které definují souřadnice X, Y a Z. Čtení/zápis float[].

**Vrací:**
float[]
### setNormalVector(float[] value) {#setNormalVector-float---}
```
public final void setNormalVector(float[] value)
```

Vrací nebo nastavuje normálový vektor. Přesněji řečeno, tento atribut definuje vektor kolmo na plochu pozadí. Vektor je reprezentován polem 3 hodnot typu float, které definují souřadnice X, Y a Z. Čtení/zápis float[].

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float[] |  |

### getAnchorPoint() {#getAnchorPoint--}
```
public final float[] getAnchorPoint()
```

Vrací nebo nastavuje bod ve 3D prostoru. Tento bod je bodem v prostoru, který zakotvuje rovinu pozadí. 3D bod je reprezentován polem 3 hodnot typu float, které definují souřadnice X, Y a Z. Čtení/zápis float[].

**Vrací:**
float[]
### setAnchorPoint(float[] value) {#setAnchorPoint-float---}
```
public final void setAnchorPoint(float[] value)
```

Vrací nebo nastavuje bod ve 3D prostoru. Tento bod je bodem v prostoru, který zakotvuje rovinu pozadí. 3D bod je reprezentován polem 3 hodnot typu float, které definují souřadnice X, Y a Z. Čtení/zápis float[].

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float[] |  |

### getUpVector() {#getUpVector--}
```
public final float[] getUpVector()
```

Vrací nebo nastavuje vektor představující směr nahoru. Přesněji řečeno, tento atribut definuje vektor představující směr nahoru ve vztahu k ploše pozadí. Vektor je reprezentován polem 3 hodnot typu float, které definují souřadnice X, Y a Z. Čtení/zápis float[].

**Vrací:**
float[]
### setUpVector(float[] value) {#setUpVector-float---}
```
public final void setUpVector(float[] value)
```

Vrací nebo nastavuje vektor představující směr nahoru. Přesněji řečeno, tento atribut definuje vektor představující směr nahoru ve vztahu k ploše pozadí. Vektor je reprezentován polem 3 hodnot typu float, které definují souřadnice X, Y a Z. Čtení/zápis float[].

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float[] |  |