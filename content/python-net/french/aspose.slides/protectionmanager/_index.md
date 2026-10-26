---
title: ProtectionManager class
second_title: Référence de l'API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/protectionmanager/
---
## ProtectionManager classe

Gestion de la protection par mot de passe de la présentation.

Le type ProtectionManager expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`encrypt_document_properties`](/slides/python-net/fr/aspose.slides/protectionmanager/encrypt_document_properties/) | Cette propriété a du sens si la présentation est protégée par mot de passe.<br/>            Si vrai alors les propriétés du document sont chiffrées dans le fichier de présentation.<br/>            Si faux alors les propriétés du document sont publiques tandis que la présentation est chiffrée.<br/>            Lecture/écriture **bool**. |
| [`is_encrypted`](/slides/python-net/fr/aspose.slides/protectionmanager/is_encrypted/) | Obtient une valeur indiquant si cette instance est chiffrée.<br/>            Lecture seule **bool**. |
| [`is_only_document_properties_loaded`](/slides/python-net/fr/aspose.slides/protectionmanager/is_only_document_properties_loaded/) | Cette propriété a du sens si le fichier de présentation est protégé par mot de passe et que les propriétés du document de ce fichier sont publiques.<br/>            La valeur vrai signifie que seules les propriétés du document sont chargées à partir d'un fichier de présentation chiffré sans utilisation du mot de passe.<br/>            La valeur faux signifie que la totalité de la présentation chiffrée est chargée avec l'utilisation du mot de passe correct, pas seulement les propriétés du document.<br/>            Si la présentation n'est pas chiffrée, alors la valeur de la propriété est toujours faux.<br/>            Si les propriétés du document d'un fichier chiffré ne sont pas publiques, alors la valeur de la propriété est toujours faux.<br/>            Si Presentation.EncryptDocumentProperties est vrai alors la valeur de la propriété IsOnlyDocumentPropertiesLoaded est toujours faux.<br/>            Lecture seule **bool**. |
| [`is_write_protected`](/slides/python-net/fr/aspose.slides/protectionmanager/is_write_protected/) | Obtient une valeur indiquant si cette présentation est protégée en écriture.<br/>            Lecture seule **bool**. |
| [`encryption_password`](/slides/python-net/fr/aspose.slides/protectionmanager/encryption_password/) | Obtient le mot de passe utilisé pour le chiffrement de la présentation.<br/>            Lecture seule **str**. |
| [`read_only_recommended`](/slides/python-net/fr/aspose.slides/protectionmanager/read_only_recommended/) | Obtient ou définit la recommandation en lecture seule.<br/>            Lecture/écriture **bool**. |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`encrypt(self, encryption_password)`](/slides/python-net/fr/aspose.slides/protectionmanager/encrypt/#str) | Chiffre la présentation avec le mot de passe spécifié. |
| [`remove_encryption(self)`](/slides/python-net/fr/aspose.slides/protectionmanager/remove_encryption/#) | Supprime le chiffrement. |
| [`set_write_protection(self, password)`](/slides/python-net/fr/aspose.slides/protectionmanager/set_write_protection/#str) | Définit la protection en écriture pour cette présentation avec le mot de passe spécifié. |
| [`remove_write_protection(self)`](/slides/python-net/fr/aspose.slides/protectionmanager/remove_write_protection/#) | Supprime la protection en écriture pour cette présentation. |
| [`check_write_protection(self, password)`](/slides/python-net/fr/aspose.slides/protectionmanager/check_write_protection/#str) | Détermine si une présentation est protégée par mot de passe pour la modification. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)