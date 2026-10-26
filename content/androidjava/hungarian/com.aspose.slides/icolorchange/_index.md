---
title: IColorChange
second_title: Aspose.Slides Androidra Java API hivatkozás
description: Színváltoztatási effektet képvisel.
type: docs
url: /hu/com.aspose.slides/icolorchange/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Színváltoztatási effektet képvisel. A FromColor példányai a ToColor példányaival lesznek helyettesítve.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getFromColor()](#getFromColor--) | A Color, amely helyettesítésre kerül. |
| [getToColor()](#getToColor--) | A Color, amely helyettesíti. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


A Color, amely helyettesítésre kerül. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


A Color, amely helyettesíti. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Visszatérési érték:**
[IColorFormat](../../com.aspose.slides/icolorformat)