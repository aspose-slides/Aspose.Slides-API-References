---
title: ProtectionManager
second_title: Aspose.Slides voor Android via Java API-referentie
description: Beheer van wachtwoordbeveiliging voor presentaties.
type: docs
url: /nl/com.aspose.slides/protectionmanager/
---
**Erfenis:**
java.lang.Object

**Alle geïmplementeerde interfaces:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Beheer van wachtwoordbeveiliging voor presentaties.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Deze eigenschap heeft betekenis als de presentatie met een wachtwoord is beveiligd. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Deze eigenschap heeft betekenis als de presentatie met een wachtwoord is beveiligd. |
| [isEncrypted()](#isEncrypted--) | Haalt een waarde op die aangeeft of deze instantie versleuteld is. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Deze eigenschap heeft betekenis als het presentatiedocument met een wachtwoord is beveiligd en de documenteigenschappen van dit bestand openbaar zijn. |
| [isWriteProtected()](#isWriteProtected--) | Haalt een waarde op die aangeeft of deze presentatie schrijfbeveiligd is. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Versleutelt de presentatie met het opgegeven wachtwoord. |
| [removeEncryption()](#removeEncryption--) | Verwijdert de versleuteling. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Stelt schrijfbeveiliging in voor deze presentatie met het opgegeven wachtwoord. |
| [removeWriteProtection()](#removeWriteProtection--) | Verwijdert de schrijfbeveiliging voor deze presentatie. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Bepaalt of een presentatie met een wachtwoord is beveiligd om te wijzigen. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Haalt het wachtwoord op dat wordt gebruikt voor de versleuteling van de presentatie. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Haalt of stelt de alleen-lezen aanbeveling in. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Haalt of stelt de alleen-lezen aanbeveling in. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Deze eigenschap heeft betekenis als de presentatie met een wachtwoord is beveiligd. Indien true dan worden de documenteigenschappen versleuteld in het presentatiebestand. Indien false zijn de documenteigenschappen openbaar terwijl de presentatie versleuteld is. Lezen/Schrijven boolean.

**Retour:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Deze eigenschap heeft betekenis als de presentatie met een wachtwoord is beveiligd. Indien true dan worden de documenteigenschappen versleuteld in het presentatiebestand. Indien false zijn de documenteigenschappen openbaar terwijl de presentatie versleuteld is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Haalt een waarde op die aangeeft of deze instantie versleuteld is. Alleen-lezen boolean.

Waarde: true als de presentatie is geladen uit een versleuteld bestand of de \#encrypt(String).encrypt(String)-methode is aangeroepen; anders false.

**Retour:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Deze eigenschap heeft betekenis als het presentatiedocument met een wachtwoord is beveiligd en de documenteigenschappen van dit bestand openbaar zijn. Een waarde van true betekent dat alleen de documenteigenschappen worden geladen uit een versleuteld presentatiedocument zonder gebruik van een wachtwoord. Een waarde van false betekent dat de volledige versleutelde presentatie wordt geladen met het juiste wachtwoord, niet alleen de documenteigenschappen. Als de presentatie niet versleuteld is, is de eigenschapswaarde altijd false. Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn, is de eigenschapswaarde altijd false. Als Presentation.EncryptDocumentProperties true is, dan is de IsOnlyDocumentPropertiesLoaded-eigenschap altijd false. Alleen-lezen boolean.

**Retour:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Haalt een waarde op die aangeeft of deze presentatie schrijfbeveiligd is. Alleen-lezen boolean.

**Retour:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Versleutelt de presentatie met het opgegeven wachtwoord.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Het wachtwoord. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

Verwijdert de versleuteling.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Stelt schrijfbeveiliging in voor deze presentatie met het opgegeven wachtwoord.

--------------------

> ```
> De volgende voorbeeldcode laat zien hoe je een schrijfbeveiliging op een presentatie instelt.
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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | java.lang.String | Het wachtwoord. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Verwijdert de schrijfbeveiliging voor deze presentatie.

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

Bepaalt of een presentatie met een wachtwoord is beveiligd om te wijzigen.

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
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | java.lang.String | Het wachtwoord voor controle.
1. U dient de (\#isWriteProtected.isWriteProtected) eigenschap te controleren voordat u deze methode aanroept. 2. Als het wachtwoord null of leeg is, retourneert deze methode false. |

**Retour:**
boolean - Waar als het wachtwoord geldig is; anders, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Haalt het wachtwoord op dat wordt gebruikt voor de versleuteling van de presentatie. Alleen-lezen String.

**Retour:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Haalt of stelt de alleen-lezen aanbeveling in. Lezen/Schrijven boolean.

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

**Retour:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

Haalt of stelt de alleen-lezen aanbeveling in. Lezen/Schrijven boolean.

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

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |