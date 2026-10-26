---
title: AddClone()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.
type: docs
weight: 547
url: /pt/aspose.slides/shapecollection/addclone/
---
## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float, float, float) method

Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y, float width, float height) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A forma a ser clonada. |
| x | **float** | A coordenada x da moldura da nova forma\u2019s, em pontos. |
| y | **float** | A coordenada y da moldura da nova forma\u2019s, em pontos. |
| width | **float** | A largura da moldura da nova forma\u2019s, em pontos. |
| height | **float** | A altura da moldura da nova forma\u2019s, em pontos. |

### Valor de Retorno

O [IShape](../../ishape/) recém-criado.

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>, float, float) method

Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. A nova forma mantém a largura e a altura da *sourceShape* .

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape, float x, float y) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | A forma a ser clonada. |
| x | **float** | A coordenada x da moldura da nova forma\u2019s, em pontos. |
| y | **float** | A coordenada y da moldura da nova forma\u2019s, em pontos. |

### Valor de Retorno

O [IShape](../../ishape/) recém-criado.

## ShapeCollection::AddClone(System::SharedPtr\<IShape\>) method

Cria uma cópia da forma especificada e a adiciona ao final da coleção de formas. A forma clonada mantém a posição e o tamanho originais.

```cpp
System::SharedPtr<IShape> Aspose::Slides::ShapeCollection::AddClone(System::SharedPtr<IShape> sourceShape) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| sourceShape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | O [IShape](../../ishape/) a ser clonada. |

### Valor de Retorno

O [IShape](../../ishape/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IShape](../../ishape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)