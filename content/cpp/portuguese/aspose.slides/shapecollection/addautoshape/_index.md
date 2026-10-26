---
title: AddAutoShape()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova forma automática com formatação padrão e a adiciona ao final da coleção de formas.
type: docs
weight: 352
url: /pt/aspose.slides/shapecollection/addautoshape/
---
## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float) método


Cria uma nova forma automática com formatação padrão e a adiciona ao final da coleção de formas.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma automática a ser adicionada. |
| x | **float** | A coordenada x da moldura da forma, em pontos. |
| y | **float** | A coordenada y da moldura da forma, em pontos. |
| width | **float** | A largura da moldura da forma, em pontos. |
| height | **float** | A altura da moldura da forma, em pontos. |

### Valor de Retorno

A [IAutoShape](../../iautoshape/) recém-criada.

## ShapeCollection::AddAutoShape(ShapeType, float, float, float, float, bool) método


Cria uma nova forma automática e a adiciona ao final da coleção de formas, opcionalmente inicializando-a com a formatação de modelo padrão.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::AddAutoShape(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma automática a ser adicionada. |
| x | **float** | A coordenada x da moldura da forma, em pontos. |
| y | **float** | A coordenada y da moldura da forma, em pontos. |
| width | **float** | A largura da moldura da forma, em pontos. |
| height | **float** | A altura da moldura da forma, em pontos. |
| createFromTemplate | **bool** | True para aplicar o estilo de modelo padrão (estilo simples, texto centralizado e nome não vazio) à nova forma; false para criar a forma com todas as propriedades definidas para seus valores padrão. |

### Valor de Retorno

A [IAutoShape](../../iautoshape/) recém-criada.

## Veja Também

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)