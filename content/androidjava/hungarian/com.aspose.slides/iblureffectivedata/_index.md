---
title: IBlurEffectiveData
second_title: Aspose.Slides for Android a Java API hivatkozáson keresztül
description: Megváltoztathatatlan objektum, amely egy Blur hatást képvisel, amely az egész alakzatra, beleértve a kitöltését is, alkalmazva van.
type: docs
url: /hu/com.aspose.slides/iblureffectivedata/
---
**Minden implementált interfész:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Megváltoztathatatlan objektum, amely egy Blur hatást képvisel, amely az egész alakzatra, beleértve a kitöltését is, alkalmazva van. Minden színcsatorna, beleértve az alfát is, érintett.
## Módszerek

| Method | Description |
| --- | --- |
| [getRadius()](#getRadius--) | Visszaadja vagy beállítja az elmosódási sugár értékét. |
| [getGrow()](#getGrow--) | Megállapítja, hogy az objektum határai a elmosódás következtében növekedni kell-e. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Visszaadja vagy beállítja az elmosódási sugár értékét. Csak olvasható double.

**Visszatér:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Megállapítja, hogy az objektum határai a elmosódás következtében növekedni kell-e. Az igaz érték azt jelzi, hogy a határok növekednek, míg a hamis azt, hogy nem. Csak olvasható boolean.

**Visszatér:**
boolean