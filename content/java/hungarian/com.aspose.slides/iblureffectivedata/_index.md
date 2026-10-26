---
title: IBlurEffectiveData
second_title: Aspose.Slides Java API referencia
description: Megváltoztathatatlan objektum, amely egy Blur hatást képvisel, amely az egész alakzatra, beleértve a kitöltését, alkalmazható.
type: docs
url: /hu/com.aspose.slides/iblureffectivedata/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IEffectEffectiveData](../../com.aspose.slides/ieffecteffectivedata)
```
public interface IBlurEffectiveData extends IEffectEffectiveData
```

Megváltoztathatatlan objektum, amely egy Blur hatást képvisel, amely az egész alakzatra, beleértve a kitöltését, alkalmazható. Minden színcsatorna, beleértve az alfát is, érintett.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getRadius()](#getRadius--) | Visszaadja vagy beállítja a blur sugarát. |
| [getGrow()](#getGrow--) | Meghatározza, hogy az objektum határai a blur hatás következtében növekedjenek-e. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Visszaadja vagy beállítja a blur sugarát. Csak olvasható double.

**Visszatérési érték:**
double
### getGrow() {#getGrow--}
```
public abstract boolean getGrow()
```


Meghatározza, hogy az objektum határai a blur hatás következtében növekedjenek-e. Az igaz érték azt jelzi, hogy a határok növekszenek, a hamis érték pedig, hogy nem. Csak olvasható boolean.

**Visszatérési érték:**
boolean