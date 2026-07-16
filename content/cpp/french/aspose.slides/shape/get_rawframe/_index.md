---
title: get_RawFrame()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie les propriétés du cadre brut de la forme. Lire IShapeFrame.
type: docs
weight: 40
url: /fr/aspose.slides/shape/get_rawframe/
---
## Shape::get_RawFrame() méthode

Renvoie les propriétés du cadre brut de la forme. Lire [IShapeFrame](../../ishapeframe/).

```cpp
System::SharedPtr<IShapeFrame> Aspose::Slides::Shape::get_RawFrame() override
```

## Remarques

Le code qui tente d'assigner un cadre indéfini à [IShape::set_Frame](../../ishape/set_frame/) n'a pas de sens dans le cas général (particulièrement lorsque le parent [GroupShape](../../groupshape/) est imbriqué plusieurs fois dans d'autres GroupShape-s). Par exemple :
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
Un tel code peut entraîner des situations ambiguës. Des restrictions ont donc été ajoutées pour l'utilisation de valeurs indéfinies pour [IShape::set_Frame](../../ishape/set_frame/). Les valeurs de x, y, width, height, flipH, flipV et rotationAngle doivent être définies (pas std::numeric_limits<float>::quiet_NaN() ou [NullableBool::NotDefined](../../nullablebool/)). Le code d'exemple ci-dessus lève maintenant une exception ArgumentException. Cela s'applique à ces cas d'utilisation :
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

Mais un cadre pour la méthode [IShape::set_RawFrame](../../ishape/set_rawframe/) peut être indéfini. Cela a du sens lorsque la forme est liée à un espace réservé. Alors les valeurs indéfinies du cadre de forme sont remplacées par celles de la forme d'espace réservé parente. S'il n'existe pas de forme d'espace réservé parente pour cette forme, alors cette forme utilise les valeurs par défaut lorsqu'elle calcule le cadre effectif en fonction de son [IShape::get_RawFrame](../../ishape/get_rawframe/). Les valeurs par défaut sont 0 et [NullableBool::False](../../nullablebool/) pour x, y, width, height, flipH, flipV et rotationAngle. Par exemple :
```cpp
SharedPtr<IShape> shape = ...; // la forme est liée à un espace réservé
shape->set_RawFrame(System::MakeObject<ShapeFrame>(std::numeric_limits<float>::quiet_NaN(), 
std::numeric_limits<float>::quiet_NaN(), 100.0f, std::numeric_limits<float>::quiet_NaN(), 
NullableBool::NotDefined, NullableBool::NotDefined, 0.0f)); // maintenant la forme hérite des valeurs x, y, height, flipH, flipV de l'espace réservé et remplace width=100 et rotationAngle=0.
```

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IShapeFrame](../../ishapeframe/)
* Classe [Shape](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)