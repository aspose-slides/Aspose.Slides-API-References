---
title: AddGroupShape()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova forma de grupo vazia e a adiciona ao final da coleção de formas. A moldura do grupo\\u2019s será ajustada automaticamente para acomodar quaisquer formas adicionadas a ela.
type: docs
weight: 391
url: /pt/aspose.slides/shapecollection/addgroupshape/
---
## ShapeCollection::AddGroupShape() método

Cria uma nova forma de grupo vazia e a adiciona ao final da coleção de formas. A moldura do grupo\\u2019s será ajustada automaticamente para acomodar quaisquer formas adicionadas a ela.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape() override
```

### Valor de Retorno

A [IGroupShape](../../igroupshape/) recém-criada.

## Observações

O exemplo a seguir mostra como adicionar uma forma de grupo a um slide do PowerPoint [Presentation](../../presentation/). 
```cpp
// Instanciar a classe Presentation
auto pres = System::MakeObject<Presentation>();

// Obter o primeiro slide
auto slide = pres->get_Slides()->idx_get(0);
// Acessando a coleção de formas dos slides
auto slideShapes = slide->get_Shapes();
// Adicionando uma forma de grupo ao slide
System::SharedPtr<IGroupShape> groupShape = slideShapes->AddGroupShape();

// Adicionando formas dentro da forma de grupo adicionada
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 100.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 300.0f, 300.0f, 100.0f, 100.0f);
groupShape->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 500.0f, 300.0f, 100.0f, 100.0f);
// Adicionando a moldura da forma de grupo
groupShape->set_Frame(System::MakeObject<ShapeFrame>(100.0f, 300.0f, 500.0f, 40.0f, NullableBool::False, NullableBool::False, 0.0f));

// Gravar o arquivo PPTX no disco
pres->Save(u"GroupShape_out.pptx", SaveFormat::Pptx);
```

## ShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) método

Cria uma nova forma de grupo, converte a imagem SVG especificada em formas individuais e adiciona o grupo resultante ao final da coleção de formas.

```cpp
System::SharedPtr<IGroupShape> Aspose::Slides::ShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height) override
```

### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | O [ISvgImage](../../isvgimage/) contendo conteúdo vetorial a ser convertido em formas. |
| x | **float** | A coordenada x da moldura do grupo\\u2019s, em points. |
| y | **float** | A coordenada y da moldura do grupo\\u2019s, em points. |
| width | **float** | A largura da moldura do grupo\\u2019s, em points. |
| height | **float** | A altura da moldura do grupo\\u2019s, em points. |

### Valor de Retorno

O [IGroupShape](../../igroupshape/) recém-criado.

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IGroupShape](../../igroupshape/)
* Classe [ShapeCollection](../)
* Classe [ISvgImage](../../isvgimage/)
* Espaço de nomes [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)