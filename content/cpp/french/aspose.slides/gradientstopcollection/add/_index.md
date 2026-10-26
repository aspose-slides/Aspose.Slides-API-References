---
title: Add()
second_title: Référence de l'API Aspose.Slides pour C++
description: Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection.
type: docs
weight: 53
url: /fr/aspose.slides/gradientstopcollection/add/
---
## GradientStopCollection::Add(float, System::Drawing::Color) méthode

Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, System::Drawing::Color color) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| position | **float** | Position du nouveau point d'arrêt de dégradé. |
| color | [System::Drawing::Color](../../../system.drawing/color/) | Couleur du nouveau point d'arrêt radient. |

### Valeur de retour

Indice du nouveau point d'arrêt de dégradé dans la collection.

## GradientStopCollection::Add(float, PresetColor) méthode

Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, PresetColor presetColor) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| position | **float** | Position du nouveau point d'arrêt de dégradé. |
| presetColor | [PresetColor](../../presetcolor/) | Couleur du nouveau point d'arrêt radient. |

### Valeur de retour

Indice du nouveau point d'arrêt de dégradé dans la collection.

## GradientStopCollection::Add(float, SchemeColor) méthode

Crée le nouveau point d'arrêt de dégradé et l'ajoute à la fin de la collection.

```cpp
System::SharedPtr<IGradientStop> Aspose::Slides::GradientStopCollection::Add(float position, SchemeColor schemeColor) override
```

### Arguments

| Paramètre | Type | Description |
| --- | --- | --- |
| position | **float** | Position du nouveau point d'arrêt de dégradé. |
| schemeColor | [SchemeColor](../../schemecolor/) | Couleur du nouveau point d'arrêt radient. |

### Valeur de retour

Indice du nouveau point d'arrêt de dégradé dans la collection.

## Voir aussi

* Enum [PresetColor](../../presetcolor/)
* Enum [SchemeColor](../../schemecolor/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IGradientStop](../../igradientstop/)
* Class [Color](../../../system.drawing/color/)
* Class [GradientStopCollection](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)