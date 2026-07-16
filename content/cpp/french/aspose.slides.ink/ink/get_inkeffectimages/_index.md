---
title: get_InkEffectImages()
second_title: Référence de l'API Aspose.Slides pour C++
description: Obtient la collection d'images personnalisées utilisées pour simuler des effets visuels pour les pinceaux d'encre. Ces images sont utilisées lors du rendu de l'encre avec des valeurs InkEffectType spécifiques, telles que Galaxy, Rainbow, etc. En fournissant vos propres images, vous pouvez contrôler l'apparence de chaque effet d'encre.
type: docs
weight: 14
url: /fr/aspose.slides.ink/ink/get_inkeffectimages/
---
## Ink::get_InkEffectImages() méthode


Obtient la collection d'images personnalisées utilisées pour simuler des effets visuels pour les pinceaux d'encre. Ces images sont utilisées lors du rendu de l'encre avec des valeurs [InkEffectType](../../inkeffecttype/) spécifiques, telles que Galaxy, Rainbow, etc. En fournissant vos propres images, vous pouvez contrôler l'apparence de chaque effet d'encre.

```cpp
static System::SharedPtr<System::Collections::Generic::IDictionary<InkEffectType, System::SharedPtr<IImage>>> Aspose::Slides::Ink::Ink::get_InkEffectImages()
```

## Remarques


Cette propriété permet de remplacer les textures d'effet d'encre par défaut par des textures définies par l'utilisateur, ce qui est particulièrement utile lorsque les ressources par défaut sont limitées par la licence ou indisponibles à l'exécution.

Chaque entrée du dictionnaire doit associer une valeur [InkEffectType](../../inkeffecttype/) à un objet [IImage](../../../aspose.slides/iimage/) correspondant (par exemple, Bitmap, ou une interface d'image **Aspose**). 


```cpp
System::SharedPtr<IImage> image = Images::FromFile(u"image.png");
Ink::get_InkEffectImages()->Add(InkEffectType::Galaxy, image);
```

## Voir aussi

* Enum [InkEffectType](../../inkeffecttype/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IDictionary](../../../system.collections.generic/idictionary/)
* Classe [IImage](../../../aspose.slides/iimage/)
* Classe [Ink](../)
* Espace de noms [Aspose::Slides::Ink](../../)
* Library [Aspose.Slides](../../../)