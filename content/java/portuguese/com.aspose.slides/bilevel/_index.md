---
title: BiLevel
second_title: Referência da API Aspose.Slides para Java
description: Representa um efeito Bi-Level preto/branco.
type: docs
url: /pt/com.aspose.slides/bilevel/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IBiLevel](../../com.aspose.slides/ibilevel), com.aspose.slides.IVisualEffect
```
public final class BiLevel extends ImageTransformOperation implements IBiLevel, IVisualEffect
```

Representa um efeito Bi-Level (preto/branco). Cores de entrada cuja luminância é menor que o valor de limiar especificado são alteradas para preto. Cores de entrada cuja luminância é maior ou igual ao valor especificado são definidas como branco. Os valores de efeito alfa não são afetados por este efeito.
## Métodos

| Método | Descrição |
| --- | --- |
| [getEffective()](#getEffective--) | Obtém os dados efetivos do efeito Bi-Level com a herança aplicada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se o [BiLevel](../../com.aspose.slides/bilevel) especificado é igual ao [BiLevel](../../com.aspose.slides/bilevel) atual. |
| [hashCode()](#hashCode--) | Serve como função de hash para um tipo específico. |
### getEffective() {#getEffective--}
```
public final IBiLevelEffectiveData getEffective()
```


Obtém os dados efetivos do efeito Bi-Level com a herança aplicada.

**Retorna:**
[IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata) - Um [IBiLevelEffectiveData](../../com.aspose.slides/ibileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determina se o [BiLevel](../../com.aspose.slides/bilevel) especificado é igual ao [BiLevel](../../com.aspose.slides/bilevel) atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O [BiLevel](../../com.aspose.slides/bilevel) a ser comparado. |

**Retorna:**
boolean - true se os objetos forem iguais; caso contrário, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Serve como função de hash para um tipo específico.

**Retorna:**
int - Um código hash para o objeto atual.