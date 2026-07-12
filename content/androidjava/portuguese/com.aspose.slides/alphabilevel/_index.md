---
title: AlphaBiLevel
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa um efeito Alpha Bi-Level.
type: docs
url: /pt/com.aspose.slides/alphabilevel/
---
**Herança:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject), [com.aspose.slides.ImageTransformOperation](../../com.aspose.slides/imagetransformoperation)

**Todas as Interfaces Implementadas:**
[com.aspose.slides.IAlphaBiLevel](../../com.aspose.slides/ialphabilevel), com.aspose.slides.IVisualEffect
```
public final class AlphaBiLevel extends ImageTransformOperation implements IAlphaBiLevel, IVisualEffect
```

Representa um efeito Alpha Bi-Level. Valores de Alpha (Opacidade) menores que o limiar são alterados para 0 (totalmente transparente) e valores de alpha maiores ou iguais ao limiar são alterados para 100% (totalmente opaco).
## Métodos

| Método | Descrição |
| --- | --- |
| [getThreshold()](#getThreshold--) | Retorna o limiar do efeito. |
| [setThreshold(float value)](#setThreshold-float-) | Retorna o limiar do efeito. |
| [getEffective()](#getEffective--) | Obtém os dados efetivos do efeito Alpha Bi-Level com a herança aplicada. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determina se o [AlphaBiLevel](../../com.aspose.slides/alphabilevel) especificado é igual ao [AlphaBiLevel](../../com.aspose.slides/alphabilevel) atual. |
| [hashCode()](#hashCode--) | Serve como função hash para um tipo específico. |
### getThreshold() {#getThreshold--}
```
public final float getThreshold()
```

Retorna o limiar do efeito. Leitura/escrita float.

**Retorna:**
float
### setThreshold(float value) {#setThreshold-float-}
```
public final void setThreshold(float value)
```

Retorna o limiar do efeito. Leitura/escrita float.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| value | float |  |

### getEffective() {#getEffective--}
```
public final IAlphaBiLevelEffectiveData getEffective()
```

Obtém os dados efetivos do efeito Alpha Bi-Level com a herança aplicada.

**Retorna:**
[IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata) - Um [IAlphaBiLevelEffectiveData](../../com.aspose.slides/ialphabileveleffectivedata).
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Determina se o [AlphaBiLevel](../../com.aspose.slides/alphabilevel) especificado é igual ao [AlphaBiLevel](../../com.aspose.slides/alphabilevel) atual.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| obj | java.lang.Object | O [AlphaBiLevel](../../com.aspose.slides/alphabilevel) a comparar. |

**Retorna:**
boolean - true se os objetos forem iguais; caso contrário, false.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Serve como função hash para um tipo específico.

**Retorna:**
int - Um código hash para o objeto atual.