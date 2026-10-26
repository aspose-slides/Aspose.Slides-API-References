---
title: AddAutoShape()
second_title: Aspose.Slides para Referência da API C++
description: Cria uma nova forma automática com formatação padrão e a adiciona ao final da coleção de formas.
type: docs
weight: 313
url: /pt/aspose.slides/ishapecollection/addautoshape/
---
## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float) method


Cria uma nova forma automática com formatação padrão e a adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma automática a ser adicionada. |
| x | **float** | A coordenada x da moldura da forma, em pontos. |
| y | **float** | A coordenada y da moldura da forma, em pontos. |
| width | **float** | A largura da moldura da forma, em pontos. |
| height | **float** | A altura da moldura da forma, em pontos. |

### Valor de Retorno

O [IAutoShape](../../iautoshape/) recém-criado.

## IShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) method


Cria uma nova forma automática e a adiciona ao final da coleção de formas, opcionalmente inicializando-a com a formatação padrão de modelo.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma automática a ser adicionada. |
| x | **float** | A coordenada x da moldura da forma, em pontos. |
| y | **float** | A coordenada y da moldura da forma, em pontos. |
| width | **float** | A largura da moldura da forma, em pontos. |
| height | **float** | A altura da moldura da forma, em pontos. |
| createFromTemplate | **bool** | True para aplicar o estilo de modelo padrão (estilo simples, texto centralizado e nome não vazio) à nova forma; false para criar a forma com todas as propriedades definidas para seus valores padrão. |

### Valor de Retorno

O [IAutoShape](../../iautoshape/) recém-criado.

## Veja Também

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)