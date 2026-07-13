---
title: IProtectionManager
second_title: Aspose.Slides för Android via Java API-referens
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
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Denna egenskap är meningsfull om presentationen är lösenordsskyddad. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Denna egenskap är meningsfull om presentationen är lösenordsskyddad. |
| [isEncrypted()](#isEncrypted--) | Hämtar ett värde som indikerar om denna instans är krypterad. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad och dokumentegenskaperna för den filen är offentliga. |
| [isWriteProtected()](#isWriteProtected--) | Hämtar ett värde som indikerar om denna presentation är skrivskyddad. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Returnerar krypteringslösenord. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Hämtar eller anger rekommendation för skrivskydd. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Hämtar eller anger rekommendation för skrivskydd. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Krypterar presentationen med angivet lösenord. |
| [removeEncryption()](#removeEncryption--) | Tar bort krypteringen. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Sätter skrivskydd för denna presentation med angivet lösenord. |
| [removeWriteProtection()](#removeWriteProtection--) | Tar bort skrivskyddet för denna presentation. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Fastställer om en presentation är lösenordsskyddad för att modifieras. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Denna egenskap är meningsfull om presentationen är lösenordsskyddad. Om true är dokumentegenskaperna krypterade i presentationsfilen. Om false är dokumentegenskaperna offentliga medan presentationen är krypterad. Läs/skriv boolesk.

**Returnerar:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Denna egenskap är meningsfull om presentationen är lösenordsskyddad. Om true är dokumentegenskaperna krypterade i presentationsfilen. Om false är dokumentegenskaperna offentliga medan presentationen är krypterad. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Hämtar ett värde som indikerar om denna instans är krypterad. Endast läsning boolesk.

Värde: true om presentationen lästes in från en krypterad fil eller #encrypt(String).encrypt(String)-metoden anropades; annars false.

**Returnerar:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad och dokumentegenskaperna för den filen är offentliga. Värdet true betyder att endast dokumentegenskaper laddas från en krypterad presentationsfil utan att ett lösenord används. Värdet false betyder att hela den krypterade presentationen laddas med rätt lösenord, inte bara dokumentegenskaperna. Om presentationen inte är krypterad är egenskapsvärdet alltid false. Om dokumentegenskaperna för en krypterad fil inte är offentliga är egenskapsvärdet alltid false. Om PresentationEx.EncryptDocumentProperties är true är värdet för IsOnlyDocumentPropertiesLoaded alltid false. Endast läsning boolesk.

**Returnerar:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Hämtar ett värde som indikerar om denna presentation är skrivskyddad. Endast läsning boolesk.

**Returnerar:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Returnerar krypteringslösenord. Endast läsning String.

**Returnerar:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Hämtar eller anger rekommendation för skrivskydd. Läs/skriv boolesk.

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

Hämtar eller anger rekommendation för skrivskydd. Läs/skriv boolesk.

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

Fastställer om en presentation är lösenordsskyddad för att modifieras.

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

1. Du bör kontrollera egenskapen (#isWriteProtected.isWriteProtected) innan du anropar den här metoden. 2. När lösenordet är null eller tomt, returnerar den här metoden false. |

**Returnerar:**
boolean