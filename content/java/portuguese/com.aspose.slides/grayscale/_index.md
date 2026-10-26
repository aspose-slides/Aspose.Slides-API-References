---
title: GrayScale
second_title: Referência da API Aspose.Slides para Java
description: Representa um efeito de Escala de Cinza.
type: docs
url: /pt/com.aspose.slides/grayscale/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IGrayScale](../../com.aspose.slides/igrayscale), com.aspose.slides.IVisualEffect
```
public final class GrayScale extends ImageTransformOperation implements IGrayScale, IVisualEffect
```

Representa um efeito de Escala de Cinza. Converte todos os valores de cor do efeito para um tom de cinza, correspondente à sua luminância. Os valores de alfa (opacidade) do efeito não são alterados.

## Métodos

| Método | Descrição |
| --- | --- |
| [getEffective()](#getEffective--) | Obtém os dados efetivos do efeito de Escala de Cinza com a herança aplicada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se o [GrayScale](../../com.aspose.slides/grayscale) especificado é igual ao [GrayScale](../../com.aspose.slides/grayscale) atual. |
| [hashCode()](#hashCode--) | Serve como uma função hash para um tipo específico. |

### getEffective() {#getEffective--}
```
public final IGrayScaleEffectiveData getEffective()
```

Obtém os dados efetivos do efeito de Escala de Cinza com a herança aplicada.

**Retorna:**
[IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata) - Um [IGrayScaleEffectiveData](../../com.aspose.slides/igrayscaleeffectivedata).

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se o [GrayScale](../../com.aspose.slides/grayscale) especificado é igual ao [GrayScale](../../com.aspose.slides/grayscale) atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O [GrayScale](../../com.aspose.slides/grayscale) a ser comparado. |

**Retorna:**
boolean - true se os objetos são iguais; caso contrário, false.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Serve como uma função hash para um tipo específico.

**Retorna:**
int - Um código hash para o objeto atual.