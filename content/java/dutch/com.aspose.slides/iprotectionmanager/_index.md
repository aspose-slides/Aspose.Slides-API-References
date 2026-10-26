---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: Beheer van presentatiewachtwoordbeveiliging.
type: docs
url: /nl/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Beheer van presentatiewachtwoordbeveiliging.
## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Deze eigenschap is relevant als de presentatie met een wachtwoord is beveiligd. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Deze eigenschap is relevant als de presentatie met een wachtwoord is beveiligd. |
| [isEncrypted()](#isEncrypted--) | Haalt een waarde op die aangeeft of deze instantie versleuteld is. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Deze eigenschap is relevant als het presentatie-bestand met een wachtwoord is beveiligd en de documenteigenschappen van dit bestand openbaar zijn. |
| [isWriteProtected()](#isWriteProtected--) | Haalt een waarde op die aangeeft of deze presentatie alleen-schrijfbescherming heeft. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Retourneert het versleutelingswachtwoord. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Haalt de aanbeveling voor alleen-lezen op of stelt deze in. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Haalt de aanbeveling voor alleen-lezen op of stelt deze in. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Versleutelt de presentatie met het opgegeven wachtwoord. |
| [removeEncryption()](#removeEncryption--) | Verwijdert de versleuteling. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Stelt schrijfbescherming in voor deze presentatie met het opgegeven wachtwoord. |
| [removeWriteProtection()](#removeWriteProtection--) | Verwijdert de schrijfbescherming voor deze presentatie. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Bepaalt of een presentatie met wachtwoord is beveiligd om te wijzigen. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Deze eigenschap is relevant als de presentatie met een wachtwoord is beveiligd. Als true dan zijn de documenteigenschappen versleuteld in het presentatie-bestand. Als false dan zijn de documenteigenschappen openbaar terwijl de presentatie is versleuteld. Lezen/Schrijven boolean.

**Retour:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Deze eigenschap is relevant als de presentatie met een wachtwoord is beveiligd. Als true dan zijn de documenteigenschappen versleuteld in het presentatie-bestand. Als false dan zijn de documenteigenschappen openbaar terwijl de presentatie is versleuteld. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Haalt een waarde op die aangeeft of deze instantie versleuteld is. Alleen-lezen boolean.

Waarde: true als de presentatie is geladen vanuit een versleuteld bestand of de \#encrypt(String).encrypt(String)-methode is aangeroepen; anders false.

**Retour:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Deze eigenschap is relevant als het presentatie-bestand met een wachtwoord is beveiligd en de documenteigenschappen van dit bestand openbaar zijn. Waarde true betekent dat alleen de documenteigenschappen worden geladen uit een versleuteld presentatie-bestand zonder wachtwoord. Waarde false betekent dat de volledige versleutelde presentatie wordt geladen met het juiste wachtwoord, niet alleen de documenteigenschappen. Als de presentatie niet versleuteld is, is de eigenschap altijd false. Als de documenteigenschappen van een versleuteld bestand niet openbaar zijn, is de eigenschap altijd false. Als PresentationEx.EncryptDocumentProperties true is, is IsOnlyDocumentPropertiesLoaded altijd false. Alleen-lezen boolean.

**Retour:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Haalt een waarde op die aangeeft of deze presentatie schrijfbescherming heeft. Alleen-lezen boolean.

**Retour:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Retourneert het versleutelingswachtwoord. Alleen-lezen String.

**Retour:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Haalt de aanbeveling voor alleen-lezen op of stelt deze in. Lezen/Schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Retour:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Haalt de aanbeveling voor alleen-lezen op of stelt deze in. Lezen/Schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Versleutelt de presentatie met het opgegeven wachtwoord.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Het wachtwoord. |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Verwijdert de versleuteling.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Stelt schrijfbescherming in voor deze presentatie met het opgegeven wachtwoord.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | java.lang.String | Het wachtwoord. |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Verwijdert de schrijfbescherming voor deze presentatie.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Bepaalt of een presentatie met wachtwoord is beveiligd om te wijzigen.

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

--------------------

1. U moet de (\#isWriteProtected.isWriteProtected) eigenschap controleren voordat u deze methode aanroept. 2. Wanneer het wachtwoord null of leeg is, retourneert deze methode false. |

**Retour:**
boolean - True als het wachtwoord geldig is; anders false.