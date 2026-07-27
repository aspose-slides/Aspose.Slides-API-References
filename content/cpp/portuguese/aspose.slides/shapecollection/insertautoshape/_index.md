---
title: InsertAutoShape()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova forma automática e a insere na coleção de formas no índice especificado, aplicando a formatação padrão do modelo.
type: docs
weight: 378
url: /pt/aspose.slides/shapecollection/insertautoshape/
---
## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) método


Cria uma nova forma automática e a insere na coleção de formas no índice especificado, aplicando formatação de modelo padrão.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height) override
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir a nova forma automática. |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma automática a ser inserida. |
| x | **float** | A coordenada x da moldura da forma, em pontos. |
| y | **float** | A coordenada y da moldura da forma, em pontos. |
| width | **float** | A largura da moldura da forma, em pontos. |
| height | **float** | A altura da moldura da forma, em pontos. |

### Return Value

O [IAutoShape](../../iautoshape/) recém-criado.

## ShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) método


Cria uma nova forma automática e a insere na coleção de formas no índice especificado, opcionalmente inicializando-a com estilo de modelo padrão.

```cpp
System::SharedPtr<IAutoShape> Aspose::Slides::ShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Arguments

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir a forma automática. |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma automática a ser inserida. |
| x | **float** | A coordenada x da moldura da forma, em pontos. |
| y | **float** | A coordenada y da moldura da forma, em pontos. |
| width | **float** | A largura da moldura da forma, em pontos. |
| height | **float** | A altura da moldura da forma, em pontos. |
| createFromTemplate | **bool** | True para aplicar o estilo de modelo padrão (incluindo um nome não vazio, estilo simples e texto centralizado); false para criar a forma com todas as propriedades definidas para seus valores padrão. |

### Return Value

O [IAutoShape](../../iautoshape/) recém-criado.

## See Also

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IAutoShape](../../iautoshape/)
* Class [ShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)