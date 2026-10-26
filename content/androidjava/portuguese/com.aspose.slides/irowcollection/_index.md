---
title: IRowCollection
second_title: Referência da API Java do Aspose.Slides para Android
description: Representa a coleção de linhas de tabela.
type: docs
url: /pt/com.aspose.slides/irowcollection/
---
**Todas as Interfaces Implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IRowCollection extends IGenericCollection<IRow>
```

Representa a coleção de linhas de tabela.
## Métodos

| Method | Description |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Obtém o elemento no índice especificado. |
| [addClone(IRow templ, boolean withAttachedRows)](#addClone-com.aspose.slides.IRow-boolean-) | Cria uma cópia da linha modelo especificada e a insere na parte inferior de uma tabela. |
| [insertClone(int index, IRow templ, boolean withAttachedRows)](#insertClone-int-com.aspose.slides.IRow-boolean-) | Cria uma cópia da linha modelo especificada e a insere na posição especificada em uma tabela. |
| [removeAt(int firstRowIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Remove uma linha na posição especificada de uma tabela. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IRow get_Item(int index)
```

Obtém o elemento no índice especificado.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Retorno:**
[IRow](../../com.aspose.slides/irow)
### addClone(IRow templ, boolean withAttachedRows) {#addClone-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] addClone(IRow templ, boolean withAttachedRows)
```

Cria uma cópia da linha modelo especificada e a insere na parte inferior de uma tabela.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| templ | [IRow](../../com.aspose.slides/irow) | Linha usada como modelo. |
| withAttachedRows | boolean | True para copiar também todas as linhas anexadas à linha modelo. |

**Retorno:**
com.aspose.slides.IRow[] - Linhas adicionadas.
### insertClone(int index, IRow templ, boolean withAttachedRows) {#insertClone-int-com.aspose.slides.IRow-boolean-}
```
public abstract IRow[] insertClone(int index, IRow templ, boolean withAttachedRows)
```

Cria uma cópia da linha modelo especificada e a insere na posição especificada em uma tabela.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Índice de uma nova linha. |
| templ | [IRow](../../com.aspose.slides/irow) | Linha usada como modelo. |
| withAttachedRows | boolean | True para copiar também todas as linhas anexadas à linha modelo. |

**Retorno:**
com.aspose.slides.IRow[] - Linhas inseridas.
### removeAt(int firstRowIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstRowIndex, boolean withAttachedRows)
```

Remove uma linha na posição especificada de uma tabela.

**Parâmetros:**
| Parameter | Type | Description |
| --- | --- | --- |
| firstRowIndex | int | Índice de uma linha a ser excluída. |
| withAttachedRows | boolean | True para excluir também todas as linhas anexadas. |