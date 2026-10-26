---
title: ProtectionManager
second_title: Aspose.Slides Androidra a Java API hivatkozás alapján
description: Prezentáció jelszóvédelmi kezelése.
type: docs
url: /hu/com.aspose.slides/protectionmanager/
---
**Öröklődés:**
java.lang.Object

**Minden Megvalósított Interfész:**
[com.aspose.slides.IProtectionManager](../../com.aspose.slides/iprotectionmanager)
```
public final class ProtectionManager implements IProtectionManager
```

Prezentáció jelszóvédelmi kezelése.
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [getEncryptDocumentProperties()](#getEncryptDocumentProperties--) | Ez a tulajdonság értelmes, ha a prezentáció jelszóval védett. |
| [setEncryptDocumentProperties(boolean value)](#setEncryptDocumentProperties-boolean-) | Ez a tulajdonság értelmes, ha a prezentáció jelszóval védett. |
| [isEncrypted()](#isEncrypted--) | Lekér egy értéket, amely jelzi, hogy ez a példány titkosított-e. |
| [isOnlyDocumentPropertiesLoaded()](#isOnlyDocumentPropertiesLoaded--) | Ez a tulajdonság értelmes, ha a prezentációfájl jelszóval van védve, és a fájl dokumentumtulajdonságai nyilvánosak. |
| [isWriteProtected()](#isWriteProtected--) | Lekér egy értéket, amely jelzi, hogy ez a prezentáció írásvédett-e. |
| [encrypt(String encryptionPassword)](#encrypt-java.lang.String-) | Titkosítja a Presentation-t a megadott jelszóval. |
| [removeEncryption()](#removeEncryption--) | Eltávolítja a titkosítást. |
| [setWriteProtection(String password)](#setWriteProtection-java.lang.String-) | Beállítja az írásvédelmet ehhez a Presentation-hez a megadott jelszóval. |
| [removeWriteProtection()](#removeWriteProtection--) | Eltávolítja az írásvédelmet ebből a Presentation-ből. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Megállapítja, hogy egy Presentation módosításra jelszóval védett-e. |
| [getEncryptionPassword()](#getEncryptionPassword--) | Lekér egy jelszót, amely a Presentation titkosításához használatos. |
| [getReadOnlyRecommended()](#getReadOnlyRecommended--) | Lekér vagy beállítja a csak-olvasás ajánlást. |
| [setReadOnlyRecommended(boolean value)](#setReadOnlyRecommended-boolean-) | Lekér vagy beállítja a csak-olvasás ajánlást. |
### getEncryptDocumentProperties() {#getEncryptDocumentProperties--}
```
public final boolean getEncryptDocumentProperties()
```

Ez a tulajdonság értelmes, ha a prezentáció jelszóval védett. Ha igaz, akkor a dokumentumtulajdonságok titkosítva vannak a prezentációfájlban. Ha hamis, akkor a dokumentumtulajdonságok nyilvánosak, míg a prezentáció titkosított. Olvasás/írás boolean.

**Visszatérési érték:**
boolean
### setEncryptDocumentProperties(boolean value) {#setEncryptDocumentProperties-boolean-}
```
public final void setEncryptDocumentProperties(boolean value)
```

Ez a tulajdonság értelmes, ha a prezentáció jelszóval védett. Ha igaz, akkor a dokumentumtulajdonságok titkosítva vannak a prezentációfájlban. Ha hamis, akkor a dokumentumtulajdonságok nyilvánosak, míg a prezentáció titkosított. Olvasás/írás boolean.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | boolean |  |

### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Lekér egy értéket, amely jelzi, hogy ez a példány titkosított-e. Csak-olvasás boolean.

Érték: true, ha a prezentáció titkosított fájlból volt betöltve vagy a \#encrypt(String).encrypt(String) metódus lett meghívva; egyébként false.

**Visszatérési érték:**
boolean
### isOnlyDocumentPropertiesLoaded() {#isOnlyDocumentPropertiesLoaded--}
```
public final boolean isOnlyDocumentPropertiesLoaded()
```

Ez a tulajdonság értelmes, ha a prezentációfájl jelszóval védett, és a fájl dokumentumtulajdonságai nyilvánosak. Az igaz érték azt jelenti, hogy csak a dokumentumtulajdonságok lettek betöltve egy titkosított prezentációfájlból jelszó használata nélkül. A hamis érték azt jelenti, hogy a teljes titkosított prezentációt a helyes jelszóval töltötték be, nem csak a dokumentumtulajdonságok. Ha a prezentáció nincs titkosítva, a tulajdonság értéke mindig hamis. Ha egy titkosított fájl dokumentumtulajdonságai nem nyilvánosak, a tulajdonság értéke mindig hamis. Ha a Presentation.EncryptDocumentProperties igaz, akkor az IsOnlyDocumentPropertiesLoaded értéke mindig hamis. Csak-olvasás boolean.

**Visszatérési érték:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final boolean isWriteProtected()
```

Lekér egy értéket, amely jelzi, hogy ez a prezentáció írásvédett-e. Csak-olvasás boolean.

**Visszatérési érték:**
boolean
### encrypt(String encryptionPassword) {#encrypt-java.lang.String-}
```
public final void encrypt(String encryptionPassword)
```

Titkosítja a Presentation-t a megadott jelszóval.

--------------------

> ```
> A következő példa kód megmutatja, hogyan lehet titkosítani egy PowerPoint Presentation-t.
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

Beállítja az írásvédelmet ehhez a Presentation-hez a megadott jelszóval.

--------------------

> ```
> A következő példakód megmutatja, hogyan lehet írásvédelmet beállítani egy prezentációra.
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

Eltávolítja az írásvédelmet ebből a Presentation-ből.

--------------------

> ```
> Ez a mintakód megmutatja, hogyan lehet eltávolítani az írásvédelmet egy PowerPoint Presentation-ből.
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

Megállapítja, hogy egy Presentation módosításra jelszóval védett-e.

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
| password | java.lang.String | A jelszó a ellenőrzéshez.

1. Ellenőrizni kell a (\#isWriteProtected.isWriteProtected) tulajdonságot, mielőtt meghívná ezt a metódust. 2. Ha a jelszó null vagy üres, a metódus false értéket ad vissza. |

**Visszatérési érték:**
boolean - True, ha a jelszó érvényes; egyébként false.
### getEncryptionPassword() {#getEncryptionPassword--}
```
public final String getEncryptionPassword()
```

Lekér egy jelszót, amely a Presentation titkosításához használatos. Csak-olvasás String.

**Visszatérési érték:**
java.lang.String
### getReadOnlyRecommended() {#getReadOnlyRecommended--}
```
public final boolean getReadOnlyRecommended()
```

Lekér vagy beállítja a csak-olvasás ajánlást. Olvasás/írás boolean.

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

Lekér vagy beállítja a csak-olvasás ajánlást. Olvasás/írás boolean.

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