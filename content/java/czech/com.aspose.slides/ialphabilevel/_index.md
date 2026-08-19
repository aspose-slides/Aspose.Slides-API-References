---
title: IAlphaBiLevel
second_title: Aspose.Slides pro Java – reference API
description: Představuje efekt Alpha Bi-Level.
type: docs
url: /cs/com.aspose.slides/ialphabilevel/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Představuje efekt Alpha Bi-Level. Hodnoty Alpha (průhlednosti) menší než práh jsou změněny na 0 (zcela průhledné) a hodnoty alpha větší nebo rovné prahu jsou změněny na 100% (zcela neprůhledné).

--------------------

Použijte ImageTransformOperationFactory k vytvoření instancí v COM.
## Metody

| Metoda | Popis |
| --- | --- |
| [getThreshold()](#getThreshold--) | Vrací práh efektu. |
| [setThreshold(float value)](#setThreshold-float-) | Vrací práh efektu. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Vrací práh efektu. Číst/zapisovat float.

**Vrací:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Vrací práh efektu. Číst/zapisovat float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |