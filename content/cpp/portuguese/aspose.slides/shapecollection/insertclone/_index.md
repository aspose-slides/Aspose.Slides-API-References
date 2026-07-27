---
title: InsertClone()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado.
type: docs
weight: 560
url: /pt/aspose.slides/shapecollection/insertclone/
---
## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float, float, float) método


Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero onde a forma clonada será inserida. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | O [IShape](../../ishape/) a ser clonado. |
| x | **float** | A coordenada x da moldura da forma clonada, em pontos. |
| y | **float** | A coordenada y da moldura da forma clonada, em pontos. |
| width | **float** | A largura da moldura da forma clonada, em pontos. |
| height | **float** | A altura da moldura da forma clonada, em pontos. |

### Valor de Retorno

O [IShape](../../ishape/) recém-criado.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>, float, float) método


Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. A nova forma mantém a largura e a altura da *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape, float x, float y) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero onde a forma clonada será inserida. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | O [IShape](../../ishape/) a ser clonado. |
| x | **float** | A coordenada x da moldura da forma clonada, em pontos. |
| y | **float** | A coordenada y da moldura da forma clonada, em pontos. |

### Valor de Retorno

O [IShape](../../ishape/) recém-criado.

## ShapeCollection::InsertClone(int32_t, System::SharedPtr\<IShape\>) método


Cria uma cópia da forma especificada e a insere na coleção de formas no índice especificado. A forma clonada mantém a posição e o tamanho originais.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::InsertClone(int32_t index, System::SharedPtr<IShape> sourceShape) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero onde a forma clonada será inserida. |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | O [IShape](../../ishape/) a ser clonado. |

### Valor de Retorno

O [IShape](../../ishape/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)