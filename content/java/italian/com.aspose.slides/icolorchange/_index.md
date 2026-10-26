---
title: IColorChange
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un effetto di cambio colore.
type: docs
url: /it/com.aspose.slides/icolorchange/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Rappresenta un effetto di cambio colore. Le istanze di FromColor vengono sostituite con istanze di ToColor.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFromColor()](#getFromColor--) | Colore che sarà sostituito. |
| [getToColor()](#getToColor--) | Colore che sostituirà. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


Colore che sarà sostituito. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


Colore che sostituirà. Solo lettura [IColorFormat](../../com.aspose.slides/icolorformat).

**Restituisce:**
[IColorFormat](../../com.aspose.slides/icolorformat)