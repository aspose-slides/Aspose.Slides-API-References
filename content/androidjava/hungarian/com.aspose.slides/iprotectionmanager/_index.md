---
title: IProtectionManager
second_title: Aspose.Slides Androidra a Java API referencia
description: A prezentáció jelszóvédelem kezelése.
type: docs
url: /hu/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

A prezentáció jelszóvédelem kezelése.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Ez a tulajdonság akkor értelmes, ha a prezentáció jelszóval védett. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Ez a tulajdonság akkor értelmes, ha a prezentáció jelszóval védett. |
| [isEncrypted()](#isEncrypted--) | Visszaad egy értéket, amely azt jelzi, hogy ez a példány titkosított-e. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Ez a tulajdonság akkor értelmes, ha a prezentáció fájl jelszóval védett és a fájl dokumentum tulajdonságai nyilvánosak. |
| [isWriteProtected()](#isWriteProtected--) | Visszaad egy értéket, amely azt jelzi, hogy ez a prezentáció írásvédett-e. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Visszaadja a titkosítási jelszót. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Lekéri vagy beállítja az írásvédett ajánlást. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Lekéri vagy beállítja az írásvédett ajánlást. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Titkosítja a prezentációt a megadott jelszóval. |
| [removeEncryption()](#removeEncryption--) | Eltávolítja a titkosítást. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Írásvédelmet állít be a prezentációhoz a megadott jelszóval. |
| [removeWriteProtection()](#removeWriteProtection--) | Eltávolítja az írásvédelmet a prezentációról. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Megállapítja, hogy a prezentáció módosításra jelszóval védett-e. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Ez a tulajdonság akkor értelmes, ha a prezentáció jelszóval védett. Ha igaz, akkor a dokumentum tulajdonságok titkosítva vannak a prezentáció fájlban. Ha hamis, akkor a dokumentum tulajdonságok nyilvánosak, miközben a prezentáció titkosított. Olvasás/írás boolean.

**Visszatér:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Ez a tulajdonság akkor értelmes, ha a prezentáció jelszóval védett. Ha igaz, akkor a dokumentum tulajdonságok titkosítva vannak a prezentáció fájlban. Ha hamis, akkor a dokumentum tulajdonságok nyilvánosak, miközben a prezentáció titkosított. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Visszaad egy értéket, amely azt jelzi, hogy ez a példány titkosított-e. Csak olvasható boolean.

Érték: igaz, ha a prezentáció titkosított fájlból lett betöltve vagy a \#encrypt(String).encrypt(String) metódus lett meghívva; egyébként hamis.

**Visszatér:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Ez a tulajdonság akkor értelmes, ha a prezentáció fájl jelszóval védett és a fájl dokumentum tulajdonságai nyilvánosak. Az igaz érték azt jelenti, hogy csak a dokumentum tulajdonságok lettek betöltve egy titkosított prezentációs fájlból jelszó használata nélkül. A hamis érték azt jelenti, hogy a teljes titkosított prezentáció betöltésre került a megfelelő jelszóval, nem csak a dokumentum tulajdonságok. Ha a prezentáció nincs titkosítva, a tulajdonság értéke mindig hamis. Ha egy titkosított fájl dokumentum tulajdonságai nem nyilvánosak, a tulajdonság értéke mindig hamis. Ha a PresentationEx.EncryptDocumentProperties igaz, akkor az IsOnlyDocumentPropertiesLoaded tulajdonság értéke mindig hamis. Csak olvasható boolean.

**Visszatér:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Visszaad egy értéket, amely azt jelzi, hogy ez a prezentáció írásvédett-e. Csak olvasható boolean.

**Visszatér:**
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Visszaadja a titkosítási jelszót. Csak olvasható String.

**Visszatér:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Lekéri vagy beállítja az írásvédett ajánlást. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**Visszatér:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public abstract void setReadOnlyRecommended(boolean value)
```

Lekéri vagy beállítja az írásvédett ajánlást. Olvasás/írás boolean.

--------------------

> ```
> Presentation pres = new Presentation();
>  pres.getProtectionManager().setReadOnlyRecommended(true);
>  pres.save("ReadOnlyPresentation.pptx", SaveFormat.Pptx);
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public abstract void encrypt(String encryptionPassword)
```

Titkosítja a prezentációt a megadott jelszóval.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| encryptionPassword | java.lang.String | A jelszó. |
### removeEncryption() {#removeEncryption--}
```
public abstract void removeEncryption()
```

Eltávolítja a titkosítást.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public abstract void setWriteProtection(String password)
```

Írásvédelmet állít be a prezentációhoz a megadott jelszóval.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | java.lang.String | A jelszó. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Eltávolítja az írásvédelmet a prezentációról.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Megállapítja, hogy a prezentáció módosításra jelszóval védett-e.

--------------------

> ```
> Presentation presentation = new Presentation(presentationFilePath);
>  try {
>      boolean isWriteProtected = presentation.getProtectionManager().checkWriteProtection("my_password");
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | java.lang.String | A jelszó ellenőrzéshez.

1. Ellenőrizni kell a (\#isWriteProtected.isWriteProtected) tulajdonságot, mielőtt meghívja ezt a metódust. 2. Ha a jelszó null vagy üres, a metódus false értékkel tér vissza. |

**Visszatér:**
boolean - Igaz, ha a jelszó érvényes; egyébként hamis.