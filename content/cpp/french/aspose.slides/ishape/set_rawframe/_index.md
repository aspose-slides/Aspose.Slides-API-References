---
title: set_RawFrame()
second_title: Référence API Aspose.Slides pour C++
description: Définit les propriétés du cadre brut de la forme. Écrivez IShapeFrame.
type: docs
weight: 53
url: /fr/aspose.slides/ishape/set_rawframe/
---
## IShape::set_RawFrame(System::SharedPtr\<IShapeFrame\>) méthode


Définit les propriétés du cadre brut de la forme. Écrivez [IShapeFrame](../../ishapeframe/).

```cpp
virtual void Aspose::Slides::IShape::set_RawFrame(System::SharedPtr<IShapeFrame> value)=0
```

## Remarques


Le code qui tente d'attribuer un cadre indéfini à [IShape::set_Frame](../set_frame/) n'a pas de sens dans le cas général (particulièrement lorsqu'un parent [GroupShape](../../groupshape/) est imbriqué plusieurs fois dans d'autres GroupShape-s). Par exemple: 
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
 Un tel code peut conduire à des situations ambiguës. Ainsi, des restrictions ont été ajoutées pour l'utilisation de valeurs indéfinies pour [IShape::set_Frame](../set_frame/). Les valeurs de x, y, width, height, flipH, flipV et rotationAngle doivent être définies (pas std::numeric_limits<float>::quiet_NaN() ou [NullableBool::NotDefined](../../nullablebool/)). Le code d'exemple ci-dessus lève désormais une exception ArgumentException. Cela s'applique à ces cas d'utilisation: 
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


Cependant, un cadre pour la méthode [IShape::set_RawFrame](./) peut être indéfini. Cela a du sens lorsqu'une forme est liée à un espace réservé. Alors les valeurs de cadre indéfinies de la forme sont remplacées par celles de la forme espace réservé parent. S'il n'existe pas de forme espace réservé parent pour cette forme, alors cette forme utilise les valeurs par défaut lorsqu'elle évalue le cadre effectif en fonction de son [IShape::get_RawFrame](../get_rawframe/). Les valeurs par défaut sont 0 et [NullableBool::False](../../nullablebool/) pour x, y, width, height, flipH, flipV et rotationAngle. Par exemple: 
```cpp
SharedPtr<IShape> shape = ...; // la forme est liée à placeholder
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // maintenant la forme hérite des valeurs x, y, height, flipH, flipV du placeholder et remplace width=100 et rotationAngle=0.
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShapeFrame](../../ishapeframe/)
* Classe [IShape](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)