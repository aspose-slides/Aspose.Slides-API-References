---
title: AddGroupShape()
second_title: Referência da API Aspose.Slides para C++
description: Cria uma nova forma de grupo vazia e a adiciona ao final da coleção de formas. A moldura do grupo será ajustada automaticamente para acomodar quaisquer formas adicionadas a ela.
type: docs
weight: 352
url: /pt/aspose.slides/ishapecollection/addgroupshape/
---
## IShapeCollection::AddGroupShape() método


Cria uma nova forma de grupo vazia e a adiciona ao final da coleção de formas. A moldura do grupo\\u2019s será ajustada automaticamente para acomodar quaisquer formas adicionadas a ela.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape()=0
```


### Valor de Retorno

O [IGroupShape](../../igroupshape/) recém-criado.

## IShapeCollection::AddGroupShape(System::SharedPtr\<ISvgImage\>, float, float, float, float) método


Cria uma nova forma de grupo, converte a imagem SVG especificada em formas individuais e adiciona o grupo resultante ao final da coleção de formas.

```cpp
virtual System::SharedPtr<IGroupShape> Aspose::Slides::IShapeCollection::AddGroupShape(System::SharedPtr<ISvgImage> svgImage, float x, float y, float width, float height)=0
```


### Argumentos

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| svgImage | [System::SharedPtr](../../../system/sharedptr/)\<[ISvgImage](../../isvgimage/)\> | O [ISvgImage](../../isvgimage/) contendo conteúdo vetorial para converter em formas. |
| x | **float** | A coordenada x da moldura do grupo\\u2019s, em pontos. |
| y | **float** | A coordenada y da moldura do grupo\\u2019s, em pontos. |
| width | **float** | A largura da moldura do grupo\\u2019s, em pontos. |
| height | **float** | A altura da moldura do grupo\\u2019s, em pontos. |

### Valor de Retorno

O [IGroupShape](../../igroupshape/) recém-criado.

## Ver Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IGroupShape](../../igroupshape/)
* Classe [IShapeCollection](../)
* Classe [ISvgImage](../../isvgimage/)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)