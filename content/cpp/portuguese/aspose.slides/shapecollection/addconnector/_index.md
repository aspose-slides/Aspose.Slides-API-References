---
title: AddConnector()
second_title: Aspose.Slides para C++ Referência da API
description: Cria uma nova forma de conector com estilo de modelo padrão e a adiciona ao final da coleção de formas.
type: docs
weight: 417
url: /pt/aspose.slides/shapecollection/addconnector/
---
## ShapeCollection::AddConnector(ShapeType, float, float, float, float) método


Cria uma nova forma de conector com estilo de modelo padrão e a adiciona ao final da coleção de formas.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma de conector a ser adicionada. |
| x | **float** | A coordenada x da moldura do conector\u2019s, em pontos. |
| y | **float** | A coordenada y da moldura do conector\u2019s, em pontos. |
| width | **float** | A largura da moldura do conector\u2019s, em pontos. |
| height | **float** | A altura da moldura do conector\u2019s, em pontos. |

### Valor de Retorno

O [IConnector](../../iconnector/) recém-criado.

## Observações



O exemplo a seguir mostra como adicionar um conector (um conector curvo) entre duas formas (uma elipse e um retângulo) no PowerPoint [Presentation](../../presentation/). 
```cpp
// Instancia uma classe de apresentação que representa um arquivo PPTX
auto input = System::MakeObject<Presentation>();

// Acessa a coleção de formas de um slide específico
auto shapes = input->get_Slides()->idx_get(0)->get_Shapes();
// Adiciona uma forma automática de elipse
System::SharedPtr<IAutoShape> ellipse = shapes->AddAutoShape(ShapeType::Ellipse, 0.0f, 100.0f, 100.0f, 100.0f);
// Adiciona uma forma automática de retângulo
System::SharedPtr<IAutoShape> rectangle = shapes->AddAutoShape(ShapeType::Rectangle, 100.0f, 300.0f, 100.0f, 100.0f);

// Adiciona uma forma de conector à coleção de formas do slide
System::SharedPtr<IConnector> connector = shapes->AddConnector(ShapeType::BentConnector2, 0.0f, 0.0f, 10.0f, 10.0f);
// Conecta as formas utilizando o conector
connector->set_StartShapeConnectedTo(ellipse);
connector->set_EndShapeConnectedTo(rectangle);
// Chama reroute que define o caminho mais curto automático entre as formas
connector->Reroute();

// Salva a apresentação
input->Save(u"Shapes-connector.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddConnector(ShapeType, float, float, float, float, bool) método


Cria uma nova forma de conector e a adiciona ao final da coleção de formas, opcionalmente aplicando o estilo de modelo padrão.

```cpp
System::SharedPtr<IConnector> Aspose::Slides::ShapeCollection::AddConnector(ShapeType shapeType, float x, float y, float width, float height, bool createFromTemplate) override
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| shapeType | [ShapeType](../../shapetype/) | O [ShapeType](../../shapetype/) da forma de conector a ser criada. |
| x | **float** | A coordenada x da moldura do conector\u2019s, em pontos. |
| y | **float** | A coordenada y da moldura do conector\u2019s, em pontos. |
| width | **float** | A largura da moldura do conector\u2019s, em pontos. |
| height | **float** | A altura da moldura do conector\u2019s, em pontos. |
| createFromTemplate | **bool** | True para aplicar o estilo de modelo padrão (nome não vazio, estilo simples); false para criar o conector com valores de propriedades padrão. |

### Valor de Retorno

O [IConnector](../../iconnector/) recém-criado.

## Veja Também

* Enumeração [ShapeType](../../shapetype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IConnector](../../iconnector/)
* Classe [ShapeCollection](../)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)