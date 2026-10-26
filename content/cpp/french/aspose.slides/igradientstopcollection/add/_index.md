---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection.
type: docs
weight: 14
url: /fr/aspose.slides/igradientstopcollection/add/
---
## IGradientStopCollection::Add(float, System::Drawing::Color) méthode

Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection.

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, System::Drawing::Color color)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| position | **float** | Position du nouveau point d'arrêt de dégradé. |
| color | [System::Drawing::Color](../../../system.drawing/color/) | Couleur du nouveau point d'arrêt de dégradé. |

### Valeur de retour

Indice du nouveau point d'arrêt de dégradé dans la collection.

## IGradientStopCollection::Add(float, PresetColor) méthode

Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection.

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, PresetColor presetColor)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| position | **float** | Position du nouveau point d'arrêt de dégradé. |
| presetColor | [PresetColor](../../presetcolor/) | Couleur du nouveau point d'arrêt de dégradé. |

### Valeur de retour

Indice du nouveau point d'arrêt de dégradé dans la collection.

## IGradientStopCollection::Add(float, SchemeColor) méthode

Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection.

```cpp
virtual System::SharedPtr<IGradientStop> Aspose::Slides::IGradientStopCollection::Add(float position, SchemeColor schemeColor)=0
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| position | **float** | Position du nouveau point d'arrêt de dégradé. |
| schemeColor | [SchemeColor](../../schemecolor/) | Couleur du nouveau point d'arrêt de dégradé. |

### Valeur de retour

Indice du nouveau point d'arrêt de dégradé dans la collection.

## Voir aussi

* Enum [PresetColor](../../presetcolor/)
* Enum [SchemeColor](../../schemecolor/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGradientStop](../../igradientstop/)
* Class [Color](../../../system.drawing/color/)
* Class [IGradientStopCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)