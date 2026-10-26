---
title: PdfAccessPermissions
second_title: Aspose.Sildes pour PHP via la référence de l'API Java
description: 
type: docs

url: /fr/aspose.slides/pdfaccesspermissions/
---
## PdfAccessPermissions classe

Contient un ensemble de drapeaux spécifiant quelles autorisations d'accès doivent être accordées lorsque le document est ouvert avec l'accès utilisateur.

## Constantes

| Nom | Valeur | Description |
| --- | --- | --- |
[None](#None) | 0 | Spécifie qu'un utilisateur ne possède aucune autorisation d'accès. |
[PrintDocument](#PrintDocument) | 4 | Spécifie si un utilisateur peut imprimer le document (possiblement pas au niveau de qualité le plus élevé, selon que le bit PdfAccessPermissions#HighQualityPrint est également défini). |
[ModifyContent](#ModifyContent) | 8 | Spécifie si un utilisateur peut modifier le contenu du document par des opérations autres que celles contrôlées par les bits PdfAccessPermissions#AddOrModifyFields, PdfAccessPermissions#FillExistingFields, PdfAccessPermissions#AssembleDocument. |
[CopyTextAndGraphics](#CopyTextAndGraphics) | 16 | Spécifie si un utilisateur peut copier ou extraire autrement du texte et des graphiques du document par des opérations autres que celles contrôlées par le bit PdfAccessPermissions#ExtractTextAndGraphics. |
[AddOrModifyFields](#AddOrModifyFields) | 32 | Spécifie si un utilisateur peut ajouter ou modifier des annotations de texte, remplir des champs de formulaire interactifs, et, si le bit PdfAccessPermissions#ModifyContent est également défini, créer ou modifier des champs de formulaire interactifs (y compris les champs de signature). |
[FillExistingFields](#FillExistingFields) | 256 | Spécifie si un utilisateur peut remplir des champs de formulaire interactifs existants (y compris les champs de signature), même si le bit PdfAccessPermissions#AddOrModifyFields est désactivé. |
[ExtractTextAndGraphics](#ExtractTextAndGraphics) | 512 | Spécifie si un utilisateur peut extraire du texte et des graphiques afin de soutenir l'accessibilité pour les utilisateurs en situation de handicap ou à d'autres fins. |
[AssembleDocument](#AssembleDocument) | 1024 | Spécifie si un utilisateur peut assembler le document (insérer, pivoter ou supprimer des pages et créer des signets ou des miniatures), même si le bit PdfAccessPermissions#ModifyContent est désactivé. |
[HighQualityPrint](#HighQualityPrint) | 2048 | Spécifie si un utilisateur peut imprimer le document sous une représentation à partir de laquelle une copie numérique fidèle du contenu PDF pourrait être générée. Lorsque ce bit est désactivé (et que le bit PdfAccessPermissions#PrintDocument est défini), l'impression est limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée. |

---

### None {#None}
Spécifie qu'un utilisateur ne possède aucune autorisation d'accès.

---

### PrintDocument {#PrintDocument}
Spécifie si un utilisateur peut imprimer le document (possiblement pas au niveau de qualité le plus élevé, selon que le bit PdfAccessPermissions#HighQualityPrint est également défini).

---

### ModifyContent {#ModifyContent}
Spécifie si un utilisateur peut modifier le contenu du document par des opérations autres que celles contrôlées par les bits PdfAccessPermissions#AddOrModifyFields, PdfAccessPermissions#FillExistingFields, PdfAccessPermissions#AssembleDocument.

---

### CopyTextAndGraphics {#CopyTextAndGraphics}
Spécifie si un utilisateur peut copier ou extraire autrement du texte et des graphiques du document par des opérations autres que celles contrôlées par le bit PdfAccessPermissions#ExtractTextAndGraphics.

---

### AddOrModifyFields {#AddOrModifyFields}
Spécifie si un utilisateur peut ajouter ou modifier des annotations de texte, remplir des champs de formulaire interactifs, et, si le bit PdfAccessPermissions#ModifyContent est également défini, créer ou modifier des champs de formulaire interactifs (y compris les champs de signature).

---

### FillExistingFields {#FillExistingFields}
Spécifie si un utilisateur peut remplir des champs de formulaire interactifs existants (y compris les champs de signature), même si le bit PdfAccessPermissions#AddOrModifyFields est désactivé.

---

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
Spécifie si un utilisateur peut extraire du texte et des graphiques afin de soutenir l'accessibilité pour les utilisateurs en situation de handicap ou à d'autres fins.

---

### AssembleDocument {#AssembleDocument}
Spécifie si un utilisateur peut assembler le document (insérer, pivoter ou supprimer des pages et créer des signets ou des miniatures), même si le bit PdfAccessPermissions#ModifyContent est désactivé.

---

### HighQualityPrint {#HighQualityPrint}
Spécifie si un utilisateur peut imprimer le document sous une représentation à partir de laquelle une copie numérique fidèle du contenu PDF pourrait être générée. Lorsque ce bit est désactivé (et que le bit PdfAccessPermissions#PrintDocument est défini), l'impression est limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée.

---