---
title: IProtectionManager class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/iprotectionmanager/
---
## IProtectionManager classe

Gestion de la protection par mot de passe de la présentation.

Le type IProtectionManager expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/fr/aspose.slides/iprotectionmanager/encrypt_document_properties/) | Cette propriété a du sens si la présentation est protégée par un mot de passe.<br/>            Si vrai alors les propriétés du document sont chiffrées dans le fichier de présentation.<br/>            Si faux alors les propriétés du document sont publiques tandis que la présentation est chiffrée.<br/>            Lecture/écriture **bool**. |
| [`is_encrypted`](/slides/python-net/fr/aspose.slides/iprotectionmanager/is_encrypted/) | Obtient une valeur indiquant si cette instance est chiffrée.<br/>            Lecture seule **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/fr/aspose.slides/iprotectionmanager/is_only_document_properties_loaded/) | Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe et que les propriétés du document de ce fichier sont publiques.<br/>            La valeur vraie signifie que seules les propriétés du document sont chargées depuis un fichier de présentation chiffré sans utilisation du mot de passe.<br/>            La valeur fausse signifie que toute la présentation chiffrée est chargée avec le bon mot de passe, pas seulement les propriétés du document.<br/>            Si la présentation n'est pas chiffrée, alors la valeur de la propriété est toujours fausse.<br/>            Si les propriétés du document d'un fichier chiffré ne sont pas publiques, alors la valeur de la propriété est toujours fausse.<br/>            Si PresentationEx.EncryptDocumentProperties est vrai, alors la valeur de la propriété IsOnlyDocumentPropertiesLoaded est toujours fausse.<br/>            Lecture seule **bool**. |
| [`is_write_protected`](/slides/python-net/fr/aspose.slides/iprotectionmanager/is_write_protected/) | Obtient une valeur indiquant si cette présentation est protégée en écriture.<br/>            Lecture seule **bool**. |
| [`encryption_password`](/slides/python-net/fr/aspose.slides/iprotectionmanager/encryption_password/) | Renvoie le mot de passe de chiffrement.<br/>            Lecture seule **str**. |
| [`read_only_recommended`](/slides/python-net/fr/aspose.slides/iprotectionmanager/read_only_recommended/) | Obtient ou définit la recommandation en lecture seule.<br/>            Lecture/écriture **bool**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/fr/aspose.slides/iprotectionmanager/encrypt/#str) | Chiffre la présentation avec le mot de passe spécifié. |
| [`remove_encryption(self)`](/slides/python-net/fr/aspose.slides/iprotectionmanager/remove_encryption/#) | Supprime le chiffrement. |
| [`set_write_protection(self, password)`](/slides/python-net/fr/aspose.slides/iprotectionmanager/set_write_protection/#str) | Définit la protection en écriture pour cette présentation avec le mot de passe spécifié. |
| [`remove_write_protection(self)`](/slides/python-net/fr/aspose.slides/iprotectionmanager/remove_write_protection/#) | Supprime la protection en écriture pour cette présentation. |
| [`check_write_protection(self, password)`](/slides/python-net/fr/aspose.slides/iprotectionmanager/check_write_protection/#str) | Détermine si une présentation est protégée par un mot de passe pour la modifier. |

### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)