---
title: ColorChange
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa um efeito de alteração de cor.
type: docs
url: /pt/com.aspose.slides/colorchange/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IColorChange](../../com.aspose.slides/icolorchange), com.aspose.slides.IVisualEffect
```
public final class ColorChange extends ImageTransformOperation implements IColorChange, IVisualEffect
```

Representa um efeito de alteração de cor. Instâncias de FromColor são substituídas por instâncias de ToColor.
## Métodos

| Método | Descrição |
| --- | --- |
| [getFromColor()](#getFromColor--) | Cor que será substituída. |
| [getToColor()](#getToColor--) | Cor que substituirá. |
| [getEffective()](#getEffective--) | Obtém dados efetivos do efeito de Mudança de Cor com a herança aplicada. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se o [ColorChange](../../com.aspose.slides/colorchange) especificado é igual ao [ColorChange](../../com.aspose.slides/colorchange) atual. |
| [hashCode()](#hashCode--) | Serve como função de hash para um tipo específico. |
### getFromColor() {#getFromColor--}
```
public final IColorFormat getFromColor()
```

Cor que será substituída. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getToColor() {#getToColor--}
```
public final IColorFormat getToColor()
```

Cor que substituirá. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorChangeEffectiveData getEffective()
```

Obtém dados efetivos do efeito de Mudança de Cor com a herança aplicada.

**Retorna:**
[IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata) - Um [IColorChangeEffectiveData](../../com.aspose.slides/icolorchangeeffectivedata).
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

Determina se o [ColorChange](../../com.aspose.slides/colorchange) especificado é igual ao [ColorChange](../../com.aspose.slides/colorchange) atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O [ColorChange](../../com.aspose.slides/colorchange) a ser comparado. |

**Retorna:**
boolean - true se os objetos forem iguais; caso contrário, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Serve como função de hash para um tipo específico.

**Retorna:**
int - Um código hash para o objeto atual.