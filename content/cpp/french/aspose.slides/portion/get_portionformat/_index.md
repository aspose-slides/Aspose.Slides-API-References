---
title: get_PortionFormat()
second_title: Référence de l'API Aspose.Slides pour C++
description: Renvoie un objet de mise en forme qui contient les propriétés de mise en forme définies explicitement de la portion de texte sans héritage appliqué. Lecture seule IPortionFormat.
type: docs
weight: 1
url: /fr/aspose.slides/portion/get_portionformat/
---
## Portion::get_PortionFormat() méthode

Renvoie l'objet de mise en forme qui contient les propriétés de mise en forme définies explicitement de la portion de texte sans héritage appliqué. Lecture seule [IPortionFormat](../../iportionformat/).

```cpp
System::SharedPtr<IPortionFormat> Aspose::Slides::Portion::get_PortionFormat() override
```

## Remarques

L'objet de mise en forme contient les paramètres de mise en forme définis uniquement pour la portion actuelle, les données héritées ne sont pas appliquées.

Afin d'obtenir les valeurs effectives incluant celles héritées, utilisez la [PortionFormat::GetEffective](../../portionformat/geteffective/) méthode.

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortionFormat](../../iportionformat/)
* Classe [Portion](../)
* Espace de noms [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)