---
title: IProtectionManager
second_title: Aspose.Slides for Android via Java API Reference
description: Presentation password protection management.
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
| [isEncrypted()](#isEncrypted--) | Získá hodnotu určující, zda je tato instance šifrována. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Tato vlastnost dává smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné. |
| [isWriteProtected()](#isWriteProtected--) | Získá hodnotu určující, zda je tato prezentace chráněna proti zápisu. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Vrací šifrovací heslo. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Získá nebo nastaví doporučení pouze pro čtení. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Získá nebo nastaví doporučení pouze pro čtení. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Zašifruje prezentaci pomocí zadaného hesla. |
| [removeEncryption()](#removeEncryption--) | Odstraní šifrování. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Nastaví ochranu proti zápisu pro tuto prezentaci pomocí zadaného hesla. |
| [removeWriteProtection()](#removeWriteProtection--) | Odstraní ochranu proti zápisu pro tuto prezentaci. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Určuje, zda je prezentace chráněna heslem pro úpravy. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Tato vlastnost dává smysl, pokud je prezentace chráněna heslem. Pokud je true, pak jsou vlastnosti dokumentu v souboru prezentace zašifrovány. Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je zašifrována. Boolean – čtení/zápis.

**Vrací:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Tato vlastnost dává smysl, pokud je prezentace chráněna heslem. Pokud je true, pak jsou vlastnosti dokumentu v souboru prezentace zašifrovány. Pokud je false, pak jsou vlastnosti dokumentu veřejné, zatímco prezentace je zašifrována. Boolean – čtení/zápis.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Získá hodnotu určující, zda je tato instance šifrována. Boolean – jen pro čtení.

Hodnota: true, pokud byla prezentace načtena ze šifrovaného souboru nebo byla zavolána metoda \#encrypt(String).encrypt(String); jinak false.

**Vrací:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Tato vlastnost dává smysl, pokud je soubor prezentace chráněn heslem a vlastnosti dokumentu tohoto souboru jsou veřejné. Hodnota true znamená, že jsou z šifrovaného souboru prezentace načteny pouze vlastnosti dokumentu bez použití hesla. Hodnota false znamená, že je načtena celá šifrovaná prezentace s použitím správného hesla, nikoli pouze vlastnosti dokumentu. Pokud není prezentace šifrována, pak je hodnota vlastnosti vždy false. Pokud nejsou vlastnosti dokumentu šifrovaného souboru veřejné, pak je hodnota vlastnosti vždy false. Pokud je PresentationEx.EncryptDocumentProperties true, pak je hodnota vlastnosti IsOnlyDocumentPropertiesLoaded vždy false. Boolean – jen pro čtení.

**Vrací:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Získá hodnotu určující, zda je tato prezentace chráněna proti zápisu. Boolean – jen pro čtení.

**Vrací:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Vrací šifrovací heslo. String – jen pro čtení.

**Vrací:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Získá nebo nastaví doporučení pouze pro čtení. Boolean – čtení/zápis.

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

Získá nebo nastaví doporučení pouze pro čtení. Boolean – čtení/zápis.

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

Zašifruje prezentaci pomocí zadaného hesla.

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

Nastaví ochranu proti zápisu pro tuto prezentaci pomocí zadaného hesla.

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
| password | java.lang.String | Heslo pro kontrolu. |
1. Měli byste zkontrolovat vlastnost (\#isWriteProtected.isWriteProtected) před voláním této metody. 2. Když je heslo null nebo prázdné, tato metoda vrací false.

**Vrací:**
boolean – true, pokud je heslo platné; jinak false.