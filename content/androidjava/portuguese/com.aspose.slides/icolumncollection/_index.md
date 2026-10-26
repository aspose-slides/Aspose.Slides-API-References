---
title: IColumnCollection
second_title: Aspose.Slides para Android via Referência da API Java
description: Representa a coleção de colunas em uma tabela.
type: docs
url: /pt/com.aspose.slides/icolumncollection/
---
**Todas as interfaces implementadas:**
com.aspose.slides.IGenericCollection
```
public interface IColumnCollection extends IGenericCollection<IColumn>
```

Representa a coleção de colunas em uma tabela.
## Métodos

| Método | Descrição |
| --- | --- |
| [get_Item(int index)](#get-Item-int-) | Retorna a coluna no índice especificado. |
| [addClone(IColumn templ, boolean withAttachedColumns)](#addClone-com.aspose.slides.IColumn-boolean-) | Cria uma cópia da linha de modelo especificada e a insere na parte inferior de uma tabela. |
| [insertClone(int index, IColumn templ, boolean withAttachedColumns)](#insertClone-int-com.aspose.slides.IColumn-boolean-) | Cria uma cópia da coluna de modelo especificada e a insere na posição especificada em uma tabela. |
| [removeAt(int firstColumnIndex, boolean withAttachedRows)](#removeAt-int-boolean-) | Remove uma coluna na posição especificada de uma tabela. |
### get_Item(int index) {#get-Item-int-}
```
public abstract IColumn get_Item(int index)
```


Retorna a coluna no índice especificado. Somente leitura [IColumn](../../com.aspose.slides/icolumn).

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int |  |

**Retorna:**
[IColumn](../../com.aspose.slides/icolumn)
### addClone(IColumn templ, boolean withAttachedColumns) {#addClone-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] addClone(IColumn templ, boolean withAttachedColumns)
```


Cria uma cópia da linha de modelo especificada e a insere na parte inferior de uma tabela.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Coluna que é usada como modelo. |
| withAttachedColumns | boolean | True para copiar também todas as colunas anexadas à linha de modelo. |

**Retorna:**
com.aspose.slides.IColumn[] - Colunas adicionadas.
### insertClone(int index, IColumn templ, boolean withAttachedColumns) {#insertClone-int-com.aspose.slides.IColumn-boolean-}
```
public abstract IColumn[] insertClone(int index, IColumn templ, boolean withAttachedColumns)
```


Cria uma cópia da coluna de modelo especificada e a insere na posição especificada em uma tabela.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | int | Índice da nova coluna. |
| templ | [IColumn](../../com.aspose.slides/icolumn) | Coluna que é usada como modelo. |
| withAttachedColumns | boolean | True para copiar também todas as colunas anexadas à coluna de modelo. |

**Retorna:**
com.aspose.slides.IColumn[] - Colunas inseridas.
### removeAt(int firstColumnIndex, boolean withAttachedRows) {#removeAt-int-boolean-}
```
public abstract void removeAt(int firstColumnIndex, boolean withAttachedRows)
```


Remove uma coluna na posição especificada de uma tabela.

**Parâmetros:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| firstColumnIndex | int | Índice da coluna a excluir. |
| withAttachedRows | boolean | True para excluir também todas as colunas anexadas. |