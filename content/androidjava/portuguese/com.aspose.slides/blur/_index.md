---
title: Blur
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa um efeito Blur que é aplicado a toda a forma, incluindo seu preenchimento.
type: docs
url: /pt/com.aspose.slides/blur/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBlur](../../com.aspose.slides/iblur), com.aspose.slides.IVisualEffect
```
public final class Blur extends ImageTransformOperation implements IBlur, IVisualEffect
```

Representa um efeito Blur que é aplicado a toda a forma, incluindo seu preenchimento. Todos os canais de cor, incluindo alfa, são afetados.
## Métodos

| Método | Descrição |
| --- | --- |
| [getRadius()](#getRadius--) | Retorna ou define o raio do desfoque. |
| [setRadius(double value)](#setRadius-double-) | Retorna ou define o raio do desfoque. |
| [getGrow()](#getGrow--) | Determina se os limites do objeto devem ser ampliados como resultado do desfoque. |
| [setGrow(boolean value)](#setGrow-boolean-) | Determina se os limites do objeto devem ser ampliados como resultado do desfoque. |
| [getEffective()](#getEffective--) | Obtém os dados efetivos do efeito Blur com a herança aplicada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se o [Blur](../../com.aspose.slides/blur) especificado é igual ao [Blur](../../com.aspose.slides/blur) atual. |
| [hashCode()](#hashCode--) | Atua como uma função hash para um tipo específico. |
### getRadius() {#getRadius--}
```
public final double getRadius()
```


Retorna ou define o raio do desfoque. Leitura/gravação double.

**Retorna:**
double
### setRadius(double value) {#setRadius-double-}
```
public final void setRadius(double value)
```


Retorna ou define o raio do desfoque. Leitura/gravação double.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | double |  |

### getGrow() {#getGrow--}
```
public final boolean getGrow()
```


Determina se os limites do objeto devem ser ampliados como resultado do desfoque. true indica que os limites são ampliados enquanto false indica que não são. Leitura/gravação boolean.

**Retorna:**
boolean
### setGrow(boolean value) {#setGrow-boolean-}
```
public final void setGrow(boolean value)
```


Determina se os limites do objeto devem ser ampliados como resultado do desfoque. true indica que os limites são ampliados enquanto false indica que não são. Leitura/gravação boolean.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | boolean |  |

### getEffective() {#getEffective--}
```
public final IBlurEffectiveData getEffective()
```


Obtém os dados efetivos do efeito Blur com a herança aplicada.

**Retorna:**
[IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata) - Um [IBlurEffectiveData](../../com.aspose.slides/iblureffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se o [Blur](../../com.aspose.slides/blur) especificado é igual ao [Blur](../../com.aspose.slides/blur) atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O [Blur](../../com.aspose.slides/blur) a ser comparado. |

**Retorna:**
boolean - true se os objetos são iguais; caso contrário, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Atua como uma função hash para um tipo específico.

**Retorna:**
int - Um código hash para o objeto atual.