---
title: AddClone()
second_title: Aspose.Slides para C++ Referência da API
description: Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.
type: docs
weight: 495
url: /pt/aspose.slides/ishapecollection/addclone/
---
## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) método


Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A forma a ser clonada. |
| x | **float** | A coordenada x da moldura da forma clonada, em pontos. |
| y | **float** | A coordenada y da moldura da forma clonada, em pontos. |
| width | **float** | A largura da moldura da forma clonada, em pontos. |
| height | **float** | A altura da moldura da forma clonada, em pontos. |

### Valor de Retorno

O [IShape](../../ishape/) recém-criado.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) método


Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. A nova forma mantém a largura e a altura da *sourceShape* .

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | O [IShape](../../ishape/) a ser clonado. |
| x | **float** | A coordenada x da moldura da forma clonada, em pontos. |
| y | **float** | A coordenada y da moldura da forma clonada, em pontos. |

### Valor de Retorno

O [IShape](../../ishape/) recém-criado.

## IShapeCollection::AddClone(System::SharedPtr\<IShape\>) método


Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. A forma clonada mantém a posição e o tamanho do original.

```cpp
virtual System::SharedPtr<IShape> Aspose::Slides::IShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | O [IShape](../../ishape/) a ser clonado. |

### Valor de Retorno

O [IShape](../../ishape/) recém-criado.

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShape](../../ishape/)
* Classe [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)