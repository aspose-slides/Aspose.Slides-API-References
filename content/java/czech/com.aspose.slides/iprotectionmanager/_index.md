---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: Správa ochrany prezentace heslem.
type: docs
url: /cs/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

Správa ochrany prezentace heslem.
## Metody

| Metoda | Popis |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Tato vlastnost dává smysl, pokud je prezentace chráněna heslem. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Tato vlastnost dává smysl, pokud je prezentace chráněna heslem. |
| [isEncrypted()](#isEncrypted--) | Získá hodnotu indikující, zda je tato instance zašifrována. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Tato vlastnost dává smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné. |
| [isWriteProtected()](#isWriteProtected--) | Získá hodnotu indikující, zda je tato prezentace chráněna proti zápisu. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Vrací šifrovací heslo. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Získá nebo nastaví doporučení pouze pro čtení. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Získá nebo nastaví doporučení pouze pro čtení. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Zašifruje prezentaci zadaným heslem. |
| [removeEncryption()](#removeEncryption--) | Odstraní šifrování. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Nastaví ochranu proti zápisu pro tuto prezentaci se zadaným heslem. |
| [removeWriteProtection()](#removeWriteProtection--) | Odstraní ochranu proti zápisu pro tuto prezentaci. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Určuje, zda je prezentace chráněna heslem pro úpravy. |

### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Tato vlastnost dává smysl, pokud je prezentace chráněna heslem. Pokud je true, pak jsou vlastnosti dokumentu zašifrovány v souboru prezentace. Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je zašifrována. Čtení/zápis boolovská hodnota.

**Vrací:**
boolean

### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Tato vlastnost dává smysl, pokud je prezentace chráněna heslem. Pokud je true, pak jsou vlastnosti dokumentu zašifrovány v souboru prezentace. Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je zašifrována. Čtení/zápis boolovská hodnota.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Získá hodnotu indikující, zda je tato instance zašifrována. Pouze pro čtení boolovská hodnota.

Hodnota: true pokud byla prezentace načtena z zašifrovaného souboru nebo byla zavolána metoda \#encrypt(String).encrypt(String); jinak false.

**Vrací:**
boolean

### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Tato vlastnost dává smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné. Hodnota true znamená, že jsou načteny pouze vlastnosti dokumentu z zašifrovaného souboru prezentace bez použití hesla. Hodnota false znamená, že celá zašifrovaná prezentace je načtena s použitím správného hesla, ne pouze vlastnosti dokumentu. Pokud prezentace není zašifrována, je hodnota vlastnosti vždy false. Pokud vlastnosti dokumentu zašifrovaného souboru nejsou veřejné, je hodnota vlastnosti vždy false. Pokud je PresentationEx.EncryptDocumentProperties true, pak je hodnota IsOnlyDocumentPropertiesLoaded vždy false. Pouze pro čtení boolovská hodnota.

**Vrací:**
boolean

### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Získá hodnotu indikující, zda je tato prezentace chráněna proti zápisu. Pouze pro čtení boolovská hodnota.

**Vrací:**
boolean

### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Vrací šifrovací heslo. Pouze pro čtení String.

**Vrací:**
java.lang.String

### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Získá nebo nastaví doporučení pouze pro čtení. Čtení/zápis boolovská hodnota.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Vrací:**
boolean

### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Získá nebo nastaví doporučení pouze pro čtení. Čtení/zápis boolovská hodnota.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```


**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |

### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Zašifruje prezentaci zadaným heslem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| encryptionPassword | java.lang.String | Heslo. |

### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Odstraní šifrování.

### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Nastaví ochranu proti zápisu pro tuto prezentaci se zadaným heslem.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| password | java.lang.String | Heslo. |

### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Odstraní ochranu proti zápisu pro tuto prezentaci.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
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

1. Před voláním této metody byste měli zkontrolovat vlastnost (\#isWriteProtected.isWriteProtected). 2. Když je heslo null nebo prázdné, tato metoda vrací false.

**Vrací:**
boolean - True pokud je heslo platné; jinak false.