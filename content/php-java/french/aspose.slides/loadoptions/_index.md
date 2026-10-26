---
title: LoadOptions
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs
url: /fr/aspose.slides/loadoptions/
---
## LoadOptions classe

Permet de spécifier des options supplémentaires (telles que le format ou la police par défaut) lors du chargement d'une présentation.

### LoadOptions {#LoadOptions}

| Nom | Description |
| --- | --- |
| LoadOptions() | Crée de nouvelles options de chargement par défaut. |

**Retourne :**
LoadOptions

---

### LoadOptions {#LoadOptions}

| Nom | Description |
| --- | --- |
| LoadOptions(int) | Crée de nouvelles options de chargement. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| loadFormat | int | Format d'une présentation à charger. |

**Retourne :**
LoadOptions

---

### getBlobManagementOptions {#getBlobManagementOptions}

| Nom | Description |
| --- | --- |
| getBlobManagementOptions () | Représente les options qui peuvent être utilisées pour gérer le comportement de manipulation des Binary Large Objects (BLOBs), comme l'utilisation de fichiers temporaires ou le nombre maximal d'octets BLOBs en mémoire. Ces options sont destinées à définir le meilleur ratio performance/consommation de mémoire pour un environnement ou des exigences particulières. Un Binary Large Object (BLOB) est une donnée binaire stockée comme une entité unique ; par exemple, un BLOB peut être un audio, une vidéo ou la présentation elle-même. |

**Retourne :**
[BlobManagementOptions](../blobmanagementoptions)

---

### getDefaultAsianFont {#getDefaultAsianFont}

| Nom | Description |
| --- | --- |
| getDefaultAsianFont () | Retourne ou définit la police asiatique utilisée lorsque la police source n'est pas trouvée. Lecture/écriture String. |

**Retourne :**
String

---

### getDefaultRegularFont {#getDefaultRegularFont}

| Nom | Description |
| --- | --- |
| getDefaultRegularFont () | Retourne ou définit la police régulière utilisée lorsque la police source n'est pas trouvée. Lecture/écriture String. |

**Retourne :**
String

---

### getDefaultSymbolFont {#getDefaultSymbolFont}

| Nom | Description |
| --- | --- |
| getDefaultSymbolFont () | Retourne ou définit la police symbole utilisée lorsque la police source n'est pas trouvée. Lecture/écriture String. |

**Retourne :**
String

---

### getDefaultTextLanguage {#getDefaultTextLanguage}

| Nom | Description |
| --- | --- |
| getDefaultTextLanguage () | Retourne ou définit la langue par défaut pour le texte de la présentation. Lecture/écriture String. |

**Retourne :**
String

---

### getDeleteEmbeddedBinaryObjects {#getDeleteEmbeddedBinaryObjects}

| Nom | Description |
| --- | --- |
| getDeleteEmbeddedBinaryObjects () | Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation. Types des objets binaires incorporés : Lecture/écriture boolean. La valeur par défaut est false. |

**Retourne :**
boolean

---

### getDocumentLevelFontSources {#getDocumentLevelFontSources}

| Nom | Description |
| --- | --- |
| getDocumentLevelFontSources () | Spécifie les sources des polices externes à utiliser par la présentation. Ces polices sont disponibles pendant toute la durée de vie de la présentation et ne sont pas partagées avec d'autres présentations. |

**Retourne :**
[FontSources](../fontsources)

---

### getInterruptionToken {#getInterruptionToken}

| Nom | Description |
| --- | --- |
| getInterruptionToken () | Le jeton permettant de surveiller les demandes d'interruption. Ce jeton gère la durée de vie complète de l'instance IPresentation. Toute opération longue, comme le chargement ou la sauvegarde d'une présentation, sera interrompue en appelant la méthode InterruptionTokenSource#interrupt du InterruptionTokenSource. |

**Retourne :**
[InterruptionToken](../interruptiontoken)

---

### getLoadFormat {#getLoadFormat}

| Nom | Description |
| --- | --- |
| getLoadFormat () | Retourne ou définit le format d'une présentation à charger. Lecture/écriture LoadFormat. |

**Retourne :**
int

---

### getOnlyLoadDocumentProperties {#getOnlyLoadDocumentProperties}

| Nom | Description |
| --- | --- |
| getOnlyLoadDocumentProperties () | Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe. La valeur true signifie que seules les propriétés du document doivent être chargées à partir d'un fichier de présentation chiffré et que le mot de passe doit être ignoré. La valeur false signifie que l'intégralité de la présentation chiffrée doit être chargée en utilisant le bon mot de passe. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d'un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, les propriétés du document ne peuvent pas être chargées et une exception sera levée. Lecture/écriture boolean. |

**Retourne :**
boolean

---

### getPassword {#getPassword}

| Nom | Description |
| --- | --- |
| getPassword () | Obtient ou définit le mot de passe. Lecture/écriture String. Valeur : le mot de passe. |

**Retourne :**
String

---

### getResourceLoadingCallback {#getResourceLoadingCallback}

| Nom | Description |
| --- | --- |
| getResourceLoadingCallback () | Retourne ou définit l'interface de rappel qui gère le chargement des ressources externes. Lecture/écriture IResourceLoadingCallback. |

**Retourne :**
SvgResourceResolver, ResourceLoadingAdapter

---

### getSpreadsheetOptions {#getSpreadsheetOptions}

| Nom | Description |
| --- | --- |
| getSpreadsheetOptions () | Obtient les options pour les feuilles de calcul. Par exemple, ces options influent sur le calcul des formules pour les graphiques. |

**Retourne :**
[SpreadsheetOptions](../spreadsheetoptions)

---

### getWarningCallback {#getWarningCallback}

