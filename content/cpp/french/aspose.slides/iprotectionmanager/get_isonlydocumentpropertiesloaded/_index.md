---
title: get_IsOnlyDocumentPropertiesLoaded()
second_title: Référence de l'API Aspose.Slides pour C++
description: Cette propriété a du sens si le fichier de présentation est protégé par mot de passe et que les propriétés du document de ce fichier sont publiques. La valeur true indique que seules les propriétés du document sont chargées à partir d'un fichier de présentation chiffré sans utilisation du mot de passe. La valeur false indique que la présentation chiffrée entière est chargée avec le bon mot de passe, et pas seulement les propriétés du document sont chargées. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours false. Si les propriétés du document d'un fichier chiffré ne sont pas publiques, la valeur de la propriété est toujours false. Si PresentationEx.EncryptDocumentProperties est true, alors la valeur de la propriété IsOnlyDocumentPropertiesLoaded est toujours false. Lecture seule bool.
type: docs
weight: 40
url: /fr/aspose.slides/iprotectionmanager/get_isonlydocumentpropertiesloaded/
---
## IProtectionManager::get_IsOnlyDocumentPropertiesLoaded() méthode

Cette propriété a du sens, si le fichier de présentation est protégé par mot de passe et que les propriétés du document de ce fichier sont publiques. La valeur true signifie que seules les propriétés du document sont chargées à partir d'un fichier de présentation chiffré sans utilisation du mot de passe. La valeur false signifie que la présentation chiffrée entière est chargée avec le mot de passe correct, et pas seulement les propriétés du document sont chargées. Si la présentation n'est pas chiffrée, alors la valeur de la propriété est toujours false. Si les propriétés du document d'un fichier chiffré ne sont pas publiques, alors la valeur de la propriété est toujours false. Si PresentationEx.EncryptDocumentProperties est true alors la valeur de la propriété IsOnlyDocumentPropertiesLoaded est toujours false. Lecture seule **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_IsOnlyDocumentPropertiesLoaded()=0
```

## Voir aussi

* Classe [IProtectionManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)