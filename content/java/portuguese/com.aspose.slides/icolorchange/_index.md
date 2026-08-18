---
title: IColorChange
second_title: Referência da API Aspose.Slides para Java
description: Representa um efeito de alteração de cor.
type: docs
url: /pt/com.aspose.slides/icolorchange/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IColorChange extends IImageTransformOperation, IAccessiblePVIObject<IColorChangeEffectiveData>
```

Representa um efeito de alteração de cor. Instâncias de FromColor são substituídas por instâncias de ToColor.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFromColor()](#getFromColor--) | Cor que será substituída. |
| [getToColor()](#getToColor--) | Cor que substituirá. |
### getFromColor() {#getFromColor--}
```
public abstract IColorFormat getFromColor()
```


Cor que será substituída. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public abstract IColorFormat getToColor()
```


Cor que substituirá. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)