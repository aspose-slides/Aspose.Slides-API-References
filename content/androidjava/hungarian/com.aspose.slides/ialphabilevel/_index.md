---
title: IAlphaBiLevel
second_title: Aspose.Slides Android számára Java API referenciája
description: Alfa kettős szintű hatást ábrázol.
type: docs
url: /hu/com.aspose.slides/ialphabilevel/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Alfa kettős szintű hatást ábrázol. Az alfa (átlátszóság) értékek, amelyek kisebbek a küszöbnél, 0-ra (teljesen átlátszó) módosulnak, a küszögnél nagyobb vagy egyenlő alfa értékek 100%-ra (teljesen átlátszatlan) módosulnak.

--------------------

Az ImageTransformOperationFactory használatával példányokat hozhat létre COM-ban.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getThreshold()](#getThreshold--) | Visszaadja a hatás küszöbértékét. |
| [setThreshold(float value)](#setThreshold-float-) | Visszaadja a hatás küszöbértékét. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```


Visszaadja a hatás küszöbértékét. Olvasás/írás float.

**Visszatérési érték:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```


Visszaadja a hatás küszöbértékét. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |