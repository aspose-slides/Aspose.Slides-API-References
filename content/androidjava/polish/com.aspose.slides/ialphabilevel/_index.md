---
title: IAlphaBiLevel
second_title: Aspose.Slides dla Androida za pośrednictwem dokumentacji API Java
description: Reprezentuje efekt Alpha Bi-Level.
type: docs
url: /pl/com.aspose.slides/ialphabilevel/
---
**Wszystkie zaimplementowane interfejsy:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Reprezentuje efekt Alpha Bi-Level. Wartości Alpha (Opacity) mniejsze niż próg są zmieniane na 0 (całkowicie przezroczyste), a wartości alpha większe lub równe progowi są zmieniane na 100 % (całkowicie nieprzezroczyste).

--------------------

Użyj ImageTransformOperationFactory do tworzenia instancji w COM.
## Metody

| Metoda | Opis |
| --- | --- |
| [getThreshold()](#getThreshold--) | Zwraca próg efektu. |
| [setThreshold(float value)](#setThreshold-float-) | Zwraca próg efektu. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Zwraca próg efektu. Odczyt/zapis float.

**Zwraca:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Zwraca próg efektu. Odczyt/zapis float.

**Parametry:**
| Parametr | Typ | Opis |
| --- | --- | --- |
| value | float |  |