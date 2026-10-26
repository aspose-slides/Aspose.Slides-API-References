---
title: PresentationInfo class
second_title: Référence API Aspose.Slides pour Python via .NET
description: 
type: docs
url: /fr/aspose.slides/presentationinfo/
---
## PresentationInfo classe

Informations sur le fichier de présentation

Le type PresentationInfo expose les membres suivants :

## Propriétés

| Propriété | Description |
| :- | :- |
| [`is_encrypted`](/slides/python-net/fr/aspose.slides/presentationinfo/is_encrypted/) | Obtient True si la présentation liée est chiffrée, sinon False.<br/>            Lecture seule **bool**. |
| [`is_password_protected`](/slides/python-net/fr/aspose.slides/presentationinfo/is_password_protected/) | Obtient une valeur indiquant si la présentation liée est protégée par un mot de passe d'ouverture. |
| [`is_write_protected`](/slides/python-net/fr/aspose.slides/presentationinfo/is_write_protected/) | Obtient une valeur indiquant si la présentation liée est protégée en écriture. |
| [`load_format`](/slides/python-net/fr/aspose.slides/presentationinfo/load_format/) | Obtient le format de la présentation liée.<br/>            Lecture seule [`LoadFormat`](/slides/python-net/fr/aspose.slides/loadformat). |

## Méthodes

| Méthode | Description |
| :- | :- |
| [`write_binded_presentation(self, stream)`](/slides/python-net/fr/aspose.slides/presentationinfo/write_binded_presentation/#iorawiobase) | Écrit la présentation liée dans le flux. |
| [`write_binded_presentation(self, file)`](/slides/python-net/fr/aspose.slides/presentationinfo/write_binded_presentation/#str) | Écrit la présentation liée dans le fichier. |
| [`check_password(self, password)`](/slides/python-net/fr/aspose.slides/presentationinfo/check_password/#str) | Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe d'ouverture. |
| [`check_write_protection(self, password)`](/slides/python-net/fr/aspose.slides/presentationinfo/check_write_protection/#str) | Vérifie si le mot de passe de modification est correct pour une présentation protégée en écriture. |
| [`read_document_properties(self)`](/slides/python-net/fr/aspose.slides/presentationinfo/read_document_properties/#) | Obtient les propriétés du document de la présentation liée. |
| [`update_document_properties(self, document_properties)`](/slides/python-net/fr/aspose.slides/presentationinfo/update_document_properties/#idocumentproperties) | Met à jour les propriétés de la présentation liée. |


### Voir aussi
* module [`aspose.slides`](/slides/python-net/fr/aspose.slides)
* bibliothèque [`Aspose.Slides`](/slides/python-net)