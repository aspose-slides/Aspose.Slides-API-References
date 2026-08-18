---
title: ColorReplace
second_title: Referência da API Aspose.Slides para Java
description: Representa um efeito de Substituição de Cor.
type: docs
url: /pt/com.aspose.slides/colorreplace/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IColorReplace](../../com.aspose.slides/icolorreplace), com.aspose.slides.IVisualEffect, java.lang.Cloneable
```
public final class ColorReplace extends ImageTransformOperation implements IColorReplace, IVisualEffect, Cloneable
```

Representa um efeito de Substituição de Cor. Todas as cores do efeito são alteradas para uma cor fixa. Os valores alfa não são afetados.
## Métodos

| Método | Descrição |
| --- | --- |
| [getColor()](#getColor--) | Retorna o formato de cor que substituirá a cor de cada pixel. |
| [getEffective()](#getEffective--) | Obtém os dados efetivos do efeito de Substituição de Cor com a herança aplicada. |
| [getVersion()](#getVersion--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se o [ColorReplace](../../com.aspose.slides/colorreplace) especificado é igual ao [ColorReplace](../../com.aspose.slides/colorreplace) atual. |
| [hashCode()](#hashCode--) | Serve como uma função hash para um tipo específico. |
### getColor() {#getColor--}
```
public final IColorFormat getColor()
```

Retorna o formato de cor que substituirá a cor de cada pixel. Somente leitura [IColorFormat](../../com.aspose.slides/icolorformat).

**Retorna:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### getEffective() {#getEffective--}
```
public final IColorReplaceEffectiveData getEffective()
```

Obtém os dados efetivos do efeito de Substituição de Cor com a herança aplicada.

**Retorna:**
[IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata) - A [IColorReplaceEffectiveData](../../com.aspose.slides/icolorreplaceeffectivedata).
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

Determina se o [ColorReplace](../../com.aspose.slides/colorreplace) especificado é igual ao [ColorReplace](../../com.aspose.slides/colorreplace) atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O [ColorReplace](../../com.aspose.slides/colorreplace) a ser comparado. |

**Retorna:**
boolean - true se os objetos são iguais; caso contrário, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Serve como uma função hash para um tipo específico.

**Retorna:**
int - Um código hash para o objeto atual.