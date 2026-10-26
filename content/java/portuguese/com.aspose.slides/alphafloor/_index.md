---
title: AlphaFloor
second_title: Referência da API Aspose.Slides para Java
description: Representa um efeito Alpha Floor.
type: docs
url: /pt/com.aspose.slides/alphafloor/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IAlphaFloor](../../com.aspose.slides/ialphafloor), com.aspose.slides.IVisualEffect
```
public final class AlphaFloor extends ImageTransformOperation implements IAlphaFloor, IVisualEffect
```

Representa um efeito Alpha Floor. Valores de Alpha (opacidade) menores que 100% são alterados para zero. Em outras palavras, tudo que é parcialmente transparente torna-se totalmente transparente.
## Métodos

| Método | Descrição |
| --- | --- |
| [getEffective()](#getEffective--) | Gets effective Alpha Floor effect data with the inheritance applied. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines whether the specified [AlphaFloor](../../com.aspose.slides/alphafloor) is equal to the current [AlphaFloor](../../com.aspose.slides/alphafloor). |
| [hashCode()](#hashCode--) | Serves as a hash function for a particular type. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Obtém os dados efetivos do efeito Alpha Floor com a herança aplicada.

**Retorna:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - A [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se o [AlphaFloor](../../com.aspose.slides/alphafloor) especificado é igual ao [AlphaFloor](../../com.aspose.slides/alphafloor) atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O [AlphaFloor](../../com.aspose.slides/alphafloor) a ser comparado. |

**Retorna:**
boolean - verdadeiro se os objetos são iguais; caso contrário, falso.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serve como função de hash para um tipo específico.

**Retorna:**
int - Um código de hash para o objeto atual.