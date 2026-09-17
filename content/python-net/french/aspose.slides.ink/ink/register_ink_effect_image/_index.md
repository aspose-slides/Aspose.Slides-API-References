---
title: register_ink_effect_image method
second_title: Aspose.Slides pour Python via .NET Référence d'API
description: 
type: docs
url: /fr/aspose.slides.ink/ink/register_ink_effect_image/
weight: 50
---
## register_ink_effect_image(effect_type, image) {#inkeffecttype-iimage}
Enregistre une image dans la collection d'images personnalisées utilisées pour simuler les effets visuels des pinceaux à encre.
            Ces images sont utilisées lors du rendu de l'encre avec des valeurs [`InkEffectType`](/slides/python-net/fr/aspose.slides.ink/inkeffecttype) spécifiques,
            telles que Galaxy, Rainbow, etc. En fournissant vos propres images, vous pouvez contrôler l'apparition de chaque effet d'encre.


```python
@staticmethod
def register_ink_effect_image(effect_type, image):
    ...
```


| Paramètre | Type | Description |
| :- | :- | :- |
| effect_type | [`InkEffectType`](/slides/python-net/fr/aspose.slides.ink/inkeffecttype) |  |
| image | [`IImage`](/slides/python-net/fr/aspose.slides/iimage) |  |

### Remarques

Cette méthode permet de remplacer les textures d'effets d'encre par défaut par des textures définies par l'utilisateur,
            ce qui est particulièrement utile lorsque les ressources par défaut sont limitées par des licences ou indisponibles à l'exécution.
            Chaque paire de valeurs enregistrée doit associer une valeur [`InkEffectType`](/slides/python-net/fr/aspose.slides.ink/inkeffecttype) à un objet [`IImage`](/slides/python-net/fr/aspose.slides/iimage) correspondant
            (par exemple, Bitmap, ou une interface d'image Aspose).


### Voir aussi
* classe [`IImage`](/slides/python-net/fr/aspose.slides/iimage)
* classe [`Ink`](/slides/python-net/fr/aspose.slides.ink/ink)
* énumération [`InkEffectType`](/slides/python-net/fr/aspose.slides.ink/inkeffecttype)
* module [`aspose.slides.ink`](/slides/python-net/fr/aspose.slides.ink)
* bibliothèque [`Aspose.Slides`](/slides/python-net)