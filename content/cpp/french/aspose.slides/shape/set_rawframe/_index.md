---
title: set_RawFrame()
second_title: Référence API Aspose.Slides pour C++
description: Définit les propriétés du cadre brut de la forme. Écrivez IShapeFrame.
type: docs
weight: 53
url: /fr/aspose.slides/shape/set_rawframe/
---
## Shape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) méthode

Définit les propriétés du cadre brut de la forme. Écrivez [IShapeFrame](../../ishapeframe/).

```cpp
void Aspose::Slides::Shape::set_RawFrame(System::SharedPtr<IShapeFrame> value) override
```

## Remarques

Le code qui tente d'attribuer un cadre non défini à [IShape::set_Frame](../../ishape/set_frame/) n'a pas de sens dans le cas général (particulièrement lorsque le parent [GroupShape](../../groupshape/) est imbriqué plusieurs fois dans d'autres GroupShape). Par exemple:
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
 Un tel code peut entraîner des situations ambiguës. Ainsi, des restrictions ont été ajoutées pour l'utilisation de valeurs non définies pour [IShape::set_Frame](../../ishape/set_frame/). Les valeurs de x, y, width, height, flipH, flipV et rotationAngle doivent être définies (pas std::numeric_limits<float>::quiet_NaN() ou [NullableBool::NotDefined](../../nullablebool/)). Le code d'exemple ci-dessous lance maintenant une exception ArgumentException. Cela s'applique à ces cas d'utilisation:
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

Mais le cadre pour la méthode [IShape::set_RawFrame](../../ishape/set_rawframe/) peut être non défini. Cela a du sens lorsque la forme est liée à un espace réservé. Alors les valeurs du cadre de forme non définies sont remplacées par celles de la forme d'espace réservé parent. S'il n'existe aucun espace réservé parent pour cette forme, alors la forme utilise les valeurs par défaut lorsqu'elle évalue le cadre effectif en fonction de son [IShape::get_RawFrame](../../ishape/get_rawframe/). Les valeurs par défaut sont 0 et [NullableBool::False](../../nullablebool/) pour x, y, width, height, flipH, flipV et rotationAngle. Par exemple:
```cpp
SharedPtr<IShape> shape = ...; // la forme est liée à l'espace réservé
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // maintenant la forme hérite des valeurs x, y, height, flipH, flipV du placeholder et surcharge width=100 et rotationAngle=0.
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShapeFrame](../../ishapeframe/)
* Classe [Shape](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)