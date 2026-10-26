---
title: IPresentationInfo
second_title: Aspose.Slides for Java API Reference
description: Information about presentation file
type: docs
url: /hu/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Információ a prezentációfájlról
## Módszerek

| Metódus | Leírás |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | True-t ad, ha a kötött prezentáció titkosított, különben False. |
| [isPasswordProtected()](#isPasswordProtected--) | Értéket ad, amely jelzi, hogy a kötött prezentáció jelszóval védett-e a megnyitáshoz. |
| [isWriteProtected()](#isWriteProtected--) | Értéket ad, amely jelzi, hogy a kötött prezentáció írásvédelem alatt áll. |
| [getLoadFormat()](#getLoadFormat--) | A kötött prezentáció formátumát adja vissza. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Ellenőrzi, hogy a jelszó helyes-e egy nyitó jelszóval védett prezentációhoz. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Ellenőrzi, hogy a módosítási jelszó helyes-e egy írásvédett prezentáció esetén. |
| [readDocumentProperties()](#readDocumentProperties--) | A kötött prezentáció dokumentumtulajdonságait adja vissza. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Frissíti a kötött prezentáció tulajdonságait. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | A kötött prezentációt kiírja egy adatfolyamba. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | A kötött prezentációt fájlba írja. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```


True-t ad, ha a kötött prezentáció titkosított, különben False. Csak-olvasható boolean.

**Visszatér:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```


Értéket ad, amely jelzi, hogy a kötött prezentáció jelszóval védett-e a megnyitáshoz.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```


**Visszatér:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```


Értéket ad, amely jelzi, hogy a kötött prezentáció írásvédelem alatt áll.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

Ha a prezentáció jelszóval védett a megnyitáshoz, a tulajdonság értéke NotDefined. Lásd a [NullableBool](../../com.aspose.slides/nullablebool) felsorolást.

**Visszatér:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```


A kötött prezentáció formátumát adja vissza. Csak-olvasható [LoadFormat](../../com.aspose.slides/loadformat).

**Visszatér:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```


Ellenőrzi, hogy a jelszó helyes-e egy nyitó jelszóval védett prezentációhoz.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | java.lang.String | A ellenőrzendő jelszó.

--------------------

Ha a jelszó null vagy üres, ez a metódus false-t ad vissza.

**Visszatér:**
boolean - True, ha a prezentáció nyitó jelszóval védett, a jelszó helyes, egyébként false.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```


Ellenőrzi, hogy a módosítási jelszó helyes-e egy írásvédett prezentáció esetén.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| password | java.lang.String | A ellenőrzendő jelszó.

--------------------

1. Ellenőriznie kell a (\#isWriteProtected.isWriteProtected) tulajdonságot, mielőtt ezt a metódust meghívná. 2. Ha a jelszó null vagy üres, ez a metódus false-t ad vissza.

**Visszatér:**
boolean - True, ha a prezentáció írásvédett és a jelszó helyes. False egyébként.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```


A kötött prezentáció dokumentumtulajdonságait adja vissza.

**Visszatér:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Dokumentumtulajdonságok [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```


Frissíti a kötött prezentáció tulajdonságait.

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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Dokumentumtulajdonságok [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```


A kötött prezentációt kiírja egy adatfolyamba.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| stream | java.io.OutputStream | A folyamot kereshetőnek és írhatónak kell lennie. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```


A kötött prezentációt fájlba írja.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| file | java.lang.String | Prezentációfájl. |