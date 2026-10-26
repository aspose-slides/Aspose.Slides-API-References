---
title: PresentationInfo
second_title: Référence de l'API Aspose.Slides pour Java
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
| [isEncrypted()](#isEncrypted--) | Renvoie True si la présentation liée est chiffrée, sinon False. |
| [isPasswordProtected()](#isPasswordProtected--) | Renvoie une valeur indiquant si la présentation liée est protégée par un mot de passe à l'ouverture. |
| [isWriteProtected()](#isWriteProtected--) | Renvoie une valeur indiquant si la présentation liée est protégée en écriture. |
| [getLoadFormat()](#getLoadFormat--) | Renvoie le format de la présentation liée. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe d'ouverture. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Vérifie si le mot de passe de modification est correct pour une présentation protégée en écriture. |
| [readDocumentProperties()](#readDocumentProperties--) | Renvoie les propriétés du document de la présentation liée. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Met à jour les propriétés de la présentation liée. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Écrit la présentation liée dans un flux. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Écrit la présentation liée dans un fichier. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Renvoie True si la présentation liée est chiffrée, sinon False. Boolean lecture seule.

**Retour :**  
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Renvoie une valeur indiquant si la présentation liée est protégée par un mot de passe à l'ouverture.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


**Retour :**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Renvoie une valeur indiquant si la présentation liée est protégée en écriture.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


---

Si la présentation est protégée par un mot de passe à l'ouverture, la valeur de la propriété est égale à NotDefined.

**Retour :**  
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Renvoie le format de la présentation liée. Lecture seule [LoadFormat](../../com.aspose.slides/loadformat).

**Retour :**  
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Vérifie si un mot de passe est correct pour une présentation protégée par un mot de passe d'ouverture.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Le mot de passe à vérifier. |

Lorsque le mot de passe est null ou vide, cette méthode renvoie false.

**Retour :**  
boolean - True si la présentation est protégée par un mot de passe d'ouverture et que le mot de passe est correct, sinon false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Vérifie si le mot de passe de modification est correct pour une présentation protégée en écriture.

---

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| password | java.lang.String | Le mot de passe à vérifier. |

1. Vous devez vérifier la propriété (#isWriteProtected.isWriteProtected) avant d'appeler cette méthode. 2. Lorsque le mot de passe est null ou vide, cette méthode renvoie false.

**Retour :**  
boolean - True si la présentation est protégée en écriture et que le mot de passe est correct. False sinon.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Renvoie les propriétés du document de la présentation liée.

**Retour :**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Met à jour les propriétés de la présentation liée.

---

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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Écrit la présentation liée dans un flux.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Le flux doit être cherchable et accessible en écriture. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Écrit la présentation liée dans un fichier.

**Paramètres :**  
| Paramètre | Type | Description |
| --- | --- | --- |
| file | java.lang.String | Fichier de présentation. |