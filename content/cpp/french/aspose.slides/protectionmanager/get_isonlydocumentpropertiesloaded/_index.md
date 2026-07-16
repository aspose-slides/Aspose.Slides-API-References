---
title: get_IsOnlyDocumentPropertiesLoaded()
second_title: Référence API Aspose.Slides pour C++
description: Cette propriété n'a de sens que si le fichier de présentation est protégé par mot de passe et que les propriétés du document de ce fichier sont publiques. La valeur true signifie que seules les propriétés du document sont chargées à partir d'un fichier de présentation chiffré sans utilisation du mot de passe. La valeur false signifie que toute la présentation chiffrée est chargée en utilisant le bon mot de passe, et que les propriétés du document ne sont pas les seules chargées. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours false. Si les propriétés du document d'un fichier chiffré ne sont pas publiques, la valeur de la propriété est toujours false. Si Presentation.EncryptDocumentProperties est true, alors la valeur de la propriété IsOnlyDocumentPropertiesLoaded est toujours false. Lecture seule bool.
type: docs
weight: 40
url: /fr/aspose.slides/protectionmanager/get_isonlydocumentpropertiesloaded/
---
## ProtectionManager::get_IsOnlyDocumentPropertiesLoaded() méthode

Cette propriété n'a de sens que si le fichier de présentation est protégé par mot de passe et que les propriétés du document de ce fichier sont publiques. La valeur true signifie que seules les propriétés du document sont chargées à partir d'un fichier de présentation chiffré sans utilisation du mot de passe. La valeur false signifie que la présentation chiffrée entière est chargée avec le mot de passe correct, et que ce ne sont pas uniquement les propriétés du document qui sont chargées. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours false. Si les propriétés du document d'un fichier chiffré ne sont pas publiques, la valeur de la propriété est toujours false. Si Presentation.EncryptDocumentProperties est true, alors la valeur de la propriété IsOnlyDocumentPropertiesLoaded est toujours false. Lecture seule **bool**.

```cpp
bool Aspose::Slides::ProtectionManager::get_IsOnlyDocumentPropertiesLoaded() override
```

## Voir aussi

* Classe [ProtectionManager](../)
* Espace de noms [Aspose::Slides](../../)
* Bibliothèque [Aspose.Slides](../../../)