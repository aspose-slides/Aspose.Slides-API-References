---
title: get_PortionFormat()
second_title: Référence API Aspose.Slides pour C++
description: Retourne un objet de formatage qui contient les propriétés de formatage définies explicitement de la portion de texte sans aucun héritage appliqué. Lecture seule IPortionFormat.
type: docs
weight: 1
url: /fr/aspose.slides/iportion/get_portionformat/
---
## IPortion::get_PortionFormat() méthode

Retourne un objet de formatage contenant les propriétés de formatage définies explicitement pour la portion de texte, sans aucun héritage appliqué. Lecture seule [IPortionFormat](../../iportionformat/).

```cpp
virtual System::SharedPtr<IPortionFormat> Aspose::Slides::IPortion::get_PortionFormat()=0
```

## Remarques

L'objet de formatage contient les paramètres de formatage définis uniquement pour la portion actuelle, les données héritées ne sont pas appliquées.

Pour obtenir les valeurs effectives incluant celles héritées, utilisez la méthode [IPortionFormat::GetEffective](../../iportionformat/geteffective/).

## Voir aussi

* Typedef [SharedPtr](../../../system/sharedptr/)
* Classe [IPortionFormat](../../iportionformat/)
* Classe [IPortion](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)