---
title: ProtectionManager
second_title: Référence API Aspose.Slides pour Java
description: Gestion de la protection par mot de passe des présentations.
type: docs
url: /fr/com.aspose.slides/protectionmanager/
---
**Héritage :**
java.lang.Object

**Toutes les interfaces implémentées :**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Gestion de la protection par mot de passe des présentations.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Cette propriété a du sens si la présentation est protégée par mot de passe. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Cette propriété a du sens si la présentation est protégée par mot de passe. |
| [isEncrypted()](#isEncrypted--) | Obtient une valeur indiquant si cette instance est chiffrée. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Cette propriété a du sens si le fichier de présentation est protégé par mot de passe et les propriétés du document de ce fichier sont publiques. |
| [isWriteProtected()](#isWriteProtected--) | Obtient une valeur indiquant si cette présentation est protégée contre l'écriture. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Chiffre la présentation avec le mot de passe spécifié. |
| [removeEncryption()](#removeEncryption--) | Supprime le chiffrement. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Définit la protection en écriture pour cette présentation avec le mot de passe spécifié. |
| [removeWriteProtection()](#removeWriteProtection--) | Supprime la protection en écriture pour cette présentation. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Détermine si une présentation est protégée par mot de passe pour la modification. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Obtient le mot de passe utilisé pour le chiffrement de la présentation. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Obtient ou définit la recommandation en lecture seule. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Obtient ou définit la recommandation en lecture seule. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Cette propriété a du sens si la présentation est protégée par mot de passe. Si vrai, les propriétés du document sont chiffrées dans le fichier de présentation. Si faux, les propriétés du document sont publiques tandis que la présentation est chiffrée. Booléen lecture/écriture.

**Retourne :**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Cette propriété a du sens si la présentation est protégée par mot de passe. Si vrai, les propriétés du document sont chiffrées dans le fichier de présentation. Si faux, les propriétés du document sont publiques tandis que la présentation est chiffrée. Booléen lecture/écriture.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Obtient une valeur indiquant si cette instance est chiffrée. Booléen lecture seule.

Valeur : true if presentation was loaded from encrypted file or \#encrypt(String).encrypt(String) method was called ; otherwise, false.

**Retourne :**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Cette propriété a du sens si le fichier de présentation est protégé par mot de passe et les propriétés du document de ce fichier sont publiques. La valeur true signifie que seules les propriétés du document sont chargées depuis un fichier de présentation chiffré sans utilisation du mot de passe. La valeur false signifie que l’ensemble de la présentation chiffrée est chargé avec le bon mot de passe, et non seulement les propriétés du document. Si la présentation n’est pas chiffrée, la valeur de la propriété est toujours false. Si les propriétés du document d’un fichier chiffré ne sont pas publiques, la valeur de la propriété est toujours false. Si Presentation.EncryptDocumentProperties est true, alors la valeur de IsOnlyDocumentPropertiesLoaded est toujours false. Booléen lecture seule.

**Retourne :**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Obtient une valeur indiquant si cette présentation est protégée contre l'écriture. Booléen lecture seule.

**Retourne :**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Chiffre la présentation avec le mot de passe spécifié.

--------------------

> ```
> The following sample code shows you how to encrypt a PowerPoint Presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Le mot de passe. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

Supprime le chiffrement.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Définit la protection en écriture pour cette présentation avec le mot de passe spécifié.

--------------------

> ```
> Le code d'exemple suivant montre comment appliquer une protection en écriture à une présentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Le mot de passe. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Supprime la protection en écriture pour cette présentation.

--------------------

> ```
> Ce code d'exemple montre comment supprimer la protection en écriture d'une présentation PowerPoint.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().removeWriteProtection();
>      pres.save("write-protection-removed.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Détermine si une présentation est protégée par mot de passe pour la modification.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Le mot de passe à vérifier. |
1. Vous devez vérifier la propriété (\#isWriteProtected.isWriteProtected) avant d'appeler cette méthode. 2. Lorsque le mot de passe est null ou vide, cette méthode renvoie false. |

**Retourne :**
booléen - Vrai si le mot de passe est valide ; sinon, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Obtient le mot de passe utilisé pour le chiffrement de la présentation. Chaîne lecture seule.

**Retourne :**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Obtient ou définit la recommandation en lecture seule. Booléen lecture/écriture.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Retourne :**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

Obtient ou définit la recommandation en lecture seule. Booléen lecture/écriture.

--------------------

> ```
> Presentation pres = new Presentation();
>  try {
>      pres.getProtectionManager().setReadOnlyRecommended(true);
>      pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |