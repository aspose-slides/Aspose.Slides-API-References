---
title: IAlphaBiLevel
second_title: Aspose.Slides Java API hivatkozás
description: Ábrázol egy Alpha bi-szintű hatást.
type: docs
url: /hu/com.aspose.slides/ialphabilevel/
---
**All Implemented Interfaces:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IAlphaBiLevel extends IImageTransformOperation, IAccessiblePVIObject<IAlphaBiLevelEffectiveData>
```

Ábrázol egy Alpha bi-szintű hatást. Az Alpha (Opacity) értékek, amelyek kisebbek a küszöbnél, 0-ra (teljesen átlátszó) változnak, és az alpha értékek, amelyek nagyobbak vagy egyenlőek a küszöbbel, 100%-ra (teljesen átlátszatlan) változnak.

--------------------

Használja az ImageTransformOperationFactory-t a COM-ban lévő instaces létrehozásához.

## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getThreshold()](#getThreshold--) | Visszaadja a hatás küszöbét. |
| [setThreshold(float value)](#setThreshold-float-) | Visszaadja a hatás küszöbét. |
### getThreshold() {#getThreshold--}
```
public abstract float getThreshold()
```

Visszaadja a hatás küszöbét. Olvasás/írás float.

**Visszatér:**  
float
### setThreshold(float value) {#setThreshold-float-}
```
public abstract void setThreshold(float value)
```

Visszaadja a hatás küszöbét. Olvasás/írás float.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | float |  |