---
title: ProtectionManager
second_title: Aspose.Slides pro Java – referenční dokumentace API
description: Správa ochrany prezentace heslem.
type: docs
url: /cs/com.aspose.slides/protectionmanager/
---
**Dědičnost:**
java.lang.Object

**Všechny implementované rozhraní:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Správa ochrany prezentace heslem.
## Metody

| Metoda | Popis |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Tato vlastnost dává smysl, pokud je prezentace chráněna heslem. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Tato vlastnost dává smysl, pokud je prezentace chráněna heslem. |
| [isEncrypted()](#isEncrypted--) | Získá hodnotu, která udává, zda je tato instance šifrována. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Tato vlastnost dává smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné. |
| [isWriteProtected()](#isWriteProtected--) | Získá hodnotu, která udává, zda je tato prezentace chráněna před zápisem. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Zašifruje prezentaci zadaným heslem. |
| [removeEncryption()](#removeEncryption--) | Odstraní šifrování. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Nastaví ochranu před zápisem pro tuto prezentaci se zadaným heslem. |
| [removeWriteProtection()](#removeWriteProtection--) | Odstraní ochranu před zápisem pro tuto prezentaci. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Určuje, zda je prezentace chráněna heslem pro úpravy. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Získá heslo, které je použito pro šifrování prezentace. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Získá nebo nastaví doporučení pro režim jen pro čtení. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Získá nebo nastaví doporučení pro režim jen pro čtení. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Tato vlastnost dává smysl, pokud je prezentace chráněna heslem. Pokud je true, pak jsou vlastnosti dokumentu v souboru prezentace zašifrovány. Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je šifrována. Čtení/zápis boolean.

**Vrací:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Tato vlastnost dává smysl, pokud je prezentace chráněna heslem. Pokud je true, pak jsou vlastnosti dokumentu v souboru prezentace zašifrovány. Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je šifrována. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Získá hodnotu, která udává, zda je tato instance šifrována. Pouze pro čtení boolean.

Hodnota: true pokud byla prezentace načtena ze šifrovaného souboru nebo byla zavolána metoda \#encrypt(String).encrypt(String) ; jinak false.

**Vrací:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Tato vlastnost dává smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné. Hodnota true znamená, že z šifrovaného souboru prezentace jsou načteny pouze vlastnosti dokumentu bez použití hesla. Hodnota false znamená, že je načtena celá šifrovaná prezentace s použitím správného hesla, ne pouze vlastnosti dokumentu. Pokud prezentace není šifrována, hodnota vlastnosti je vždy false. Pokud vlastnosti dokumentu šifrovaného souboru nejsou veřejné, hodnota vlastnosti je vždy false. Pokud je Presentation.EncryptDocumentProperties true, pak je hodnota vlastnosti IsOnlyDocumentPropertiesLoaded vždy false. Pouze pro čtení boolean.

**Vrací:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Získá hodnotu, která udává, zda je tato prezentace chráněna před zápisem. Pouze pro čtení boolean.

**Vrací:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Zašifruje prezentaci zadaným heslem.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Heslo. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

Odstraní šifrování.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Nastaví ochranu před zápisem pro tuto prezentaci se zadaným heslem.

--------------------

> ```
> Následující ukázkový kód ukazuje, jak nastavit ochranu před zápisem pro prezentaci.
>  
>  Presentation pres = new Presentation("pres.pptx");
>  try {
>      pres.getProtectionManager().setWriteProtection("123123");
>      pres.save("write-protected-pres.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| password | java.lang.String | Heslo. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Odstraní ochranu před zápisem pro tuto prezentaci.

--------------------

> ```
> Tento ukázkový kód vám ukazuje, jak odebrat ochranu před zápisem z prezentace PowerPoint.
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

Určuje, zda je prezentace chráněna heslem pro úpravy.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| password | java.lang.String | Heslo pro kontrolu.

--------------------

1. Měli byste zkontrolovat vlastnost (\#isWriteProtected.isWriteProtected) před voláním této metody. 2. Když je heslo null nebo prázdné, tato metoda vrací false. |

**Vrací:**
boolean - True pokud je heslo platné; jinak false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Získá heslo, které je použito pro šifrování prezentace. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Získá nebo nastaví doporučení pro režim jen pro čtení. Čtení/zápis boolean.

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

**Vrací:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

Získá nebo nastaví doporučení pro režim jen pro čtení. Čtení/zápis boolean.

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

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |