---
title: PresentationInfo
second_title: Aspose.Slides Androidhoz Java API referencia
description: Információ a prezentációfájlról
type: docs
url: /hu/com.aspose.slides/presentationinfo/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Információ a prezentációfájlról
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Igaz értéket ad, ha a kapcsolt prezentáció titkosított, egyébként Hamis. |
| [isPasswordProtected()](#isPasswordProtected--) | Értéket ad, amely jelzi, hogy a kapcsolt prezentáció jelszóval védett-e a megnyitáshoz. |
| [isWriteProtected()](#isWriteProtected--) | Értéket ad, amely jelzi, hogy a kapcsolt prezentáció írásvédett-e. |
| [getLoadFormat()](#getLoadFormat--) | A kapcsolt prezentáció formátumát adja. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Ellenőrzi, hogy a megnyitási jelszó helyes-e egy jelszóval védett prezentáció esetén. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Ellenőrzi, hogy a módosítási jelszó helyes-e egy írásvédett prezentáció esetén. |
| [readDocumentProperties()](#readDocumentProperties--) | A kapcsolt prezentáció dokumentumtulajdonságait adja. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | A kapcsolt prezentáció tulajdonságait frissíti. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | A kapcsolt prezentációt adatfolyamba írja. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | A kapcsolt prezentációt fájlba írja. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Igaz értéket ad, ha a kapcsolt prezentáció titkosított, egyébként Hamis. Csak olvasható boolean.

**Visszatér:**  
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Értéket ad, amely jelzi, hogy a kapcsolt prezentáció jelszóval védett-e a megnyitáshoz.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

**Visszatér:**  
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Értéket ad, amely jelzi, hogy a kapcsolt prezentáció írásvédett-e.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

Ha a prezentáció jelszóval védett a megnyitáshoz, a tulajdonság értéke NotDefined.

**Visszatér:**  
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

A kapcsolt prezentáció formátumát adja. Csak olvasható [LoadFormat](../../com.aspose.slides/loadformat).

**Visszatér:**  
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Ellenőrzi, hogy a megnyitási jelszó helyes-e egy jelszóval védett prezentáció esetén.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | java.lang.String | Az ellenőrzendő jelszó. |

--------------------

Ha a jelszó null vagy üres, ez a módszer Hamist ad vissza.  

**Visszatér:**  
boolean - True if the presentation is protected with open password and the password is correct and false otherwise.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Ellenőrzi, hogy a módosítási jelszó helyes-e egy írásvédett prezentáció esetén.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | java.lang.String | Az ellenőrzendő jelszó. |

--------------------

1. Ellenőrizni kell a (\#isWriteProtected.isWriteProtected) tulajdonságot, mielőtt meghívja ezt a módszert. 2. Ha a jelszó null vagy üres, ez a módszer Hamist ad vissza. |

**Visszatér:**  
boolean - True if the presentation is write protected and the password is correct. False otherwise.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

A kapcsolt prezentáció dokumentumtulajdonságait adja.

**Visszatér:**  
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

A kapcsolt prezentáció tulajdonságait frissíti.

--------------------

> ```
> Ez a példa megmutatja, hogyan hívható meg a #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) metódus,
>  hogy frissítse a dokumentumtulajdonságokat, amelyeket a #readDocumentProperties.readDocumentProperties metódus hívása ad vissza.
>  
>  IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  IDocumentProperties props = info.readDocumentProperties();
>  props.setSubject("New subject");
>  props.setLastSavedTime(Calendar.getInstance().getTime());
>  info.updateDocumentProperties(props);
>  info.writeBindedPresentation("new_pres.pptx");
> ```

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

A kapcsolt prezentációt adatfolyamba írja.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | A folyamnak kereshetőnek és írhatónak kell lennie. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

A kapcsolt prezentációt fájlba írja.

**Paraméterek:**  
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | A prezentáció fájlja. |