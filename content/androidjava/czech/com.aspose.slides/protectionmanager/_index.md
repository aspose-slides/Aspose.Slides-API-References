---
title: ProtectionManager
second_title: Aspose.Slides pro Android prostřednictvím dokumentace Java API
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
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Tato vlastnost má smysl, pokud je prezentace chráněna heslem. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Tato vlastnost má smysl, pokud je prezentace chráněna heslem. |
| [isEncrypted()](#isEncrypted--) | Vrací hodnotu, která udává, zda je tato instance šifrována. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné. |
| [isWriteProtected()](#isWriteProtected--) | Vrací hodnotu, která udává, zda je tato prezentace chráněna proti zápisu. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Šifruje prezentaci pomocí zadaného hesla. |
| [removeEncryption()](#removeEncryption--) | Odstraňuje šifrování. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Nastaví ochranu proti zápisu pro tuto prezentaci pomocí zadaného hesla. |
| [removeWriteProtection()](#removeWriteProtection--) | Odstraňuje ochranu proti zápisu pro tuto prezentaci. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Určuje, zda je prezentace chráněna heslem pro úpravy. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Vrací heslo, které se používá k šifrování prezentace. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Získává nebo nastavuje doporučení pro režim pouze pro čtení. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Získává nebo nastavuje doporučení pro režim pouze pro čtení. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Tato vlastnost má smysl, pokud je prezentace chráněna heslem. Pokud je true, pak jsou vlastnosti dokumentu v souboru prezentace šifrovány. Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je šifrována. Čtení/zápis boolean.

**Vrací:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Tato vlastnost má smysl, pokud je prezentace chráněna heslem. Pokud je true, pak jsou vlastnosti dokumentu v souboru prezentace šifrovány. Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je šifrována. Čtení/zápis boolean.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Vrací hodnotu, která udává, zda je tato instance šifrována. Pouze pro čtení boolean.

Hodnota: true pokud byla prezentace načtena ze šifrovaného souboru nebo bylo zavoláno \#encrypt(String).encrypt(String) ; jinak false.

**Vrací:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Tato vlastnost má smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné. Hodnota true znamená, že jsou z šifrovaného souboru prezentace načteny pouze vlastnosti dokumentu bez použití hesla. Hodnota false znamená, že je načtena celá šifrovaná prezentace s použitím správného hesla, nikoli pouze vlastnosti dokumentu. Pokud prezentace není šifrována, hodnota vlastnosti je vždy false. Pokud nejsou veřejné vlastnosti dokumentu šifrovaného souboru, hodnota vlastnosti je vždy false. Pokud je Presentation.EncryptDocumentProperties true, pak je hodnota vlastnosti IsOnlyDocumentPropertiesLoaded vždy false. Pouze pro čtení boolean.

**Vrací:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Vrací hodnotu, která udává, zda je tato prezentace chráněna proti zápisu. Pouze pro čtení boolean.

**Vrací:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Šifruje prezentaci pomocí zadaného hesla.

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

Odstraňuje šifrování.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Nastaví ochranu proti zápisu pro tuto prezentaci pomocí zadaného hesla.

--------------------

> ```
> Následující ukázkový kód vám ukazuje, jak nastavit ochranu proti zápisu pro prezentaci.
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

Odstraňuje ochranu proti zápisu pro tuto prezentaci.

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
| password | java.lang.String | Heslo pro kontrolu. |

1. Před voláním této metody byste měli zkontrolovat vlastnost (\#isWriteProtected.isWriteProtected). 2. Když je heslo null nebo prázdné, tato metoda vrací false. |

**Vrací:**
boolean - True pokud je heslo platné; jinak false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Vrací heslo, které se používá k šifrování prezentace. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Získává nebo nastavuje doporučení pro režim pouze pro čtení. Čtení/zápis boolean.

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

Získává nebo nastavuje doporučení pro režim pouze pro čtení. Čtení/zápis boolean.

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