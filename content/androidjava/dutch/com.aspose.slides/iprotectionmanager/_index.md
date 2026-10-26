---
title: IProtectionManager
second_title: Aspose.Slides voor Android via Java API-referentie
description: Beheer van wachtwoordbeveiliging voor presentaties.
type: docs
url: /nl/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Beheer van wachtwoordbeveiliging voor presentaties.

## Methoden

| Methode | Beschrijving |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Deze eigenschap is relevant als de presentatie met een wachtwoord is beveiligd. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Deze eigenschap is relevant als de presentatie met een wachtwoord is beveiligd. |
| [isEncrypted()](#isEncrypted--) | Geeft een waarde terug die aangeeft of dit exemplaar versleuteld is. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Deze eigenschap is relevant als het presentatied bestand met een wachtwoord is beveiligd en de documenteigenschappen van dit bestand openbaar zijn. |
| [isWriteProtected()](#isWriteProtected--) | Geeft een waarde terug die aangeeft of deze presentatie schrijfbeveiligd is. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Retourneert het versleutelingswachtwoord. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Geeft of stelt de alleen-lezen-aanbeveling in. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Geeft of stelt de alleen-lezen-aanbeveling in. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Versleutelt de presentatie met het opgegeven wachtwoord. |
| [removeEncryption()](#removeEncryption--) | Verwijdert de versleuteling. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Stelt schrijftbescherming in voor deze presentatie met het opgegeven wachtwoord. |
| [removeWriteProtection()](#removeWriteProtection--) | Verwijdert de schrijftbescherming voor deze presentatie. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Bepaalt of een presentatie met een wachtwoord is beveiligd om te wijzigen. |

### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Deze eigenschap is relevant als de presentatie met een wachtwoord is beveiligd. Als true dan is documenteigenschappen versleuteld in het presentatiebestand. Als false dan zijn documenteigenschappen openbaar terwijl de presentatie versleuteld is. Lezen/Schrijven boolean.

**Retourneert:**
boolean

### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Deze eigenschap is relevant als de presentatie met een wachtwoord is beveiligd. Als true dan is documenteigenschappen versleuteld in het presentatiebestand. Als false dan zijn documenteigenschappen openbaar terwijl de presentatie versleuteld is. Lezen/Schrijven boolean.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Geeft een waarde terug die aangeeft of dit exemplaar versleuteld is. Alleen-lezen boolean.

Waarde: true als de presentatie is geladen uit een versleuteld bestand of de methode \#encrypt(String).encrypt(String) is aangeroepen; anders false.

**Retourneert:**
boolean

### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Deze eigenschap is relevant als het presentatied bestand met een wachtwoord is beveiligd en de documenteigenschappen van dit bestand openbaar zijn. Waarde true betekent dat alleen documenteigenschappen worden geladen uit een versleuteld presentatiebestand zonder wachtwoord. Waarde false betekent dat de gehele versleutelde presentatie wordt geladen met het juiste wachtwoord; niet alleen documenteigenschappen worden geladen. Als de presentatie niet versleuteld is, is de eigenschap altijd false. Als documenteigenschappen van een versleuteld bestand niet openbaar zijn, is de eigenschap altijd false. Als PresentationEx.EncryptDocumentProperties true is, is IsOnlyDocumentPropertiesLoaded altijd false. Alleen-lezen boolean.

**Retourneert:**
boolean

### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Geeft een waarde terug die aangeeft of deze presentatie schrijfbeveiligd is. Alleen-lezen boolean.

**Retourneert:**
boolean

### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Retourneert het versleutelingswachtwoord. Alleen-lezen String.

**Retourneert:**
java.lang.String

### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Geeft of stelt de alleen-lezen-aanbeveling in. Lezen/Schrijven boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**Retourneert:**
boolean

### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Geeft of stelt de alleen-lezen-aanbeveling in. Lezen/Schrijven boolean.

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

Stelt schrijftbescherming in voor deze presentatie met het opgegeven wachtwoord.

**Parameters:**
| Parameter | Type | Beschrijving |
| --- | --- | --- |
| password | java.lang.String | Het wachtwoord. |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Verwijdert de schrijftbescherming voor deze presentatie.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
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
| password | java.lang.String | Het wachtwoord voor de controle. |

1. U dient de eigenschap (\#isWriteProtected.isWriteProtected) te controleren voordat u deze methode aanroept. 2. Wanneer het wachtwoord null of leeg is, retourneert deze methode false. |

**Retourneert:**
boolean - true als het wachtwoord geldig is; otherwise, false.