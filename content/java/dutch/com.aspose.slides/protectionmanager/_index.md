---
title: ProtectionManager
second_title: Aspose.Slides voor Java API-referentie
description: Beheer van wachtwoordbeveiliging voor presentaties.
type: docs
url: /nl/com.aspose.slides/protectionmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Beheer van wachtwoordbeveiliging voor presentaties.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Deze eigenschap is zinvol als de presentatie met een wachtwoord is beschermd. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Deze eigenschap is zinvol als de presentatie met een wachtwoord is beschermd. |
| [isEncrypted()](#isEncrypted--) | Haalt een waarde op die aangeeft of deze instantie versleuteld is. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Deze eigenschap is zinvol als het presentatiedocument met een wachtwoord is beschermd en de documenteigenschappen van dit bestand openbaar zijn. |
| [isWriteProtected()](#isWriteProtected--) | Haalt een waarde op die aangeeft of deze presentatie tegen schrijven is beschermd. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Versleutelt de presentatie met het opgegeven wachtwoord. |
| [removeEncryption()](#removeEncryption--) | Verwijdert de versleuteling. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Stelt schrijfbescherming in voor deze presentatie met het opgegeven wachtwoord. |
| [removeWriteProtection()](#removeWriteProtection--) | Verwijdert de schrijfbescherming voor deze presentatie. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Bepaalt of een presentatie met een wachtwoord is beveiligd voor bewerking. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Haalt het wachtwoord op dat wordt gebruikt voor de versleuteling van de presentatie. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Haalt de aanbeveling voor alleen-lezen op of stelt deze in. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Haalt de aanbeveling voor alleen-lezen op of stelt deze in. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```


Deze eigenschap is zinvol als de presentatie met een wachtwoord is beschermd. Als true dan is documenteigenschappen versleuteld in het presentatiedocument. Als false dan zijn documenteigenschappen openbaar terwijl de presentatie versleuteld is. Lezen/Schrijven boolean.

**Retour:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```


Deze eigenschap is zinvol als de presentatie met een wachtwoord is beschermd. Als true dan is documenteigenschappen versleuteld in het presentatiedocument. Als false dan zijn documenteigenschappen openbaar terwijl de presentatie versleuteld is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```


Haalt een waarde op die aangeeft of deze instantie versleuteld is. Alleen-lezen boolean.

Waarde: true als de presentatie is geladen uit een versleuteld bestand of de methode \#encrypt(String).encrypt(String) is aangeroepen; anders false.

**Retour:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```


Deze eigenschap is zinvol als het presentatiedocument met een wachtwoord is beschermd en de documenteigenschappen van dit bestand openbaar zijn. Waarde true betekent dat alleen documenteigenschappen zijn geladen uit een versleuteld presentatiedocument zonder gebruik van een wachtwoord. Waarde false betekent dat het volledige versleutelde presentatiedocument is geladen met gebruik van het juiste wachtwoord; niet alleen documenteigenschappen worden geladen. Als de presentatie niet versleuteld is, is de eigenschap altijd false. Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn, is de eigenschap altijd false. Als Presentation.EncryptDocumentProperties true is, is IsOnlyDocumentPropertiesLoaded altijd false. Alleen-lezen boolean.

**Retour:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```


Haalt een waarde op die aangeeft of deze presentatie tegen schrijven is beschermd. Alleen-lezen boolean.

**Retour:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```


Versleutelt de presentatie met het opgegeven wachtwoord.

--------------------

> ```
> De volgende voorbeeldcode laat zien hoe u een PowerPoint-presentatie kunt versleutelen.
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


Stelt schrijfbescherming in voor deze presentatie met het opgegeven wachtwoord.

--------------------

> ```
> De volgende voorbeeldcode laat zien hoe u een schrijfbescherming op een presentatie kunt instellen.
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


Verwijdert de schrijfbescherming voor deze presentatie.

--------------------

> ```
> Deze voorbeeldcode laat zien hoe u de schrijfbescherming van een PowerPoint-presentatie kunt verwijderen.
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


Bepaalt of een presentatie met een wachtwoord is beveiligd voor bewerking.

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

1. U moet de (\#isWriteProtected.isWriteProtected) eigenschap controleren voordat u deze methode aanroept. 2. Wanneer het wachtwoord null of leeg is, geeft deze methode false terug. |

**Retour:**
boolean - True als het wachtwoord geldig is; anders false.
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


Haalt de aanbeveling voor alleen-lezen op of stelt deze in. Lezen/Schrijven boolean.

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


Haalt de aanbeveling voor alleen-lezen op of stelt deze in. Lezen/Schrijven boolean.

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