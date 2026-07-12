---
title: IGlow
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um efeito de brilho no qual um contorno borrado de cor é adicionado fora das bordas do objeto.
type: docs
url: /pt/com.aspose.slides/iglow/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IGlow extends IImageTransformOperation, IAccessiblePVIObject<IGlowEffectiveData>
```

Representa um efeito de brilho, no qual um contorno borrado de cor é adicionado fora das bordas do objeto.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRadius()](#getRadius--) | Raio. |
| [setRadius(double value)](#setRadius-double-) | Raio. |
| [getColor()](#getColor--) | Formato de cor. |
### getRadius() {#getRadius--}
```
public abstract double getRadius()
```


Raio. Leitura/gravação double.

**Retorna:**
double
### setRadius(double value) {#setRadius-double-}
```
public abstract void setRadius(double value)
```


Raio. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getColor() {#getColor--}
```
public abstract IColorFormat getColor()
```


Formato de cor. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)