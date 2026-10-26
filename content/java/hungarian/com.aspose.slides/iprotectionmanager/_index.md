---
title: IProtectionManager
second_title: Aspose.Slides for Java API Reference
description: A prezentáció jelszóvédelem kezelése.
type: docs
url: /hu/com.aspose.slides/iprotectionmanager/
---```
public interface IProtectionManager
```

A prezentáció jelszóvédelem kezelése.
## Metódusok

| Method | Description |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Ez a tulajdonság értelmes, ha a prezentáció jelszóval védett. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Ez a tulajdonság értelmes, ha a prezentáció jelszóval védett. |
| [isEncrypted()](#isEncrypted--) | Értéket ad vissza, amely jelzi, hogy ez a példány titkosított-e. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Ez a tulajdonság értelmes, ha a prezentáció fájl jelszóval védett és a fájl dokumentum tulajdonságai nyilvánosak. |
| [isWriteProtected()](#isWriteProtected--) | Értéket ad vissza, amely jelzi, hogy ez a prezentáció írásvédelem alatt áll. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Visszaadja a titkosítás jelszavát. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Lekérdezi vagy beállítja a csak-olvasás ajánlását. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Lekérdezi vagy beállítja a csak-olvasás ajánlását. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Titkosítja a prezentációt a megadott jelszóval. |
| [removeEncryption()](#removeEncryption--) | Eltávolítja a titkosítást. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Beállítja az írásvédelmet ehhez a prezentációhoz a megadott jelszóval. |
| [removeWriteProtection()](#removeWriteProtection--) | Eltávolítja az írásvédelmet ebből a prezentációból. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Meghatározza, hogy a prezentáció jelszóval védett-e a módosításhoz. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public abstract boolean getEncryptDocumentProperties()
```

Ez a tulajdonság értelmes, ha a prezentáció jelszóval védett. Ha igaz, akkor a dokumentum tulajdonságok titkosítva vannak a prezentáció fájlban. Ha hamis, akkor a dokumentum tulajdonságok nyilvánosak, míg a prezentáció titkosítva van. Olvasás/írás boolean.

**Visszatér:**  
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public abstract void setEncryptDocumentProperties(boolean value)
```

Ez a tulajdonság értelmes, ha a prezentáció jelszóval védett. Ha igaz, akkor a dokumentum tulajdonságok titkosítva vannak a prezentáció fájlban. Ha hamis, akkor a dokumentum tulajdonságok nyilvánosak, míg a prezentáció titkosítva van. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Értéket ad vissza, amely jelzi, hogy ez a példány titkosított-e. Csak olvasás boolean.

Érték: true, ha a prezentáció titkosított fájlból lett betöltve vagy a \#encrypt(String).encrypt(String) metódust hívták; ellenkező esetben false.

**Visszatér:**  
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public abstract boolean isOnlyDocumentPropertiesLoaded()
```

Ez a tulajdonság értelmes, ha a prezentáció fájl jelszóval védett és a fájl dokumentum tulajdonságai nyilvánosak. A true érték azt jelenti, hogy csak a dokumentum tulajdonságok kerülnek betöltésre egy titkosított prezentáció fájlból jelszó használata nélkül. A false érték azt jelenti, hogy a teljes titkosított prezentáció betöltődik a helyes jelszó használatával, nem csak a dokumentum tulajdonságok. Ha a prezentáció nincs titkosítva, akkor a tulajdonság értéke mindig false. Ha egy titkosított fájl dokumentum tulajdonságai nem nyilvánosak, akkor a tulajdonság értéke mindig false. Ha a PresentationEx.EncryptDocumentProperties true, akkor az IsOnlyDocumentPropertiesLoaded tulajdonság értéke mindig false. Csak olvasás boolean.

**Visszatér:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract boolean isWriteProtected()
```

Értéket ad vissza, amely jelzi, hogy ez a prezentáció írásvédelem alatt áll. Csak olvasás boolean.

**Visszatér:**  
boolean
### getEncryptionPassword() {#getEncryptionPassword--}
```
public abstract String getEncryptionPassword()
```

Visszaadja a titkosítás jelszavát. Csak olvasás String.

**Visszatér:**  
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public abstract boolean getReadOnlyRecommended()
```

Lekérdezi vagy beállítja a csak-olvasás ajánlását. Olvasás/írás boolean.

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

Lekérdezi vagy beállítja a csak-olvasás ajánlását. Olvasás/írás boolean.

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

Beállítja az írásvédelmet ehhez a prezentációhoz a megadott jelszóval.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | java.lang.String | A jelszó. |
### removeWriteProtection() {#removeWriteProtection--}
```
public abstract void removeWriteProtection()
```

Eltávolítja az írásvédelmet ebből a prezentációból.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Meghatározza, hogy a prezentáció jelszóval védett-e a módosításhoz.

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
| password | java.lang.String | A ellenőrzéshez használt jelszó.

1. A (\#isWriteProtected.isWriteProtected) tulajdonságot ellenőrizni kell, mielőtt meghívja ezt a metódust. 2. Ha a jelszó null vagy üres, ez a metódus false értéket ad vissza. |

**Visszatér:**  
boolean - True, ha a jelszó érvényes; egyébként false.