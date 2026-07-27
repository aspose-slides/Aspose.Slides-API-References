---
title: AddConnector()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova forma de conector com estilo de modelo padrão e a adiciona ao final da coleção de formas.
type: docs
weight: 378
url: /pt/aspose.slides/ishapecollection/addconnector/
---
## IShapeCollection::AddConnector(ShapeType, float, float, float, float) método


Cria uma nova forma de conector com estilo de modelo padrão e a adiciona ao final da coleção de formas.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma de conector a ser adicionada. |
| x | **float** | A coordenada x da moldura do conector, em pontos. |
| y | **float** | A coordenada y da moldura do conector, em pontos. |
| width | **float** | A largura da moldura do conector, em pontos. |
| height | **float** | A altura da moldura do conector, em pontos. |

### Valor de Retorno

O [IConnector](../../iconnector/) recém-criado.

## IShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) método


Cria uma nova forma de conector e a adiciona ao final da coleção de formas, opcionalmente aplicando o estilo de modelo padrão.

```cpp
virtual System::SharedPtr<IConnector> Aspose::Slides::IShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma de conector a ser criada. |
| x | **float** | A coordenada x da moldura do conector, em pontos. |
| y | **float** | A coordenada y da moldura do conector, em pontos. |
| width | **float** | A largura da moldura do conector, em pontos. |
| height | **float** | A altura da moldura do conector, em pontos. |
| createFromTemplate | **bool** | True para aplicar o estilo de modelo padrão (nome não vazio, estilo simples); false para criar o conector com valores de propriedade padrão. |

### Valor de Retorno

O [IConnector](../../iconnector/) recém-criado.

## Veja Também

* Enum [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IConnector](../../iconnector/)
* Classe [IShapeCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)