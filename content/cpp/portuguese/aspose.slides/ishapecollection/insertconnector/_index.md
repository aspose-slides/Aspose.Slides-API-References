---
title: InsertConnector()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova forma de conector e a insere na coleção de formas no índice especificado, aplicando o estilo de modelo padrão.
type: docs
weight: 391
url: /pt/aspose.slides/ishapecollection/insertconnector/
---
## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float) método


Cria uma nova forma de conector e a insere na coleção de formas no índice especificado, aplicando o estilo de modelo padrão.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir a forma de conector. |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma de conector a ser inserida. |
| x | **float** | A coordenada x da moldura do conector, em pontos. |
| y | **float** | A coordenada y da moldura do conector, em pontos. |
| width | **float** | A largura da moldura do conector, em pontos. |
| height | **float** | A altura da moldura do conector, em pontos. |

### Valor de Retorno

O [IConnector](../../iconnector/) recém-criado.

## IShapeCollection::InsertConnector(int32_t, ShapeType, float, float, float, float, bool) método


Cria uma nova forma de conector e a insere na coleção de formas no índice especificado, aplicando opcionalmente o estilo de modelo padrão.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::InsertConnector(int32_t index, ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Argumentos

| Parameter | Type | Description |
| --- | --- | --- |
| index | **int32_t** | O índice baseado em zero no qual inserir a forma de conector. |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma de conector a ser inserida. |
| x | **float** | A coordenada x da moldura do conector, em pontos. |
| y | **float** | A coordenada y da moldura do conector, em pontos. |
| width | **float** | A largura da moldura do conector, em pontos. |
| height | **float** | A altura da moldura do conector, em pontos. |
| createFromTemplate | **bool** | True para aplicar o estilo de modelo padrão (nome não vazio, estilo simples); false para criar o conector com valores de propriedades padrão. |

### Valor de Retorno

O [IConnector](../../iconnector/) recém-criado.

## Veja Também

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IConnector](../../iconnector/)
* Classe [IShapeCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)