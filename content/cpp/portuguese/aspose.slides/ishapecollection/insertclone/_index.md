---
title: InsertClone()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado.
type: docs
weight: 508
url: /pt/aspose.slides/ishapecollection/insertclone/
---
## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) método

Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero onde inserir a forma clonada. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | O [IShape](../../ishape/) a ser clonado. |
| x | **float** | A coordenada x da moldura da forma clonada, em pontos. |
| y | **float** | A coordenada y da moldura da forma clonada, em pontos. |
| width | **float** | A largura da moldura da forma clonada, em pontos. |
| height | **float** | A altura da moldura da forma clonada, em pontos. |

### Valor de Retorno

O recém-criado [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) método

Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. A nova forma mantém a largura e a altura da *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero onde inserir a forma clonada. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | O [IShape](../../ishape/) a ser clonado. |
| x | **float** | A coordenada x da moldura da forma clonada, em pontos. |
| y | **float** | A coordenada y da moldura da forma clonada, em pontos. |

### Valor de Retorno

O recém-criado [IShape](../../ishape/).

## IShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) método

Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. A forma clonada mantém a posição e o tamanho da original.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero onde inserir a forma clonada. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | O [IShape](../../ishape/) a ser clonado. |

### Valor de Retorno

O recém-criado [IShape](../../ishape/).

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)