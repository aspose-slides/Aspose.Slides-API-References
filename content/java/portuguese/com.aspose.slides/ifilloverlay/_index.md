---
title: IFillOverlay
second_title: Referência da API Aspose.Slides para Java
description: Representa um efeito de sobreposição de preenchimento.
type: docs
url: /pt/com.aspose.slides/ifilloverlay/
---
**Todas as Interfaces Implementadas:**
[com.aspose.slides.IImageTransformOperation](../../com.aspose.slides/iimagetransformoperation), com.aspose.slides.IAccessiblePVIObject
```
public interface IFillOverlay extends IImageTransformOperation, IAccessiblePVIObject<IFillOverlayEffectiveData>
```

Representa um efeito de sobreposição de preenchimento. Uma sobreposição de preenchimento pode ser usada para especificar um preenchimento adicional para um objeto e mesclar os dois preenchimentos.

## Métodos

| Método | Descrição |
| --- | --- |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getFillFormat()](#getFillFormat--) | Formato de preenchimento. |

### getBlend() {#getBlend--}
```
public abstract int getBlend()
```

FillBlendMode. Leitura/gravação [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Retorna:**
int
### setBlend(int value) {#setBlend-int-}
```
public abstract void setBlend(int value)
```

FillBlendMode. Leitura/gravação [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getFillFormat() {#getFillFormat--}
```
public abstract IFillFormat getFillFormat()
```

Formato de preenchimento. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)