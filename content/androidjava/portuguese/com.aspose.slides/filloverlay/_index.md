---
title: FillOverlay
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um efeito de Sobreposição de Preenchimento.
type: docs
url: /pt/com.aspose.slides/filloverlay/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IFillOverlay](../../com.aspose.slides/ifilloverlay), com.aspose.slides.IVisualEffect
```
public final class FillOverlay extends ImageTransformOperation implements IFillOverlay, IVisualEffect
```

Representa um efeito de Sobreposição de Preenchimento. Uma sobreposição de preenchimento pode ser usada para especificar um preenchimento adicional para um objeto e mesclar os dois preenchimentos juntos.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFillFormat()](#getFillFormat--) | Formato de preenchimento. |
| [getBlend()](#getBlend--) | FillBlendMode. |
| [setBlend(int value)](#setBlend-int-) | FillBlendMode. |
| [getEffective()](#getEffective--) | Obtém os dados efetivos do efeito de Sobreposição de Preenchimento com a herança aplicada. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se o [FillOverlay](../../com.aspose.slides/filloverlay) especificado é igual ao [FillOverlay](../../com.aspose.slides/filloverlay) atual. |
| [hashCode()](#hashCode--) | Serve como uma função hash para um tipo específico. |

### getFillFormat() {#getFillFormat--}
```
public final IFillFormat getFillFormat()
```

Formato de preenchimento. Somente leitura [IFillFormat](../../com.aspose.slides/ifillformat).

**Retorna:**
[IFillFormat](../../com.aspose.slides/ifillformat)

### getBlend() {#getBlend--}
```
public final int getBlend()
```

FillBlendMode. Leitura/gravação [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Retorna:**
int

### setBlend(int value) {#setBlend-int-}
```
public final void setBlend(int value)
```

FillBlendMode. Leitura/gravação [FillBlendMode](../../com.aspose.slides/fillblendmode).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | int |  |

### getEffective() {#getEffective--}
```
public final IFillOverlayEffectiveData getEffective()
```

Obtém os dados efetivos do efeito de Sobreposição de Preenchimento com a herança aplicada.

**Retorna:**
[IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata) - Um [IFillOverlayEffectiveData](../../com.aspose.slides/ifilloverlayeffectivedata).

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versão. Somente leitura long.

**Retorna:**
long

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se o [FillOverlay](../../com.aspose.slides/filloverlay) especificado é igual ao [FillOverlay](../../com.aspose.slides/filloverlay) atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O [FillOverlay](../../com.aspose.slides/filloverlay) a comparar. |

**Retorna:**
boolean - verdadeiro se os objetos forem iguais; caso contrário, falso.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Serve como uma função hash para um tipo específico.

**Retorna:**
int - Um código hash para o objeto atual.