---
title: PdfAccessPermissions enumeration
second_title: Aspose.Slides pour Python via .NET Référence de l'API
description: 
type: docs
url: /fr/aspose.slides.export/pdfaccesspermissions/
---
## énumération PdfAccessPermissions

Contient un ensemble de drapeaux spécifiant quelles autorisations d'accès doivent être accordées lorsque le document est ouvert avec accès utilisateur.

Le type PdfAccessPermissions expose les membres suivants :

## Champs

| Champ | Description |
| :- | :- |
| NONE | Spécifie qu'un utilisateur ne possède pas d'autorisations d'accès. |
| PRINT_DOCUMENT | Spécifie si un utilisateur peut imprimer le document (éventuellement pas au niveau de qualité le plus élevé, selon que le bit [`PdfAccessPermissions.HIGH_QUALITY_PRINT`](/slides/python-net/fr/aspose.slides.export/pdfaccesspermissions/HIGH_QUALITY_PRINT) soit également activé). |
| MODIFY_CONTENT | Spécifie si un utilisateur peut modifier le contenu du document par des opérations autres que celles contrôlées par les bits [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/fr/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS), [`PdfAccessPermissions.FILL_EXISTING_FIELDS`](/slides/python-net/fr/aspose.slides.export/pdfaccesspermissions/FILL_EXISTING_FIELDS), [`PdfAccessPermissions.ASSEMBLE_DOCUMENT`](/slides/python-net/fr/aspose.slides.export/pdfaccesspermissions/ASSEMBLE_DOCUMENT). |
| COPY_TEXT_AND_GRAPHICS | Spécifie si un utilisateur peut copier ou extraire autrement du texte et des graphiques du document par des opérations autres que celles contrôlées par le bit [`PdfAccessPermissions.EXTRACT_TEXT_AND_GRAPHICS`](/slides/python-net/fr/aspose.slides.export/pdfaccesspermissions/EXTRACT_TEXT_AND_GRAPHICS). |
| ADD_OR_MODIFY_FIELDS | Spécifie si un utilisateur peut ajouter ou modifier des annotations de texte, remplir des champs de formulaire interactifs, et, si le bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/fr/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) est également activé, créer ou modifier des champs de formulaire interactifs (y compris les champs de signature). |
| FILL_EXISTING_FIELDS | Spécifie si un utilisateur peut remplir des champs de formulaire interactifs existants (y compris les champs de signature), même si le bit [`PdfAccessPermissions.ADD_OR_MODIFY_FIELDS`](/slides/python-net/fr/aspose.slides.export/pdfaccesspermissions/ADD_OR_MODIFY_FIELDS) est désactivé. |
| EXTRACT_TEXT_AND_GRAPHICS | Spécifie si un utilisateur peut extraire du texte et des graphiques afin de soutenir l'accessibilité pour les utilisateurs handicapés ou à d'autres fins. |
| ASSEMBLE_DOCUMENT | Spécifie si un utilisateur peut assembler le document (insérer, faire pivoter ou supprimer des pages et créer des signets ou des miniatures), même si le bit [`PdfAccessPermissions.MODIFY_CONTENT`](/slides/python-net/fr/aspose.slides.export/pdfaccesspermissions/MODIFY_CONTENT) est désactivé. |
| HIGH_QUALITY_PRINT | Spécifie si un utilisateur peut imprimer le document à une représentation à partir de laquelle une copie numérique fidèle du contenu PDF pourrait être générée. Lorsque ce bit est désactivé (et que le bit [`PdfAccessPermissions.PRINT_DOCUMENT`](/slides/python-net/fr/aspose.slides.export/pdfaccesspermissions/PRINT_DOCUMENT) est activé),<br/> l'impression est limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée. |

### Voir également
* module [`aspose.slides.export`](/slides/python-net/fr/aspose.slides.export)
* bibliothèque [`Aspose.Slides`](/slides/python-net)