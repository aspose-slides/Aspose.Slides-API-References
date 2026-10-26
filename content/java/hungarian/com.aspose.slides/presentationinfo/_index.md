---
title: PresentationInfo
second_title: Aspose.Slides Java API referencia
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
| [isEncrypted()](#isEncrypted--) | True értéket ad, ha a kötött prezentáció titkosított, különben False. Csak olvasható boolean. |
| [isPasswordProtected()](#isPasswordProtected--) | Értéket ad, amely jelzi, hogy a kötött prezentáció jelszóval védett-e a megnyitáshoz. |
| [isWriteProtected()](#isWriteProtected--) | Értéket ad, amely jelzi, hogy a kötött prezentáció írásvédett-e. |
| [getLoadFormat()](#getLoadFormat--) | A kötött prezentáció formátumát adja meg. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Ellenőrzi, hogy egy jelszó helyes-e egy nyitó jelszóval védett prezentációhoz. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Ellenőrzi, hogy a módosítási jelszó helyes-e egy írásvédett prezentációhoz. |
| [readDocumentProperties()](#readDocumentProperties--) | A kötött prezentáció dokumentumtulajdonságait adja vissza. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | A kötött prezentáció tulajdonságait frissíti. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | A kötött prezentációt adatfolyamra írja. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | A kötött prezentációt fájlba írja. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

True értéket ad, ha a kötött prezentáció titkosított, különben False. Csak olvasható boolean.

**Visszatér:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Értéket ad, amely jelzi, hogy a kötött prezentáció jelszóval védett-e a megnyitáshoz.

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

Értéket ad, amely jelzi, hogy a kötött prezentáció írásvédett-e.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```

--------------------

Ha a prezentáció jelszóval védett a megnyitáshoz, a tulajdonság értéke egyenlő a NotDefined értékkel.

**Visszatér:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

A kötött prezentáció formátumát adja meg. Csak olvasható [LoadFormat](../../com.aspose.slides/loadformat).

**Visszatér:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Ellenőrzi, hogy egy jelszó helyes-e egy nyitó jelszóval védett prezentációhoz.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | java.lang.String | Az ellenőrzendő jelszó. |

Ha a jelszó null vagy üres, ez a metódus false értéket ad vissza.

**Visszatér:**
boolean - True, ha a prezentáció nyitó jelszóval védett és a jelszó helyes, egyébként false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Ellenőrzi, hogy a módosítási jelszó helyes-e egy írásvédett prezentációhoz.

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

1. A metódus meghívása előtt ellenőrizni kell a (\#isWriteProtected.isWriteProtected) tulajdonságot.  
2. Ha a jelszó null vagy üres, ez a metódus false értéket ad vissza.

**Visszatér:**
boolean - True, ha a prezentáció írásvédett és a jelszó helyes. False egyébként.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

A kötött prezentáció dokumentumtulajdonságait adja vissza.

**Visszatér:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

A kötött prezentáció tulajdonságait frissíti.

--------------------

> ```
> This sample shows how to call the #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) method to
>  update the document properties returned by call of the #readDocumentProperties.readDocumentProperties method.
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

A kötött prezentációt adatfolyamra írja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | Az adatfolyamnak kereshetőnek és írhatónak kell lennie. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

A kötött prezentációt fájlba írja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Prezentáció fájl. |