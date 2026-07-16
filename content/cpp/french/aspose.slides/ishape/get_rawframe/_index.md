---
title: get_RawFrame()
second_title: Référence de l'API Aspose.Slides for C++
description: Renvoie les propriétés du cadre brut de la forme. Lire IShapeFrame.
type: docs
weight: 40
url: /fr/aspose.slides/ishape/get_rawframe/
---
## IShape::get_RawFrame() méthode

Renvoie les propriétés du cadre brut de la forme. Lire [IShapeFrame](../../ishapeframe/).

```cpp
virtual System::SharedPtr<IShapeFrame> Aspose::Slides::IShape::get_RawFrame()=0
```

## Remarques

Le code qui tente d'assigner un cadre indéfini à [IShape::set_Frame](../set_frame/) n'a pas de sens dans le cas général (particulièrement dans le cas où le parent [GroupShape](../../groupshape/) est imbriqué plusieurs fois dans d'autres GroupShape-s). Par exemple :
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
Un tel code peut conduire à des situations ambiguës. Ainsi, des restrictions ont été ajoutées pour l'utilisation de valeurs indéfinies pour [IShape::set_Frame](../set_frame/). Les valeurs de x, y, width, height, flipH, flipV et rotationAngle doivent être définies (pas std::numeric_limits<float>::quiet_NaN() ou [NullableBool::NotDefined](../../nullablebool/)). Le code d'exemple ci-dessous lance maintenant une exception ArgumentException. Ceci s'applique aux cas d'utilisation suivants :
```cpp
SharedPtr<IShape> shape = ...;
shape->set_Frame(...); // ne peut pas être indéfini

SharedPtr<IShapeCollection> shapes = ...;
// les paramètres x, y, width, height ne peuvent pas être std::numeric_limits<float>::quiet_NaN():
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

Cependant, un cadre pour la méthode [IShape::set_RawFrame](../set_rawframe/) peut être indéfini. Cela a du sens lorsque la forme est liée à un espace réservé. Alors les valeurs de cadre de forme indéfinies sont remplacées par celles de la forme d'espace réservé parent. S'il n'existe aucune forme d'espace réservé parent pour cette forme, alors cette forme utilise les valeurs par défaut lorsqu'elle évalue le cadre effectif en fonction de son [IShape::get_RawFrame](./). Les valeurs par défaut sont 0 et [NullableBool::False](../../nullablebool/) pour x, y, width, height, flipH, flipV et rotationAngle. Par exemple :
```cpp
SharedPtr<IShape> shape = ...; // la forme est liée à un espace réservé
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // la forme hérite maintenant des valeurs x, y, height, flipH, flipV du placeholder et surcharge width=100 et rotationAngle=0.
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShapeFrame](../../ishapeframe/)
* Classe [IShape](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)