| Nom | Description |
| --- | --- |
| getWarningCallback () | Retourne ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être interrompu. Lecture/écriture IWarningCallback. |

**Retourne :**
IWarningCallback

---

### setBlobManagementOptions {#setBlobManagementOptions}

| Nom | Description |
| --- | --- |
| setBlobManagementOptions ([BlobManagementOptions](../blobmanagementoptions)) | Représente les options qui peuvent être utilisées pour gérer le comportement de manipulation des Binary Large Objects (BLOBs), comme l'utilisation de fichiers temporaires ou le nombre maximal d'octets BLOBs en mémoire. Ces options sont destinées à définir le meilleur ratio performance/consommation de mémoire pour un environnement ou des exigences particulières. Un Binary Large Object (BLOB) est une donnée binaire stockée comme une entité unique ; par exemple, un BLOB peut être un audio, une vidéo ou la présentation elle-même. |

**Retourne :**
void

---

### setDefaultAsianFont {#setDefaultAsianFont}

| Nom | Description |
| --- | --- |
| setDefaultAsianFont (String) | Retourne ou définit la police asiatique utilisée lorsque la police source n'est pas trouvée. Lecture/écriture String. |

**Retourne :**
void

---

### setDefaultRegularFont {#setDefaultRegularFont}

| Nom | Description |
| --- | --- |
| setDefaultRegularFont (String) | Retourne ou définit la police régulière utilisée lorsque la police source n'est pas trouvée. Lecture/écriture String. |

**Retourne :**
void

---

### setDefaultSymbolFont {#setDefaultSymbolFont}

| Nom | Description |
| --- | --- |
| setDefaultSymbolFont (String) | Retourne ou définit la police symbole utilisée lorsque la police source n'est pas trouvée. Lecture/écriture String. |

**Retourne :**
void

---

### setDefaultTextLanguage {#setDefaultTextLanguage}

| Nom | Description |
| --- | --- |
| setDefaultTextLanguage (String) | Retourne ou définit la langue par défaut pour le texte de la présentation. Lecture/écriture String. |

**Retourne :**
void

---

### setDeleteEmbeddedBinaryObjects {#setDeleteEmbeddedBinaryObjects}

| Nom | Description |
| --- | --- |
| setDeleteEmbeddedBinaryObjects (boolean) | Détermine si Aspose.Slides supprimera tous les objets binaires incorporés lors du chargement de la présentation. Types des objets binaires incorporés : Lecture/écriture boolean. La valeur par défaut est false. |

**Retourne :**
void

---

### setDocumentLevelFontSources {#setDocumentLevelFontSources}

| Nom | Description |
| --- | --- |
| setDocumentLevelFontSources ([FontSources](../fontsources)) | Spécifie les sources des polices externes à utiliser par la présentation. Ces polices sont disponibles pendant toute la durée de vie de la présentation et ne sont pas partagées avec d'autres présentations. |

**Retourne :**
void

---

### setInterruptionToken {#setInterruptionToken}

| Nom | Description |
| --- | --- |
| setInterruptionToken ([InterruptionToken](../interruptiontoken)) | Le jeton permettant de surveiller les demandes d'interruption. Ce jeton gère la durée de vie complète de l'instance IPresentation. Toute opération longue, comme le chargement ou la sauvegarde d'une présentation, sera interrompue en appelant la méthode InterruptionTokenSource#interrupt du InterruptionTokenSource. |

**Retourne :**
void

---

### setLoadFormat {#setLoadFormat}

| Nom | Description |
| --- | --- |
| setLoadFormat (int) | Retourne ou définit le format d'une présentation à charger. Lecture/écriture LoadFormat. |

**Retourne :**
void

---

### setOnlyLoadDocumentProperties {#setOnlyLoadDocumentProperties}

| Nom | Description |
| --- | --- |
| setOnlyLoadDocumentProperties (boolean) | Cette propriété a du sens si le fichier de présentation est protégé par un mot de passe. La valeur true signifie que seules les propriétés du document doivent être chargées à partir d'un fichier de présentation chiffré et que le mot de passe doit être ignoré. La valeur false signifie que l'intégralité de la présentation chiffrée doit être chargée en utilisant le bon mot de passe. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours ignorée. Si les propriétés du document d'un fichier chiffré ne sont pas publiques et que la valeur de la propriété est true, les propriétés du document ne peuvent pas être chargées et une exception sera levée. Lecture/écriture boolean. |

**Retourne :**
void

---

### setPassword {#setPassword}

| Nom | Description |
| --- | --- |
| setPassword (String) | Obtient ou définit le mot de passe. Lecture/écriture String. Valeur : le mot de passe. |

**Retourne :**
void

---

### setResourceLoadingCallback {#setResourceLoadingCallback}

| Nom | Description |
| --- | --- |
| setResourceLoadingCallback ([IResourceLoadingCallback](../iresourceloadingcallback)) | Retourne ou définit l'interface de rappel qui gère le chargement des ressources externes. Lecture/écriture IResourceLoadingCallback. |

**Retourne :**
void

---

### setSpreadsheetOptions {#setSpreadsheetOptions}

| Nom | Description |
| --- | --- |
| setSpreadsheetOptions ([SpreadsheetOptions](../spreadsheetoptions)) | Obtient les options pour les feuilles de calcul. Par exemple, ces options influent sur le calcul des formules pour les graphiques. |

**Retourne :**
void

---

### setWarningCallback {#setWarningCallback}

| Nom | Description |
| --- | --- |
| setWarningCallback ([IWarningCallback](../iwarningcallback)) | Retourne ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être interrompu. Lecture/écriture IWarningCallback. |

**Retourne :**
void

---