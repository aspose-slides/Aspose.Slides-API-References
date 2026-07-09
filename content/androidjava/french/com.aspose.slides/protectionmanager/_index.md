---
title: ProtectionManager
second_title: "Référence de l'API Java d'Aspose.Slides pour Android"
description: "Gestion de la protection par mot de passe de la présentation."
type: docs
url: /fr/com.aspose.slides/protectionmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Gestion de la protection par mot de passe de la présentation.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Cette propriété a du sens si la présentation est protégée par mot de passe. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Cette propriété a du sens si la présentation est protégée par mot de passe. |
| [isEncrypted()](#isEncrypted--) | Obtient une valeur indiquant si cette instance est chiffrée. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Cette propriété a du sens si le fichier de présentation est protégé par mot de passe et que les propriétés du document de ce fichier sont publiques. |
| [isWriteProtected()](#isWriteProtected--) | Obtient une valeur indiquant si cette présentation est protégée en écriture. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Chiffre la présentation avec le mot de passe spécifié. |
| [removeEncryption()](#removeEncryption--) | Supprime le chiffrement. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Définit la protection en écriture pour cette présentation avec le mot de passe spécifié. |
| [removeWriteProtection()](#removeWriteProtection--) | Supprime la protection en écriture pour cette présentation. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Détermine si une présentation est protégée par mot de passe pour la modification. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Obtient le mot de passe utilisé pour le chiffrement de la présentation. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Obtient ou définit la recommandation de lecture seule. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Obtient ou définit la recommandation de lecture seule. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Cette propriété a du sens si la présentation est protégée par mot de passe. Si true alors les propriétés du document sont chiffrées dans le fichier de présentation. Si false alors les propriétés du document sont publiques tandis que la présentation est chiffrée. Lecture/écriture booléen.

**Retourne :**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Cette propriété a du sens si la présentation est protégée par mot de passe. Si true alors les propriétés du document sont chiffrées dans le fichier de présentation. Si false alors les propriétés du document sont publiques tandis que la présentation est chiffrée. Lecture/écriture booléen.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Obtient une valeur indiquant si cette instance est chiffrée. Lecture seule booléen.

Valeur : true si la présentation a été chargée à partir d'un fichier chiffré ou si la méthode #encrypt(String).encrypt(String) a été appelée ; sinon, false.

**Retourne :**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Cette propriété a du sens si le fichier de présentation est protégé par mot de passe et que les propriétés du document de ce fichier sont publiques. La valeur true signifie que seules les propriétés du document sont chargées depuis un fichier de présentation chiffré sans utilisation du mot de passe. La valeur false signifie que l'intégralité de la présentation chiffrée est chargée avec le bon mot de passe, pas seulement les propriétés du document. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours false. Si les propriétés du document d'un fichier chiffré ne sont pas publiques, la valeur de la propriété est toujours false. Si Presentation.EncryptDocumentProperties est true, alors la valeur de la propriété IsOnlyDocumentPropertiesLoaded est toujours false. Lecture seule booléen.

**Retourne :**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Obtient une valeur indiquant si cette présentation est protégée en écriture. Lecture seule booléen.

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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| encryptionPassword | java.lang.String | The password. |

### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

Supprime le chiffrement.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Set write protection for this presentation with specified password.

--------------------

> ```
> The following sample code shows you how to set a write protection to a presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password. |

### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Removes write protection for this presentation.

--------------------

> ```
> This sample code shows you how to remove the write protection from a PowerPoint Presentation.
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

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password for checking.

--------------------

1. Vous devez vérifier la propriété (\#isWriteProtected.isWriteProtected) avant d'appeler cette méthode. 2. Lorsque le mot de passe est nul ou vide, cette méthode renvoie false. |

**Returns:**
boolean - True if the password is valid; otherwise, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Obtient le mot de passe utilisé pour le chiffrement de la présentation. Lecture seule String.

**Returns:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Gets or sets read-only recommendation. Read/write boolean.

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

**Returns:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)

Gets or sets read-only recommendation. Read/write boolean.

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