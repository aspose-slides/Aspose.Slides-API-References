---
title: ProtectionManager
second_title: Référence API Java via Aspose.Slides pour PHP
description: 
type: docs

url: /fr/aspose.slides/protectionmanager/
---
## ProtectionManager classe

Gestion de la protection par mot de passe d'une présentation.

### checkWriteProtection {#checkWriteProtection}

| Nom | Description |
| --- | --- |
| checkWriteProtection (String) | Détermine si une présentation est protégée par un mot de passe pour la modification. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| password | String | Le mot de passe pour la vérification. 1. Vous devez vérifier la propriété ( #isWriteProtected) avant d'appeler cette méthode. 2. Lorsque le mot de passe est nul ou vide, cette méthode renvoie false. |

**Retour :**
boolean


---

### encrypt {#encrypt}

| Nom | Description |
| --- | --- |
| encrypt (String) | Crypte la présentation avec le mot de passe spécifié. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| encryptionPassword | String | Le mot de passe. |

**Retour :**
void


---

### getEncryptDocumentProperties {#getEncryptDocumentProperties}

| Nom | Description |
| --- | --- |
| getEncryptDocumentProperties () | Cette propriété a un sens si la présentation est protégée par un mot de passe. Si true, les propriétés du document sont chiffrées dans le fichier de présentation. Si false, les propriétés du document sont publiques tandis que la présentation est chiffrée. Booléen lecture/écriture. |

**Retour :**
boolean


---

### getEncryptionPassword {#getEncryptionPassword}

| Nom | Description |
| --- | --- |
| getEncryptionPassword () | Obtient le mot de passe utilisé pour le chiffrement de la présentation. String en lecture seule. |

**Retour :**
String


---

### getReadOnlyRecommended {#getReadOnlyRecommended}

| Nom | Description |
| --- | --- |
| getReadOnlyRecommended () | Obtient ou définit la recommandation en lecture seule. Booléen lecture/écriture. |

**Retour :**
boolean


---

### isEncrypted {#isEncrypted}

| Nom | Description |
| --- | --- |
| isEncrypted () | Obtient une valeur indiquant si cette instance est chiffrée. Booléen en lecture seule. Valeur : true si la présentation a été chargée depuis un fichier chiffré ou si la méthode #encrypt(String) a été appelée ; sinon, false. |

**Retour :**
boolean


---

### isOnlyDocumentPropertiesLoaded {#isOnlyDocumentPropertiesLoaded}

| Nom | Description |
| --- | --- |
| isOnlyDocumentPropertiesLoaded () | Cette propriété a un sens si le fichier de présentation est protégé par mot de passe et que les propriétés du document de ce fichier sont publiques. La valeur true signifie que seules les propriétés du document sont chargées depuis un fichier de présentation chiffré sans utilisation du mot de passe. La valeur false signifie que toute la présentation chiffrée est chargée avec le bon mot de passe, pas seulement les propriétés du document. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours false. Si les propriétés du document d'un fichier chiffré ne sont pas publiques, la valeur de la propriété est toujours false. Si Presentation.EncryptDocumentProperties est true alors la valeur de la propriété IsOnlyDocumentPropertiesLoaded est toujours false. Booléen en lecture seule. |

**Retour :**
boolean


---

### isWriteProtected {#isWriteProtected}

| Nom | Description |
| --- | --- |
| isWriteProtected () | Obtient une valeur indiquant si cette présentation est protégée contre l'écriture. Booléen en lecture seule. |

**Retour :**
boolean


---

### removeEncryption {#removeEncryption}

| Nom | Description |
| --- | --- |
| removeEncryption () | Supprime le chiffrement. |

**Retour :**
void


---

### removeWriteProtection {#removeWriteProtection}

| Nom | Description |
| --- | --- |
| removeWriteProtection () | Supprime la protection en écriture pour cette présentation. |

**Retour :**
void


---

### setEncryptDocumentProperties {#setEncryptDocumentProperties}

| Nom | Description |
| --- | --- |
| setEncryptDocumentProperties (boolean) | Cette propriété a un sens si la présentation est protégée par mot de passe. Si true alors les propriétés du document sont chiffrées dans le fichier de présentation. Si false alors les propriétés du document sont publiques tandis que la présentation est chiffrée. Booléen lecture/écriture. |

**Retour :**
void


---

### setReadOnlyRecommended {#setReadOnlyRecommended}

| Nom | Description |
| --- | --- |
| setReadOnlyRecommended (boolean) | Obtient ou définit la recommandation en lecture seule. Booléen lecture/écriture. |

**Retour :**
void


---

### setWriteProtection {#setWriteProtection}

| Nom | Description |
| --- | --- |
| setWriteProtection (String) | Définit la protection en écriture pour cette présentation avec le mot de passe spécifié. |

**Paramètres :**

| Nom | Type | Description |
| --- | --- | --- |
| password | String | Le mot de passe. |

**Retour :**
void


---