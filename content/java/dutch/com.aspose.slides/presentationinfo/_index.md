---
title: PresentationInfo
second_title: Aspose.Slides voor Java API-referentie
description: Informatie over presentatiebestand
type: docs
url: /nl/com.aspose.slides/presentationinfo/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Informatie over presentatiebestand
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Geeft True terug als de bindende presentatie versleuteld is, anders False. |
| [isPasswordProtected()](#isPasswordProtected--) | Geeft een waarde die aangeeft of een bindende presentatie beveiligd is met een wachtwoord om te openen. |
| [isWriteProtected()](#isWriteProtected--) | Geeft een waarde die aangeeft of een bindende presentatie schrijfbeveiligd is. |
| [getLoadFormat()](#getLoadFormat--) | Geeft het formaat van de bindende presentatie. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Controleert of een wachtwoord correct is voor een presentatie die beveiligd is met een open-wachtwoord. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Controleert of een wachtwoord om te wijzigen correct is voor een schrijfbeveiligde presentatie. |
| [readDocumentProperties()](#readDocumentProperties--) | Geeft documenteigenschappen van de bindende presentatie. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Werkt eigenschappen van de bindende presentatie bij. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Schrijft bindende presentatie naar stream. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Schrijft bindende presentatie naar bestand. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Geeft True terug als de bindende presentatie versleuteld is, anders False. Alleen-lezen boolean.

**Retour:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```


Geeft een waarde die aangeeft of een bindende presentatie beveiligd is met een wachtwoord om te openen.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**Retour:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```


Geeft een waarde die aangeeft of een bindende presentatie schrijfbeveiligd is.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

Als de presentatie beveiligd is met een wachtwoord om te openen, is de eigenschapswaarde gelijk aan NotDefined.

**Retour:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```


Geeft het formaat van de bindende presentatie. Alleen-lezen [LoadFormat](../../com.aspose.slides/loadformat).

**Retour:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```


Controleert of een wachtwoord correct is voor een presentatie die beveiligd is met een open-wachtwoord.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | java.lang.String | Het te controleren wachtwoord.

--------------------

Wanneer het wachtwoord null of leeg is, retourneert deze methode false. |

**Retour:**
boolean - True als de presentatie beveiligd is met een open-wachtwoord en het wachtwoord correct is, en anders false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```


Controleert of een wachtwoord om te wijzigen correct is voor een schrijfbeveiligde presentatie.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | java.lang.String | Het te controleren wachtwoord.

--------------------

1. U moet de (\#isWriteProtected.isWriteProtected) eigenschap controleren voordat u deze methode aanroept. 2. Wanneer het wachtwoord null of leeg is, retourneert deze methode false. |

**Retour:**
boolean - True als de presentatie schrijfbeveiligd is en het wachtwoord correct is. False anders.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```


Geeft documenteigenschappen van de bindende presentatie.

**Retour:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```


Werkt eigenschappen van de bindende presentatie bij.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```


Schrijft bindende presentatie naar stream.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| stream | java.io.OutputStream | De stream moet zoekbaar en schrijfbaar zijn. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```


Schrijft bindende presentatie naar bestand.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| file | java.lang.String | Presentatie-bestand. |