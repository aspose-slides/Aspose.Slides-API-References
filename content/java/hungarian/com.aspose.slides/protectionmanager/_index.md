---
title: ProtectionManager
second_title: Aspose.Slides Java API referencia
description: A prezentáció jelszóvédelmének kezelése.
type: docs
url: /hu/com.aspose.slides/protectionmanager/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

A prezentáció jelszóvédelmi kezelése.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Ez a tulajdonság értelmes, ha a prezentáció jelszóval védett. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Ez a tulajdonság értelmes, ha a prezentáció jelszóval védett. |
| [isEncrypted()](#isEncrypted--) | Visszaad egy értéket, amely jelzi, hogy ez a példány titkosított-e. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Ez a tulajdonság értelmes, ha a prezentáció fájl jelszóval védett és a fájl dokumentumtulajdonságai nyilvánosak. |
| [isWriteProtected()](#isWriteProtected--) | Visszaad egy értéket, amely jelzi, hogy ez a prezentáció írásvédett-e. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Titkosítja a prezentációt a megadott jelszóval. |
| [removeEncryption()](#removeEncryption--) | Eltávolítja a titkosítást. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Beállítja az írásvédelmet ehhez a prezentációhoz a megadott jelszóval. |
| [removeWriteProtection()](#removeWriteProtection--) | Eltávolítja az írásvédelmet ebből a prezentációból. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Megállapítja, hogy a prezentáció jelszóval védett-e a módosításhoz. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Visszaadja a prezentáció titkosításához használt jelszót. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Lekérdezi vagy beállítja a csak-olvasható ajánlást. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Lekérdezi vagy beállítja a csak-olvasható ajánlást. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Ez a tulajdonság értelmes, ha a prezentáció jelszóval védett. Ha igaz, akkor a dokumentum tulajdonságai titkosítva vannak a prezentáció fájlban. Ha hamis, akkor a dokumentum tulajdonságai nyilvánosak, míg a prezentáció titkosított. Olvasás/írás bool.

**Visszatérési érték:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Ez a tulajdonság értelmes, ha a prezentáció jelszóval védett. Ha igaz, akkor a dokumentum tulajdonságai titkosítva vannak a prezentáció fájlban. Ha hamis, akkor a dokumentum tulajdonságai nyilvánosak, míg a prezentáció titkosított. Olvasás/írás bool.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Visszaad egy értéket, amely jelzi, hogy ez a példány titkosított-e. Olvasás-csak bool.

Érték: igaz, ha a prezentáció titkosított fájlból lett betöltve vagy a #encrypt(String).encrypt(String) metódust hívták; egyébként hamis.

**Visszatérési érték:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Ez a tulajdonság értelmes, ha a prezentáció fájl jelszóval védett és a fájl dokumentumtulajdonságai nyilvánosak. Az igaz érték azt jelenti, hogy csak a dokumentumtulajdonságok töltődnek be egy titkosított prezentációból jelszó használata nélkül. A hamis érték azt jelenti, hogy a teljes titkosított prezentáció betöltődik a helyes jelszóval, nem csak a dokumentumtulajdonságok. Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig hamis. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak, akkor a tulajdonság értéke mindig hamis. Ha a Presentation.EncryptDocumentProperties igaz, akkor az IsOnlyDocumentPropertiesLoaded értéke mindig hamis. Olvasás-csak bool.

**Visszatérési érték:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Visszaad egy értéket, amely jelzi, hogy ez a prezentáció írásvédett-e. Olvasás-csak bool.

**Visszatérési érték:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Titkosítja a prezentációt a megadott jelszóval.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| encryptionPassword | java.lang.String | A jelszó. |
### removeEncryption() {#removeEncryption--}
```
public final void removeEncryption()
```

Eltávolítja a titkosítást.
### setWriteProtection(String password) {#setWriteProtection-java.lang.String-}
```
public final void setWriteProtection(String password)
```

Beállítja az írásvédelmet ehhez a prezentációhoz a megadott jelszóval.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | java.lang.String | A jelszó. |
### removeWriteProtection() {#removeWriteProtection--}
```
public final void removeWriteProtection()
```

Eltávolítja az írásvédelmet ebből a prezentációból.

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

Megállapítja, hogy a prezentáció jelszóval védett-e a módosításhoz.

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
| password | java.lang.String | A jelszó az ellenőrzéshez.

1. A módszer meghívása előtt ellenőrizni kell a (#isWriteProtected.isWriteProtected) tulajdonságot. 2. Ha a jelszó null vagy üres, a metódus hamisat ad vissza. |

**Visszatérési érték:**
boolean - True if the password is valid; otherwise, false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Visszaadja a prezentáció titkosításához használt jelszót. Olvasás-csak String.

**Visszatérési érték:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Lekérdezi vagy beállítja a csak-olvasható ajánlást. Olvasás/írás bool.

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


**Visszatérési érték:**
boolean
### setReadOnlyRecommended(boolean value) {#setReadOnlyRecommended-boolean-}
```
public final void setReadOnlyRecommended(boolean value)
```

Lekérdezi vagy beállítja a csak-olvasható ajánlást. Olvasás/írás bool.

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

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |