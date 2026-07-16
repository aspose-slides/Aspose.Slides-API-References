---
title: get_ThreeDFormat()
second_title: Référence API Aspose.Slides pour C++
description: Renvoie l'objet ThreeDFormat qui représente les propriétés d'effet 3D d'un texte. Lecture seule IThreeDFormat.
type: docs
weight: 300
url: /fr/aspose.slides/itextframeformat/get_threedformat/
---
## ITextFrameFormat::get_ThreeDFormat() méthode


Renvoie l'objet [ThreeDFormat](../../threedformat/) qui représente les propriétés d'effet 3D pour un texte. Lecture seule [IThreeDFormat](../../ithreedformat/).

```cpp
virtual System::SharedPtr<IThreeDFormat> Aspose::Slides::ITextFrameFormat::get_ThreeDFormat()=0
```

## Remarques



```cpp
using namespace Aspose::Slides;

auto pres = System::MakeObject<Presentation>();
auto autoShape = pres->get_Slides()->idx_get(0)->get_Shapes()->AddAutoShape(ShapeType::Rectangle, 10.0f, 20.0f, 400.0f, 300.0f);
auto textFrame = autoShape->get_TextFrame();

textFrame->set_Text(u"Aspose.Slide Test Text");

// Set text transformation
textFrame->get_TextFrameFormat()->set_Transform(TextShapeType::ArchUpPour);

// Set Extrusion
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_ExtrusionColor()->set_Color(System::Drawing::Color::get_Orange());
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->set_ExtrusionHeight(6);

// Set Contour
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_ContourColor()->set_Color(System::Drawing::Color::get_DarkRed());
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->set_ContourWidth(1.5);

// Set Depth
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->set_Depth(3);

// Set Material
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->set_Material(MaterialPresetType::Plastic);

// Set Lighting
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_LightRig()->set_Direction(LightingDirection::Top);
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_LightRig()->set_LightType(LightRigPresetType::Balanced);
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_LightRig()->SetRotation(0.0f, 0.0f, 40.0f);

// Set camera type
textFrame->get_TextFrameFormat()->get_ThreeDFormat()->get_Camera()->set_CameraType(CameraPresetType::PerspectiveContrastingRightFacing);
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IThreeDFormat](../../ithreedformat/)
* Classe [ITextFrameFormat](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)