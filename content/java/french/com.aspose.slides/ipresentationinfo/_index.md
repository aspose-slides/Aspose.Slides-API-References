---
title: IPresentationInfo
second_title: Aspose.Slides for Java API Reference
description: Informations sur le fichier de présentation
type: docs
url: /fr/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Informations sur le fichier de présentation
## Méthodes

| Méthode | Description |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Renvoie True si la présentation liée est chiffrée, sinon False. |
| [isPasswordProtected()](#isPasswordProtected--) | Obtient une valeur indiquant si la présentation liée est protégée par un mot de passe à l'ouverture. |
| [isWriteProtected()](#isWriteProtected--) | Obtient une valeur indiquant si la présentation liée est protégée en écriture. |
| [getLoadFormat()](#getLoadFormat--) | Obtient le format de la présentation liée. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Vérifie si le mot de passe est correct pour une présentation protégée par un mot de passe d'ouverture. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Vérifie si le mot de passe de modification est correct pour une présentation protégée en écriture. |
| [readDocumentProperties()](#readDocumentProperties--) | Obtient les propriétés du document de la présentation liée. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Met à jour les propriétés de la présentation liée. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Écrit la présentation liée dans le flux. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Écrit la présentation liée dans le fichier. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Renvoie True si la présentation liée est chiffrée, sinon False. Booléen en lecture seule.

**Retourne :**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


Obtient une valeur indiquant si la présentation liée est protégée par un mot de passe à l'ouverture.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**Retourne :**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```


Obtient une valeur indiquant si la présentation liée est protégée en écriture.

--------------------

> ```
> IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

Si la présentation est protégée par un mot de passe à l'ouverture, la valeur de la propriété est égale à NotDefined. Voir l'énumération [NullableBool](../../com.aspose.slides/nullablebool).

**Retourne :**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```


Obtient le format de la présentation liée. [LoadFormat](../../com.aspose.slides/loadformat) en lecture seule.

**Retourne :**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```


Vérifie si le mot de passe est correct pour une présentation protégée par un mot de passe d'ouverture.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Le mot de passe à vérifier.

--------------------

Lorsque le mot de passe est nul ou vide, cette méthode renvoie false. |

**Retourne :**
boolean - True si la présentation est protégée par un mot de passe d'ouverture et que le mot de passe est correct, sinon false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


Vérifie si le mot de passe de modification est correct pour une présentation protégée en écriture.

--------------------

> ```
> IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Le mot de passe à vérifier.

--------------------

1. Vous devez vérifier la propriété (\#isWriteProtected.isWriteProtected) avant d'appeler cette méthode. 2. Lorsque le mot de passe est nul ou vide, cette méthode renvoie false. |

**Retourne :**
boolean - True si la présentation est protégée en écriture et que le mot de passe est correct. False sinon.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```


Obtient les propriétés du document de la présentation liée.

**Retourne :**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Document properties [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```


Met à jour les propriétés de la présentation liée.

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```


**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Document properties [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```


Écrit la présentation liée dans le flux.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux doit être recherchable et accessible en écriture. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```


Écrit la présentation liée dans le fichier.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Fichier de présentation. |