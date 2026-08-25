---
title: PresentationInfo
second_title: Aspose.Sildes pour PHP via la référence API Java
description: 
type: docs

url: /fr/aspose.slides/presentationinfo/
---
## PresentationInfo classe

 Informations sur le fichier de présentation
 
### checkPassword {#checkPassword}

| Name | Description |
| --- | --- |
| checkPassword (String) | Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe d'ouverture. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| password | String | Le mot de passe à vérifier. Lorsque le mot de passe est nul ou vide, cette méthode renvoie false. |

 **Retour:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | NotSupportedException | si le format ne prend pas en charge la vérification des mots de passe. |


---


### checkWriteProtection {#checkWriteProtection}

| Name | Description |
| --- | --- |
| checkWriteProtection (String) | Vérifie si un mot de passe de modification est correct pour une présentation protégée en écriture. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| password | String | Le mot de passe à vérifier. 1. Vous devez vérifier la propriété ( #isWriteProtected) avant d'appeler cette méthode. 2. Lorsque le mot de passe est nul ou vide, cette méthode renvoie false. |

 **Retour:**
boolean

 **Exception**

| Error | Condition |
| --- | --- |
 | InvalidOperationException | Si une présentation est protégée par un mot de passe d'ouverture ou si le format ne prend pas en charge la protection en écriture |


---


### getLoadFormat {#getLoadFormat}

| Name | Description |
| --- | --- |
| getLoadFormat () | Obtient le format de la présentation liée. Lecture seule LoadFormat. |

 **Retour:**
int


---


### isEncrypted {#isEncrypted}

| Name | Description |
| --- | --- |
| isEncrypted () | Renvoie True si la présentation liée est chiffrée, sinon False. Lecture seule booléen. |

 **Retour:**
boolean


---


### isPasswordProtected {#isPasswordProtected}

| Name | Description |
| --- | --- |
| isPasswordProtected () | Obtient une valeur qui indique si une présentation liée est protégée par un mot de passe d'ouverture. |

 **Retour:**
boolean


---


### isWriteProtected {#isWriteProtected}

| Name | Description |
| --- | --- |
| isWriteProtected () | Obtient une valeur qui indique si une présentation liée est protégée en écriture. Si la présentation est protégée par un mot de passe d'ouverture, la valeur de la propriété est égale à NotDefined. |

 **Retour:**
byte


---


### readDocumentProperties {#readDocumentProperties}

| Name | Description |
| --- | --- |
| readDocumentProperties () | Obtient les propriétés du document de la présentation liée. |

 **Retour:**
[DocumentProperties](../documentproperties)


---


### updateDocumentProperties {#updateDocumentProperties}

| Name | Description |
| --- | --- |
| updateDocumentProperties ([DocumentProperties](../documentproperties)) | Met à jour les propriétés de la présentation liée. |

 **Retour:**
void


---


### writeBindedPresentation {#writeBindedPresentation}

| Name | Description |
| --- | --- |
| writeBindedPresentation (OutputStream) | Écrit la présentation liée dans le flux. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| stream | OutputStream | Le flux doit être recherchable et inscriptible. |

 **Retour:**
void


---


### writeBindedPresentation {#writeBindedPresentation}

| Name | Description |
| --- | --- |
| writeBindedPresentation (String) | Écrit la présentation liée dans le fichier. |

 **Paramètres:**

| Name | Type | Description |
| --- | --- | --- |
| file | String | Fichier de présentation. |

 **Retour:**
void


---