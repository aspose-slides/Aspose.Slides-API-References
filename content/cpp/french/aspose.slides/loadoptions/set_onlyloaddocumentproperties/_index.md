---
title: set_OnlyLoadDocumentProperties()
second_title: Référence API Aspose.Slides pour C++
description: Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe. La valeur true signifie que seules les propriétés du document doivent être chargées à partir d'un fichier de présentation chiffré et que le mot de passe doit être ignoré. La valeur false signifie que la présentation chiffrée entière doit être chargée en utilisant le bon mot de passe. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d'un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, alors les propriétés du document ne peuvent pas être chargées et une exception sera levée. Écrire **bool**.
type: docs
weight: 144
url: /fr/aspose.slides/loadoptions/set_onlyloaddocumentproperties/
---
## LoadOptions::set_OnlyLoadDocumentProperties(bool) méthode

Cette propriété a du sens, si le fichier de présentation est protégé par mot de passe. La valeur true signifie que seules les propriétés du document doivent être chargées à partir d'un fichier de présentation chiffré et que le mot de passe doit être ignoré. La valeur false signifie que la présentation chiffrée entière doit être chargée en utilisant le mot de passe correct. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d'un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, alors les propriétés du document ne peuvent pas être chargées et une exception sera levée. Écrire **bool**.

```cpp
void Aspose::Slides::LoadOptions::set_OnlyLoadDocumentProperties(bool value) override
```

## Voir aussi

* Classe [LoadOptions](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)