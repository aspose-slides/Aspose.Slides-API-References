---
title: InsertAutoShape()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova forma automática e a insere na coleção de formas no índice especificado, aplicando a formatação padrão do modelo.
type: docs
weight: 339
url: /pt/aspose.slides/ishapecollection/insertautoshape/
---
## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float) method

Cria uma nova forma automática e a insere na coleção de formas no índice especificado, aplicando a formatação padrão do modelo.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir a nova forma automática. |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma automática a ser inserida. |
| x | **float** | A coordenada x da moldura da forma, em pontos. |
| y | **float** | A coordenada y da moldura da forma, em pontos. |
| width | **float** | A largura da moldura da forma, em pontos. |
| height | **float** | A altura da moldura da forma, em pontos. |

### Valor de Retorno

O [IAutoShape](../../iautoshape/) recém-criado.

## IShapeCollection::InsertAutoShape(int32_t, ShapeType, float, float, float, float, bool) method

Cria uma nova forma automática e a insere na coleção de formas no índice especificado, opcionalmente inicializando-a com a estilização padrão do modelo.

```cpp
virtual System::SharedPtr<IAutoShape> Aspose::Slides::IShapeCollection::InsertAutoShape(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir a forma automática. |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma automática a ser inserida. |
| x | **float** | A coordenada x da moldura da forma, em pontos. |
| y | **float** | A coordenada y da moldura da forma, em pontos. |
| width | **float** | A largura da moldura da forma, em pontos. |
| height | **float** | A altura da moldura da forma, em pontos. |
| createFromTemplate | **bool** | True para aplicar a estilização padrão do modelo (incluindo um nome não vazio, estilo simples e texto centralizado); false para criar a forma com todas as propriedades definidas para seus valores padrão. |

### Valor de Retorno

O [IAutoShape](../../iautoshape/) recém-criado.

## Veja Também

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IAutoShape](../../iautoshape/)
* Classe [IShapeCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)