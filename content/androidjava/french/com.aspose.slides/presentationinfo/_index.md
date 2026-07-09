---
title: PresentationInfo
second_title: Aspose.Slides pour Android via la référence API Java
description: Informations sur le fichier de présentation
type: docs
url: /fr/com.aspose.slides/presentationinfo/
---
**Héritage:**
java.lang.Object

**Toutes les interfaces implémentées:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Informations sur le fichier de présentation
## Méthodes

| Méthode | Description |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Renvoie Vrai si la présentation liée est chiffrée, sinon Faux. |
| [isPasswordProtected()](#isPasswordProtected--) | Renvoie une valeur indiquant si la présentation liée est protégée par un mot de passe à l'ouverture. |
| [isWriteProtected()](#isWriteProtected--) | Renvoie une valeur indiquant si la présentation liée est protégée en écriture. |
| [getLoadFormat()](#getLoadFormat--) | Renvoie le format de la présentation liée. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe d'ouverture. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Vérifie si un mot de passe de modification est correct pour une présentation protégée en écriture. |
| [readDocumentProperties()](#readDocumentProperties--) | Obtient les propriétés du document de la présentation liée. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Met à jour les propriétés de la présentation liée. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Écrit la présentation liée dans le flux. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Écrit la présentation liée dans le fichier. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Renvoie Vrai si la présentation liée est chiffrée, sinon Faux. Booléen en lecture seule.

**Retour :**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Renvoie une valeur indiquant si la présentation liée est protégée par un mot de passe à l'ouverture.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**Returns:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Gets a value that indicates whether a binded presentation is write protected.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

If the presentation is protected by a password to open, the property value equals NotDefined.

**Returns:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Gets format of the binded presentation. Read-only [LoadFormat](../../com.aspose.slides/loadformat).

**Returns:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Checks whether a password is correct for a presentation protected with open password.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password to check.

--------------------

When the password is null or empty, this method returns false. |

**Returns:**
boolean - True if the presentation is protected with open password and the password is correct and false otherwise.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Checks whether a password to modify is correct for a write protected presentation.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| password | java.lang.String | The password to check.

--------------------

1. You should check the (\#isWriteProtected.isWriteProtected) property before calling this method. 2. When password is null or empty, this method returns false. |

**Returns:**
boolean - True if the presentation is write protected and the password is correct. False otherwise.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Gets document properties of binded presentation.

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```
Updates properties of binded presentation.

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDDocumentProperties).updateDocumentProperties(IDDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentProperties | [IDDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Writes binded presentation to stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | The stream must be seekable and writable. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)


Écrit la présentation liée dans le fichier.

**Paramètres :**
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Fichier de présentation. |