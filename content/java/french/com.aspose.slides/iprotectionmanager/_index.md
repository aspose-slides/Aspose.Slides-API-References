---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: Gestion de la protection par mot de passe des présentations.
type: docs
url: /fr/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Gestion de la protection par mot de passe des présentations.
## Méthodes

| Méthode | Description |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Cette propriété a du sens si la présentation est protégée par mot de passe. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Cette propriété a du sens si la présentation est protégée par mot de passe. |
| [isEncrypted()](#isEncrypted--) | Obtient une valeur indiquant si cette instance est chiffrée. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Cette propriété a du sens si le fichier de présentation est protégé par mot de passe et que les propriétés du document de ce fichier sont publiques. |
| [isWriteProtected()](#isWriteProtected--) | Obtient une valeur indiquant si cette présentation est protégée en écriture. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Renvoie le mot de passe de chiffrement. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Obtient ou définit la recommandation en lecture seule. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Obtient ou définit la recommandation en lecture seule. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Crypte la présentation avec le mot de passe spécifié. |
| [removeEncryption()](#removeEncryption--) | Supprime le chiffrement. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Définit la protection en écriture pour cette présentation avec le mot de passe spécifié. |
| [removeWriteProtection()](#removeWriteProtection--) | Supprime la protection en écriture pour cette présentation. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Détermine si une présentation est protégée par mot de passe pour être modifiée. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Cette propriété a du sens si la présentation est protégée par mot de passe. Si vrai, les propriétés du document sont chiffrées dans le fichier de présentation. Si faux, les propriétés du document sont publiques tandis que la présentation est chiffrée. Booléen en lecture/écriture.

**Renvoie:**  
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Cette propriété a du sens si la présentation est protégée par mot de passe. Si vrai, les propriétés du document sont chiffrées dans le fichier de présentation. Si faux, les propriétés du document sont publiques tandis que la présentation est chiffrée. Booléen en lecture/écriture.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Obtient une valeur indiquant si cette instance est chiffrée. Booléen en lecture seule.

Valeur : true si la présentation a été chargée à partir d'un fichier chiffré ou si la méthode \#encrypt(String).encrypt(String) a été appelée ; sinon, false.

**Renvoie:**  
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Cette propriété a du sens si le fichier de présentation est protégé par mot de passe et que les propriétés du document de ce fichier sont publiques. La valeur true signifie que seules les propriétés du document sont chargées à partir d'un fichier de présentation chiffré sans utilisation de mot de passe. La valeur false signifie que l'ensemble de la présentation chiffrée est chargé avec le bon mot de passe, pas seulement les propriétés du document. Si la présentation n'est pas chiffrée, la valeur de la propriété est toujours false. Si les propriétés du document d'un fichier chiffré ne sont pas publiques, la valeur de la propriété est toujours false. Si PresentationEx.EncryptDocumentProperties est true alors la valeur de la propriété IsOnlyDocumentPropertiesLoaded est toujours false. Booléen en lecture seule.

**Renvoie:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Obtient une valeur indiquant si cette présentation est protégée en écriture. Booléen en lecture seule.

**Renvoie:**  
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Renvoie le mot de passe de chiffrement. Chaîne en lecture seule.

**Renvoie:**  
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Obtient ou définit la recommandation en lecture seule. Booléen en lecture/écriture.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Renvoie:**  
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Obtient ou définit la recommandation en lecture seule. Booléen en lecture/écriture.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| value | boolean |  |
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Crypte la présentation avec le mot de passe spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Le mot de passe. |
### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Supprime le chiffrement.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Définit la protection en écriture pour cette présentation avec le mot de passe spécifié.

**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Le mot de passe. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Supprime la protection en écriture pour cette présentation.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Détermine si une présentation est protégée par mot de passe pour être modifiée.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paramètres:**
| Paramètre | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Le mot de passe à vérifier.

--------------------

1. Vous devez vérifier la propriété (\#isWriteProtected.isWriteProtected) avant d'appeler cette méthode. 2. Lorsque le mot de passe est nul ou vide, cette méthode renvoie false.

**Renvoie:**  
boolean - True si le mot de passe est valide ; sinon, false.