---
title: ProtectionManager
second_title: Aspose.Slides för Android via Java API-referens
description: Hantera lösenordsskydd för presentationer.
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

Presentationens lösenordsskyddshantering.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Denna egenskap är meningsfull om presentationen är lösenordsskyddad. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Denna egenskap är meningsfull om presentationen är lösenordsskyddad. |
| [isEncrypted()](#isEncrypted--) | Hämtar ett värde som indikerar om den här instansen är krypterad. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad och dokumentegenskaperna för den här filen är offentliga. |
| [isWriteProtected()](#isWriteProtected--) | Hämtar ett värde som indikerar om den här presentationen är skrivskyddad. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Krypterar presentationen med angivet lösenord. |
| [removeEncryption()](#removeEncryption--) | Tar bort krypteringen. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Ställer in skrivskydd för den här presentationen med angivet lösenord. |
| [removeWriteProtection()](#removeWriteProtection--) | Tar bort skrivskydd för den här presentationen. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Bestämmer om en presentation är lösenordsskyddad för att modifieras. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Hämtar lösenordet som används för presentationens kryptering. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Hämtar eller anger skrivskyddsrekommendation. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Hämtar eller anger skrivskyddsrekommendation. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Denna egenskap är meningsfull om presentationen är lösenordsskyddad. Om true är dokumentegenskaper krypterade i presentationsfilen. Om false är dokumentegenskaper offentliga medan presentationen är krypterad. Läs/skriv boolean.

**Returnerar:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Denna egenskap är meningsfull om presentationen är lösenordsskyddad. Om true är dokumentegenskaper krypterade i presentationsfilen. Om false är dokumentegenskaper offentliga medan presentationen är krypterad. Läs/skriv boolean.

**Parametrar:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Hämtar ett värde som indikerar om den här instansen är krypterad. Endast läs boolean.

Värde: true om presentationen lästes in från en krypterad fil eller \#encrypt(String).encrypt(String)-metoden anropades; annars false.

**Returnerar:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Denna egenskap är meningsfull om presentationsfilen är lösenordsskyddad och dokumentegenskaperna för den här filen är offentliga. Värdet true betyder att endast dokumentegenskaperna laddas från en krypterad presentationsfil utan användning av lösenord. Värdet false betyder att hela den krypterade presentationen laddas med rätt lösenord, inte bara dokumentegenskaperna. Om presentationen inte är krypterad är egenskapens värde alltid false. Om dokumentegenskaperna för en krypterad fil inte är offentliga är egenskapens värde alltid false. Om Presentation.EncryptDocumentProperties är true är IsOnlyDocumentPropertiesLoaded-egenskapens värde alltid false. Endast läs boolean.

**Returnerar:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Hämtar ett värde som indikerar om den här presentationen är skrivskyddad. Endast läs boolean.

**Returnerar:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Krypterar presentationen med angivet lösenord.

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
> The following sample code shows you how to set a write protection to a presentation.
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

Tar bort skrivskydd för den här presentationen.

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

Bestämmer om en presentation är lösenordsskyddad för att modifieras.

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

1. Du bör kontrollera egenskapen (\#isWriteProtected.isWriteProtected) innan du anropar denna metod. 2. När lösenordet är null eller tomt returnerar metoden false. |

**Returnerar:**
boolean - true om lösenordet är giltigt; annars false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Hämtar lösenordet som används för presentationens kryptering. Endast läs String.

**Returnerar:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Hämtar eller anger skrivskyddsrekommendation. Läs/skriv boolean.

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

Hämtar eller anger skrivskyddsrekommendation. Läs/skriv boolean.

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