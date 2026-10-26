---
title: PdfAccessPermissions
second_title: Référence de l'API Aspose.Slides pour Java
description: Contient un ensemble de drapeaux indiquant quelles autorisations d'accès doivent être accordées lorsque le document est ouvert avec un accès utilisateur.
type: docs
url: /fr/com.aspose.slides/pdfaccesspermissions/
---
**Héritage:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class PdfAccessPermissions extends System.Enum
```

Contient un ensemble de drapeaux indiquant les autorisations d'accès qui doivent être accordées lorsque le document est ouvert avec un accès utilisateur.
## Champs

| Champ | Description |
| --- | --- |
| [None](#None) | Spécifie qu'un utilisateur ne possède pas d'autorisations d'accès. |
| [PrintDocument](#PrintDocument) | Indique si un utilisateur peut imprimer le document (éventuellement pas à la meilleure qualité, selon que le bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) est également défini). |
| [ModifyContent](#ModifyContent) | Indique si un utilisateur peut modifier le contenu du document par des opérations autres que celles contrôlées par les bits [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument). |
| [CopyTextAndGraphics](#CopyTextAndGraphics) | Indique si un utilisateur peut copier ou extraire le texte et les graphiques du document par des opérations autres que celle contrôlée par le bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics). |
| [AddOrModifyFields](#AddOrModifyFields) | Indique si un utilisateur peut ajouter ou modifier des annotations de texte, remplir des champs de formulaire interactifs et, si le bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) est également défini, créer ou modifier des champs de formulaire interactifs (y compris les champs de signature). |
| [FillExistingFields](#FillExistingFields) | Indique si un utilisateur peut remplir les champs de formulaire interactifs existants (y compris les champs de signature), même si le bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) est désactivé. |
| [ExtractTextAndGraphics](#ExtractTextAndGraphics) | Indique si un utilisateur peut extraire le texte et les graphiques à des fins d'accessibilité pour les utilisateurs handicapés ou à d'autres fins. |
| [AssembleDocument](#AssembleDocument) | Indique si un utilisateur peut assembler le document (insérer, faire pivoter ou supprimer des pages et créer des signets ou des images miniatures), même si le bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) est désactivé. |
| [HighQualityPrint](#HighQualityPrint) | Indique si un utilisateur peut imprimer le document vers une représentation à partir de laquelle une copie numérique fidèle du contenu PDF pourrait être générée. |
### None {#None}
```
public static final int None
```

Spécifie qu'un utilisateur ne possède pas d'autorisations d'accès.

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

Indique si un utilisateur peut imprimer le document (éventuellement pas à la meilleure qualité, selon que le bit [HighQualityPrint](../../com.aspose.slides/pdfaccesspermissions\#HighQualityPrint) est également défini).

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Indique si un utilisateur peut modifier le contenu du document par des opérations autres que celles contrôlées par les bits [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields), [FillExistingFields](../../com.aspose.slides/pdfaccesspermissions\#FillExistingFields), [AssembleDocument](../../com.aspose.slides/pdfaccesspermissions\#AssembleDocument).

### CopyTextAndGraphics {#CopyTextAndGraphics}
```
public static final int CopyTextAndGraphics
```

Indique si un utilisateur peut copier ou extraire le texte et les graphiques du document par des opérations autres que celle contrôlée par le bit [ExtractTextAndGraphics](../../com.aspose.slides/pdfaccesspermissions\#ExtractTextAndGraphics).

### AddOrModifyFields {#AddOrModifyFields}
```
public static final int AddOrModifyFields
```

Indique si un utilisateur peut ajouter ou modifier des annotations de texte, remplir des champs de formulaire interactifs et, si le bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) est également défini, créer ou modifier des champs de formulaire interactifs (y compris les champs de signature).

### FillExistingFields {#FillExistingFields}
```
public static final int FillExistingFields
```

Indique si un utilisateur peut remplir les champs de formulaire interactifs existants (y compris les champs de signature), même si le bit [AddOrModifyFields](../../com.aspose.slides/pdfaccesspermissions\#AddOrModifyFields) est désactivé.

### ExtractTextAndGraphics {#ExtractTextAndGraphics}
```
public static final int ExtractTextAndGraphics
```

Indique si un utilisateur peut extraire le texte et les graphiques à des fins d'accessibilité pour les utilisateurs handicapés ou à d'autres fins.

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

Indique si un utilisateur peut assembler le document (insérer, faire pivoter ou supprimer des pages et créer des signets ou des images miniatures), même si le bit [ModifyContent](../../com.aspose.slides/pdfaccesspermissions\#ModifyContent) est désactivé.

### HighQualityPrint {#HighQualityPrint}
```
public static final int HighQualityPrint
```

Indique si un utilisateur peut imprimer le document vers une représentation à partir de laquelle une copie numérique fidèle du contenu PDF pourrait être générée. Lorsque ce bit est désactivé (et que le bit [PrintDocument](../../com.aspose.slides/pdfaccesspermissions\#PrintDocument) est défini), l'impression est limitée à une représentation de bas niveau de l'apparence, éventuellement de qualité dégradée.