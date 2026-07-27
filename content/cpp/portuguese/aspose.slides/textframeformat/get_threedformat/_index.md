---
title: get_ThreeDFormat()
second_title: Referência da API Aspose.Slides para C++
description: Retorna o objeto ThreeDFormat que representa as propriedades de efeito 3d para um texto. Somente leitura IThreeDFormat.
type: docs
weight: 1
url: /pt/aspose.slides/textframeformat/get_threedformat/
---
## TextFrameFormat::get_ThreeDFormat() método

Retorna o [ThreeDFormat](../../threedformat/) objeto que representa as propriedades de efeito 3d para um texto. Somente leitura [IThreeDFormat](../../ithreedformat/).

```cpp
System::SharedPtr<IThreeDFormat> Aspose::Slides::TextFrameFormat::get_ThreeDFormat() override
```

## Observações

```cpp
using namespace Aspose::Slides;

auto pres = System::MakeObject<Presentation>();
auto autoShape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 20.0f, 400.0f, 300.0f);
auto textFrame = autoShape->get_TextFrame();

textFrame->set_Text(u"Aspose.Slide Test Text");

// Definir transformação de texto
textFrame->get_TextFrameFormat()->set_Transform(TextShapeType::ArchUpPour);

// Definir extrusão
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_ExtrusionColor()->set_Color(System::Drawing::Color::get_Orange());
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->set_ExtrusionHeight(6);

// Definir contorno
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_ContourColor()->set_Color(System::Drawing::Color::get_DarkRed());
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->set_ContourWidth(1.5);

// Definir profundidade
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->set_Depth(3);

// Definir material
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->set_Material(MaterialPresetType::Plastic);

// Definir iluminação
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_LightRig()->set_Direction(LightingDirection::Top);
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_LightRig()->set_LightType(LightRigPresetType::Balanced);
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_LightRig()->SetRotation(0.0f, 0.0f, 40.0f);

// Set camera type
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_Camera()->set_CameraType(CameraPresetType::PerspectiveContrastingRightFacing);
```

## Veja Também

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IThreeDFormat](../../ithreedformat/)
* Classe [TextFrameFormat](../)
* Espaço de nomes [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)