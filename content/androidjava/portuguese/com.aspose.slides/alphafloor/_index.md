---
title: AlphaFloor
second_title: Aspose.Slides para Android via Referência da API Java
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

Representa um efeito Alpha Floor. Valores de Alpha (opacidade) menores que 100 % são alterados para zero. Em outras palavras, qualquer coisa parcialmente transparente torna-se totalmente transparente.
## Métodos

| Método | Descrição |
| --- | --- |
| [getEffective()](#getEffective--) | Obtém os dados efetivos do efeito Alpha Floor com a herança aplicada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se o [AlphaFloor](../../com.aspose.slides/alphafloor) especificado é igual ao [AlphaFloor](../../com.aspose.slides/alphafloor) atual. |
| [hashCode()](#hashCode--) | Atua como função hash para um tipo específico. |
### getEffective() {#getEffective--}
```
public final IAlphaFloorEffectiveData getEffective()
```


Obtém os dados efetivos do efeito Alpha Floor com a herança aplicada.

**Retorna:**
[IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata) - Um [IAlphaFloorEffectiveData](../../com.aspose.slides/ialphaflooreffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se o [AlphaFloor](../../com.aspose.slides/alphafloor) especificado é igual ao [AlphaFloor](../../com.aspose.slides/alphafloor) atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O [AlphaFloor](../../com.aspose.slides/alphafloor) para comparar. |

**Retorna:**
boolean - true se os objetos são iguais; caso contrário, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Atua como função hash para um tipo específico.

**Retorna:**
int - Um código hash para o objeto atual.