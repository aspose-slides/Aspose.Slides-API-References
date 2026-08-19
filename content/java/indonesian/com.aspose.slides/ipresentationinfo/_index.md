---
title: IPresentationInfo
second_title: Aspose.Slides for Java API Reference
description: Informasi tentang file presentasi
type: docs
url: /id/com.aspose.slides/ipresentationinfo/
---```
public interface IPresentationInfo
```

Informasi tentang file presentasi
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Mengembalikan True jika presentasi yang terikat dienkripsi, jika tidak False. |
| [isPasswordProtected()](#isPasswordProtected--) | Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi dengan kata sandi untuk dibuka. |
| [isWriteProtected()](#isWriteProtected--) | Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi terhadap penulisan. |
| [getLoadFormat()](#getLoadFormat--) | Mengembalikan format presentasi yang terikat. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Memeriksa apakah kata sandi benar untuk presentasi yang dilindungi dengan kata sandi buka. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Memeriksa apakah kata sandi untuk mengubah benar untuk presentasi yang dilindungi terhadap penulisan. |
| [readDocumentProperties()](#readDocumentProperties--) | Mengembalikan properti dokumen dari presentasi yang terikat. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Memperbarui properti presentasi yang terikat. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Menulis presentasi yang terikat ke aliran. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Menulis presentasi yang terikat ke file. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Mengembalikan True jika presentasi yang terikat dienkripsi, jika tidak False. Boolean read-only.

**Returns:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public abstract boolean isPasswordProtected()
```

Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi dengan kata sandi untuk dibuka.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by a password to open.");
>  }
> ```

**Returns:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi terhadap penulisan.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```

--------------------

Jika presentasi dilindungi dengan kata sandi untuk dibuka, nilai properti sama dengan NotDefined. Lihat enumerasi [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Mengembalikan format presentasi yang terikat. Read-only [LoadFormat](../../com.aspose.slides/loadformat).

**Returns:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public abstract boolean checkPassword(String password)
```

Memeriksa apakah kata sandi benar untuk presentasi yang dilindungi dengan kata sandi buka.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandi yang akan diperiksa. |

--------------------

Ketika kata sandi bernilai null atau kosong, metode ini mengembalikan false.

**Returns:**
boolean - True jika presentasi dilindungi dengan kata sandi buka dan kata sandi tersebut benar, dan false jika tidak.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Memeriksa apakah kata sandi untuk mengubah benar untuk presentasi yang dilindungi terhadap penulisan.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandi yang akan diperiksa. |

--------------------

1. Anda harus memeriksa properti (\#isWriteProtected.isWriteProtected) sebelum memanggil metode ini. 2. Ketika kata sandi bernilai null atau kosong, metode ini mengembalikan false.

**Returns:**
boolean - True jika presentasi dilindungi terhadap penulisan dan kata sandi benar. False jika tidak.
### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Mengembalikan properti dokumen dari presentasi yang terikat.

**Returns:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Properti dokumen [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Memperbarui properti presentasi yang terikat.

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

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Properti dokumen [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Menulis presentasi yang terikat ke aliran.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran harus dapat dicari dan dapat ditulis. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Menulis presentasi yang terikat ke file.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | File presentasi. |