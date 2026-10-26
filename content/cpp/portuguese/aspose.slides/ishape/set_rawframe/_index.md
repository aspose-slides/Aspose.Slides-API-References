---
title: set_RawFrame()
second_title: Referência da API Aspose.Slides para C++
description: Define as propriedades do quadro bruto da forma. Escreva IShapeFrame.
type: docs
weight: 53
url: /pt/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) método

Define as propriedades do quadro bruto da forma. Escreva [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## Observações

Código que tenta atribuir um quadro indefinido a [IShape::set_Frame](../set_frame/) não faz sentido no caso geral (particularmente no caso em que o pai [GroupShape](../../groupshape/) está aninhado múltiplas vezes em outros GroupShape-s). Por exemplo: 
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
 Tal código pode levar a situações pouco claras. Portanto, restrições foram adicionadas para o uso de valores indefinidos para [IShape::set_Frame](../set_frame/). Valores de x, y, width, height, flipH, flipV e rotationAngle devem ser definidos (não std::numeric_limits<float>::quiet_NaN() ou [NullableBool::NotDefined](../../nullablebool/)). O código de exemplo acima agora lança a exceção ArgumentException. Isto se aplica a estes casos de uso: 
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

Mas um quadro para o método [IShape::set_RawFrame](./) pode ser indefinido. Isso faz sentido quando a forma está vinculada a um placeholder. Então os valores indefinidos do quadro da forma são sobrescritos a partir da forma placeholder pai. Se não houver forma placeholder pai para essa forma, então ela usa valores padrão ao avaliar o quadro efetivo com base em seu [IShape::get_RawFrame](../get_rawframe/). Valores padrão são 0 e [NullableBool::False](../../nullablebool/) para x, y, width, height, flipH, flipV e rotationAngle. Por exemplo: 
```cpp
SharedPtr<IShape> shape = ...; // forma está vinculada ao placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // agora a forma herda valores x, y, altura, flipH, flipV do placeholder e sobrescreve width=100 e rotationAngle=0.
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShapeFrame](../../ishapeframe/)
* Classe [IShape](../)
* Namespace [Aspose::Slides](../../)
* Biblioteca [Aspose.Slides](../../../)