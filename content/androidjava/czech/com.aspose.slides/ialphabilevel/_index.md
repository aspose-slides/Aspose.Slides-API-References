---
title: IAlphaBiLevel
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Representuje efekt Alpha Bi-Level.
type: docs
url: /cs/com.aspose.slides/ialphabilevel/
---
**Všechna implementovaná rozhraní:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Representuje efekt Alpha Bi-Level. Alpha (Opacity) values less than the threshold are changed to 0 (zcela průhledné) and alpha values greater than or equal to the threshold are changed to 100 % (zcela neprůhledné).

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

Vrací práh efektu. Čtení/zápis float.

**Vrací:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

Vrací práh efektu. Čtení/zápis float.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | float |  |