---
title: IProtectionManager
second_title: Aspose.Slides för Java API-referens
description: Hantera lösenordsskydd för presentationer.
type: docs
url: /sv/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Hantera lösenordsskydd för presentationer.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Den här egenskapen är relevant om presentationen är lösenordsskyddad. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Den här egenskapen är relevant om presentationen är lösenordsskyddad. |
| [isEncrypted()](#isEncrypted--) | Hämtar ett värde som indikerar om detta objekt är krypterat. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Den här egenskapen är relevant om presentationsfilen är lösenordsskyddad och dokumentegenskaperna för filen är offentliga. |
| [isWriteProtected()](#isWriteProtected--) | Hämtar ett värde som indikerar om denna presentation är skrivskyddad. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Returnerar krypteringslösenordet. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Hämtar eller anger rekommendation för skrivskydd. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Hämtar eller anger rekommendation för skrivskydd. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Krypterar presentationen med angivet lösenord. |
| [removeEncryption()](#removeEncryption--) | Tar bort krypteringen. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Sätter skrivskydd för denna presentation med angivet lösenord. |
| [removeWriteProtection()](#removeWriteProtection--) | Tar bort skrivskyddet för denna presentation. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Avgör om en presentation är lösenordsskyddad för modifiering. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```


Den här egenskapen är relevant om presentationen är lösenordsskyddad. Om true är dokumentegenskaperna krypterade i presentationsfilen. Om false är dokumentegenskaperna offentliga medan presentationen är krypterad. Läs/skriv boolean.

**Returnerar:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```


Den här egenskapen är relevant om presentationen är lösenordsskyddad. Om true är dokumentegenskaperna krypterade i presentationsfilen. Om false är dokumentegenskaperna offentliga medan presentationen är krypterad. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


Hämtar ett värde som indikerar om detta objekt är krypterat. Skrivskyddad boolean.

Värde: true om presentationen lästes in från en krypterad fil eller metod \#encrypt(String).encrypt(String) anropades; annars false.

**Returnerar:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```


Den här egenskapen är relevant om presentationsfilen är lösenordsskyddad och dokumentegenskaperna för filen är offentliga. Värdet true betyder att endast dokumentegenskaperna läses in från en krypterad presentationsfil utan lösenord. Värdet false betyder att hela den krypterade presentationen läses in med korrekt lösenord, inte bara dokumentegenskaperna. Om presentationen inte är krypterad är egenskapens värde alltid false. Om dokumentegenskaperna i en krypterad fil inte är offentliga är värdet alltid false. Om PresentationEx.EncryptDocumentProperties är true är IsOnlyDocumentPropertiesLoaded alltid false. Skrivskyddad boolean.

**Returnerar:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```


Hämtar ett värde som indikerar om denna presentation är skrivskyddad. Skrivskyddad boolean.

**Returnerar:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```


Returnerar krypteringslösenordet. Skrivskyddad String.

**Returnerar:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```


Hämtar eller anger rekommendation för skrivskydd. Läs/skriv boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Returnerar:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```


Hämtar eller anger rekommendation för skrivskydd. Läs/skriv boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```


Krypterar presentationen med angivet lösenord.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Lösenordet. |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```


Tar bort krypteringen.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```


Sätter skrivskydd för denna presentation med angivet lösenord.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| password | java.lang.String | Lösenordet. |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```


Tar bort skrivskyddet för denna presentation.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


Avgör om en presentation är lösenordsskyddad för modifiering.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| password | java.lang.String | Lösenordet för kontroll.

--------------------

1. Du bör kontrollera egenskapen (\#isWriteProtected.isWriteProtected) innan du anropar den här metoden. 2. När lösenordet är null eller tomt returnerar den här metoden false. |

**Returnerar:**
boolean - True om lösenordet är giltigt; annars false.