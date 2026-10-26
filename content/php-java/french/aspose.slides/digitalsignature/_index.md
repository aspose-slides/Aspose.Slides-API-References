---
title: DigitalSignature
second_title: Aspose.Sildes pour PHP via Référence d'API Java
description: 
type: docs

url: /fr/aspose.slides/digitalsignature/
---
## classe DigitalSignature

 Signature numérique dans le fichier signé.

### DigitalSignature {#DigitalSignature}

| Name | Description |
| --- | --- |
| DigitalSignature(byte[], String) | Crée un nouvel objet DigitalSignature avec le certificat spécifié. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| certData | byte[] | un tableau d'octets contenant le certificat |
| password | String | Mot de passe requis pour accéder au certificat. |

**Retour :**
DigitalSignature

---

### DigitalSignature {#DigitalSignature}

| Name | Description |
| --- | --- |
| DigitalSignature(String, String) | Crée un nouvel objet DigitalSignature avec le chemin du fichier de certificat spécifié et le mot de passe. |

**Paramètres :**

| Name | Type | Description |
| --- | --- | --- |
| filePath | String | Chemin du fichier contenant le certificat. |
| password | String | Mot de passe requis pour accéder au certificat. |

**Retour :**
DigitalSignature

---

### getCertificate {#getCertificate}

| Name | Description |
| --- | --- |
| getCertificate () | Objet Certificate utilisé pour signer le document. Lecture seule byte[]. |

**Retour :**
byte

---

### getComments {#getComments}

| Name | Description |
| --- | --- |
| getComments () | Le but de la signature. Lecture/écriture String. |

**Retour :**
String

---

### getSignTime {#getSignTime}

| Name | Description |
| --- | --- |
| getSignTime () | L'heure à laquelle le document a été signé. Lecture seule java.util.Date. |

**Retour :**
Date

---

### isValid {#isValid}

| Name | Description |
| --- | --- |
| isValid () | Si cette signature numérique est valide et que le document n'a pas été altéré, cette valeur sera vraie. Lecture seule boolean. |

**Retour :**
boolean

---

### setComments {#setComments}

| Name | Description |
| --- | --- |
| setComments (String) | Le but de la signature. Lecture/écriture String. |

**Retour :**
void

---