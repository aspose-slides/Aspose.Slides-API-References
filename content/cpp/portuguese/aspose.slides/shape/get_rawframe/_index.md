---
title: get_RawFrame()
second_title: Referência da API Aspose.Slides para C++
description: Retorna as propriedades da moldura bruta da forma. Leia IShapeFrame.
type: docs
weight: 40
url: /pt/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() método

Retorna as propriedades da moldura bruta da forma. Leia [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## Observações

Código que tenta atribuir uma moldura indefinida a [IShape::set_Frame](../../ishape/set_frame/) não faz sentido no caso geral (particularmente no caso em que o pai [GroupShape](../../groupshape/) está aninhado múltiplas vezes em outros GroupShape-s). Por exemplo:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), NullableBool::NotDefined, 
NullableBool::NotDefined, std::numeric_limits<float>::quiet_NaN()));
```
 ou 
```cpp
slide->get_Shapes()->AddAutoShape(ShapeType::RoundCornerRectangle,
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), std::numeric_limits<float>::quiet_NaN());
```
 Tal código pode levar a situações ambíguas. Portanto, restrições foram adicionadas para usar valores indefinidos para [IShape::set_Frame](../../ishape/set_frame/). Valores de x, y, width, height, flipH, flipV e rotationAngle devem ser definidos (não std::numeric_limits<float>::quiet_NaN() ou [NullableBool::NotDefined](../../nullablebool/)). O código de exemplo acima agora lança a exceção ArgumentException. Isso se aplica aos seguintes casos de uso:
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // não pode ser indefinido

SharedPtr<IShapeCollection> shapes = ...;
// os parâmetros x, y, width, height não podem ser std::numeric_limits<float>::quiet_NaN():
{
    shapes->AddAudioFrameCD(...);
    shapes->AddAudioFrameEmbedded(...);
    shapes->AddAudioFrameLinked(...);
    shapes->AddAutoShape(...);
    shapes->AddChart(...);
    shapes->AddConnector(...);
    shapes->AddOleObjectFrame(...);
    shapes->AddPictureFrame(...);
    shapes->AddSmartArt(...);
    shapes->AddTable(...);
    shapes->AddVideoFrame(...);
    shapes->InsertAudioFrameEmbedded(...);
    shapes->InsertAudioFrameLinked(...);
    shapes->InsertAutoShape(...);
    shapes->InsertChart(...);
    shapes->InsertConnector(...);
    shapes->InsertOleObjectFrame(...);
    shapes->InsertPictureFrame(...);
    shapes->InsertTable(...);
    shapes->InsertVideoFrame(...);
}
```

Mas uma moldura para o método [IShape::set_RawFrame](../../ishape/set_rawframe/) pode ser indefinida. Isso faz sentido quando a forma está vinculada a um placeholder. Então, os valores indefinidos da moldura da forma são substituídos pelos valores da forma placeholder pai. Se não houver forma placeholder pai para essa forma, ela usa valores padrão ao avaliar a moldura efetiva com base em seu [IShape::get_RawFrame](../../ishape/get_rawframe/). Os valores padrão são 0 e [NullableBool::False](../../nullablebool/) para x, y, width, height, flipH, flipV e rotationAngle. Por exemplo:
```cpp
SharedPtr<IShape> shape = ...; // shape está vinculada ao placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // agora shape herda os valores x, y, height, flipH, flipV do placeholder e sobrescreve width=100 e rotationAngle=0.
```

## Ver também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShapeFrame](../../ishapeframe/)
* Classe [Shape](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)