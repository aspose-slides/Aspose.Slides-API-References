---
title: SaveOptions
second_title: Aspose.Sildes pour PHP via Référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/saveoptions/
---
## classe SaveOptions

 Classe abstraite avec des options qui contrôlent la façon dont une présentation est enregistrée.

### SaveOptions {#SaveOptions}

| Name | Description |
| --- | --- |
| SaveOptions() |  |

**Renvoie :**
SaveOptions

---

### getDefaultRegularFont {#getDefaultRegularFont}

| Name | Description |
| --- | --- |
| getDefaultRegularFont () | Renvoie ou définit la police utilisée si la police source n'est pas trouvée. Lecture/écriture String. |

**Renvoie :**
String

---

### getGradientStyle {#getGradientStyle}

| Name | Description |
| --- | --- |
| getGradientStyle () | Renvoie ou définit le style visuel du dégradé. Lecture/écriture GradientStyle. |

**Renvoie :**
int

---

### getProgressCallback {#getProgressCallback}

| Name | Description |
| --- | --- |
| getProgressCallback () | Représente un objet de rappel pour les mises à jour de progression de l'enregistrement en pourcentage. Voir IProgressCallback. |

**Renvoie :**
IProgressCallback

---

### getSkipJavaScriptLinks {#getSkipJavaScriptLinks}

| Name | Description |
| --- | --- |
| getSkipJavaScriptLinks () | Spécifie s’il faut ignorer les hyperliens contenant des appels JavaScript lors de l’enregistrement de la présentation. Lecture/écriture boolean. La valeur par défaut est false. Lorsque cette propriété est définie sur true, les hyperliens contenant des appels JavaScript seront ignorés lors de l’enregistrement. Lorsque cette propriété est définie sur false, tous les hyperliens seront enregistrés. |

**Renvoie :**
boolean

---

### getWarningCallback {#getWarningCallback}

| Name | Description |
| --- | --- |
| getWarningCallback () | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être interrompu. Lecture/écriture IWarningCallback. |

**Renvoie :**
IWarningCallback

---

### setDefaultRegularFont {#setDefaultRegularFont}

| Name | Description |
| --- | --- |
| setDefaultRegularFont (String) | Renvoie ou définit la police utilisée si la police source n'est pas trouvée. Lecture/écriture String. |

**Renvoie :**
void

---

### setGradientStyle {#setGradientStyle}

| Name | Description |
| --- | --- |
| setGradientStyle (int) | Renvoie ou définit le style visuel du dégradé. Lecture/écriture GradientStyle. |

**Renvoie :**
void

---

### setProgressCallback {#setProgressCallback}

| Name | Description |
| --- | --- |
| setProgressCallback ([IProgressCallback](../iprogresscallback)) | Représente un objet de rappel pour les mises à jour de progression de l'enregistrement en pourcentage. Voir IProgressCallback. |

**Renvoie :**
void

---

### setSkipJavaScriptLinks {#setSkipJavaScriptLinks}

| Name | Description |
| --- | --- |
| setSkipJavaScriptLinks (boolean) | Spécifie s’il faut ignorer les hyperliens contenant des appels JavaScript lors de l’enregistrement de la présentation. Lecture/écriture boolean. La valeur par défaut est false. Lorsque cette propriété est définie sur true, les hyperliens contenant des appels JavaScript seront ignorés lors de l’enregistrement. Lorsque cette propriété est définie sur false, tous les hyperliens seront enregistrés. |

**Renvoie :**
void

---

### setWarningCallback {#setWarningCallback}

| Name | Description |
| --- | --- |
| setWarningCallback ([IWarningCallback](../iwarningcallback)) | Renvoie ou définit un objet qui reçoit les avertissements et décide si le processus de chargement doit se poursuivre ou être interrompu. Lecture/écriture IWarningCallback. |

**Renvoie :**
void

---