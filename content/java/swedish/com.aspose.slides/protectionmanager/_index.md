---
title: ProtectionManager
second_title: Aspose.Slides för Java API-referens
description: Hantera lösenordsskydd för presentation.
type: docs
url: /sv/com.aspose.slides/protectionmanager/
---
**Arv:**
java.lang.Object

**Alla implementerade gränssnitt:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Hanering av lösenordsskydd för presentation.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Denna egenskap är meningsfull om presentationen är lösenordsskyddad. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Denna egenskap är meningsfull om presentationen är lösenordsskyddad. |
| [isEncrypted()](#isEncrypted--) | Hämtar ett värde som indikerar om den här instansen är krypterad. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad och dokumentegenskaperna för denna fil är offentliga. |
| [isWriteProtected()](#isWriteProtected--) | Hämtar ett värde som indikerar om denna presentation är skrivskyddad. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Krypterar Presentation med angivet lösenord. |
| [removeEncryption()](#removeEncryption--) | Tar bort krypteringen. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Ställer in skrivskydd för den här presentationen med angivet lösenord. |
| [removeWriteProtection()](#removeWriteProtection--) | Tar bort skrivskyddet för den här presentationen. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Avgör om en presentation är lösenordsskyddad för att modifieras. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Hämtar lösenordet som används för presentationens kryptering. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Hämtar eller anger rekommendation för skrivskydd. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Hämtar eller anger rekommendation för skrivskydd. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Denna egenskap är meningsfull om presentationen är lösenordsskyddad. Om true är dokumentegenskaper krypterade i presentationsfilen. Om false är dokumentegenskaper offentliga medan presentationen är krypterad. Läs/skriv boolesk.

**Returnerar:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Denna egenskap är meningsfull om presentationen är lösenordsskyddad. Om true är dokumentegenskaper krypterade i presentationsfilen. Om false är dokumentegenskaper offentliga medan presentationen är krypterad. Läs/skriv boolesk.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Hämtar ett värde som indikerar om den här instansen är krypterad. Läs-endast boolesk.

**Returnerar:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad och dokumentegenskaperna för denna fil är offentliga. Värdet true betyder att endast dokumentegenskaper laddas från en krypterad presentationsfil utan lösenord. Värdet false betyder att hela den krypterade presentationen laddas med rätt lösenord, inte bara dokumentegenskaperna. Om presentationen inte är krypterad är egenskapens värde alltid false. Om dokumentegenskaperna i en krypterad fil inte är offentliga är egenskapens värde alltid false. Om Presentation.EncryptDocumentProperties är true är värdet för IsOnlyDocumentPropertiesLoaded alltid false. Läs-endast boolesk.

**Returnerar:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Hämtar ett värde som indikerar om denna presentation är skrivskyddad. Läs-endast boolesk.

**Returnerar:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Krypterar Presentation med angivet lösenord.

--------------------

> ```
> Följande exempel visar hur du krypterar en PowerPoint-presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().encrypt("123123");
>      pres.save("encrypted-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Lösenordet. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

Tar bort krypteringen.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Ställer in skrivskydd för den här presentationen med angivet lösenord.

--------------------

> ```
> Följande exempel visar hur du anger ett skrivskydd för en presentation.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| password | java.lang.String | Lösenordet. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Tar bort skrivskyddet för den här presentationen.

--------------------

> ```
> Detta exempel visar hur du tar bort skrivskyddet från en PowerPoint-presentation.
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

Avgör om en presentation är lösenordsskyddad för att modifieras.

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

1. Du bör kontrollera egenskapen (#isWriteProtected.isWriteProtected) innan du anropar den här metoden. 2. När lösenordet är null eller tomt returnerar den här metoden false.

**Returnerar:**
boolean - True om lösenordet är giltigt; annars false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Hämtar lösenordet som används för presentationens kryptering. Läs-endast Sträng.

**Returnerar:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Hämtar eller anger rekommendation för skrivskydd. Läs/skriv boolesk.

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

**Returnerar:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

Hämtar eller anger rekommendation för skrivskydd. Läs/skriv boolesk.

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


**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |