---
title: IPresentationInfo
second_title: Aspose.Slides voor Android via Java API-referentie
description: Informatie over presentiebestand
type: docs
url: /nl/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Informatie over presentiebestand
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Geeft True terug als de gekoppelde presentatie is versleuteld, anders False. |
| [isPasswordProtected()](#isPasswordProtected--) | Geeft een waarde die aangeeft of een gekoppelde presentatie wordt beschermd door een wachtwoord om te openen. |
| [isWriteProtected()](#isWriteProtected--) | Geeft een waarde die aangeeft of een gekoppelde presentatie schrijfbeveiligd is. |
| [getLoadFormat()](#getLoadFormat--) | Geeft het formaat van de gekoppelde presentatie. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Controleert of een wachtwoord correct is voor een presentatie die beschermd is met een open wachtwoord. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Controleert of een wachtwoord om te wijzigen correct is voor een schrijfbeveiligde presentatie. |
| [readDocumentProperties()](#readDocumentProperties--) | Geeft documenteigenschappen van de gekoppelde presentatie. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Werk eigendommen van de gekoppelde presentatie bij. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Schrijft de gekoppelde presentatie naar een stream. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Schrijft de gekoppelde presentatie naar een bestand. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Geeft True terug als de gekoppelde presentatie versleuteld is, anders False. Alleen-lezen boolean.

**Retour:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Geeft een waarde die aangeeft of een gekoppelde presentatie wordt beschermd door een wachtwoord om te openen.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**Retour:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Geeft een waarde die aangeeft of een gekoppelde presentatie schrijfbeveiligd is.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

Als de presentatie wordt beschermd door een wachtwoord om te openen, is de eigenschapswaarde gelijk aan NotDefined. Zie enumeratie [NullableBool](../../com.aspose.slides/nullablebool).

**Retour:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Geeft het formaat van de gekoppelde presentatie. Alleen-lezen [LoadFormat](../../com.aspose.slides/loadformat).

**Retour:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Controleert of een wachtwoord correct is voor een presentatie die beschermd is met een open wachtwoord.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| password | java.lang.String | Het wachtwoord om te controleren. |

--------------------

Wanneer het wachtwoord null of leeg is, retourneert deze methode false.

**Retour:**
boolean - True als de presentatie beschermd is met een open wachtwoord en het wachtwoord correct is, en false anders.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Controleert of een wachtwoord om te wijzigen correct is voor een schrijfbeveiligde presentatie.

--------------------

> ```
> IPPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| password | java.lang.String | Het wachtwoord om te controleren. |

--------------------

1. U dient de (\#isWriteProtected.isWriteProtected) eigenschap te controleren voordat u deze methode aanroept. 2. Wanneer het wachtwoord null of leeg is, retourneert deze methode false.

**Retour:**
boolean - True als de presentatie schrijfbeveiligd is en het wachtwoord correct is. False anders.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Geeft documenteigenschappen van de gekoppelde presentatie.

**Retour:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Documenteigenschappen [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Werk eigendommen van de gekoppelde presentatie bij.

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

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Documenteigenschappen [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Schrijft de gekoppelde presentatie naar een stream.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De stream moet doorzoekbaar en schrijfbaar zijn. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Schrijft de gekoppelde presentatie naar een bestand.

**Parameters:**
| Parameter | Type | Omschrijving |
| --- | --- | --- |
| file | java.lang.String | Presentatiebestand. |