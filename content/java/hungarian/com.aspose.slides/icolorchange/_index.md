---
title: IColorChange
second_title: Aspose.Slides Java API referencia
description: Egy színváltozási hatást reprezentál.
type: docs
url: /hu/com.aspose.slides/icolorchange/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Egy színváltozás effektust reprezentál. A FromColor példányait a ToColor példányai helyettesítik.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getFromColor()](#getFromColor--) | A helyettesítendő szín. |
| [getToColor()](#getToColor--) | A helyettesítő szín. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


A helyettesítendő szín. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


A helyettesítő szín. Csak olvasható [IColorFormat](../../com.aspose.slides/icolorformat).

**Returns:**
[IColorFormat](../../com.aspose.slides/icolorformat)