---
title: IPresentationInfo
second_title: Aspose.Slides for Android via Java API Reference
description: Information about presentation file
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
| [isWriteProtected()](#isWriteProtected--) | Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi penulisan. |
| [getLoadFormat()](#getLoadFormat--) | Mengembalikan format presentasi yang terikat. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Memeriksa apakah kata sandi benar untuk presentasi yang dilindungi dengan kata sandi buka. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Memeriksa apakah kata sandi untuk memodifikasi benar untuk presentasi yang dilindungi penulisan. |
| [readDocumentProperties()](#readDocumentProperties--) | Mengembalikan properti dokumen dari presentasi yang terikat. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Memperbarui properti dari presentasi yang terikat. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Menulis presentasi yang terikat ke aliran. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Menulis presentasi yang terikat ke file. |
### isEncrypted() {#isEncrypted--}
```
public abstract boolean isEncrypted()
```

Mengembalikan True jika presentasi yang terikat dienkripsi, jika tidak False. Boolean baca-saja.

**Mengembalikan:**
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


**Mengembalikan:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public abstract byte isWriteProtected()
```

Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi penulisan.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is write protected by a password.");
>  }
> ```


--------------------

Jika presentasi dilindungi oleh kata sandi untuk dibuka, nilai properti sama dengan NotDefined. Lihat enumerasi [NullableBool](../../com.aspose.slides/nullablebool).

**Mengembalikan:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Mengembalikan format presentasi yang terikat. Baca-saja [LoadFormat](../../com.aspose.slides/loadformat).

**Mengembalikan:**
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


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandi yang akan diperiksa.

--------------------

Ketika kata sandi null atau kosong, metode ini mengembalikan false. |

**Mengembalikan:**
boolean - True jika presentasi dilindungi dengan kata sandi buka dan kata sandi benar serta false jika tidak.

### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public abstract boolean checkWriteProtection(String password)
```

Memeriksa apakah kata sandi untuk memodifikasi benar untuk presentasi yang dilindungi penulisan.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo("pres.pptx");
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandi yang akan diperiksa.

--------------------

1. Anda harus memeriksa properti (\#isWriteProtected.isWriteProtected) sebelum memanggil metode ini. 2. Ketika kata sandi null atau kosong, metode ini mengembalikan false. |

**Mengembalikan:**
boolean - True jika presentasi dilindungi penulisan dan kata sandi benar. False jika tidak.

### readDocumentProperties() {#readDocumentProperties--}
```
public abstract IDocumentProperties readDocumentProperties()
```

Mengembalikan properti dokumen dari presentasi yang terikat.

**Mengembalikan:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Properti dokumen [IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public abstract void updateDocumentProperties(IDocumentProperties documentProperties)
```

Memperbarui properti dari presentasi yang terikat.

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


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) | Properti dokumen [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |

### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public abstract void writeBindedPresentation(OutputStream stream)
```

Menulis presentasi yang terikat ke aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran harus dapat dicari dan dapat ditulis. |

### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public abstract void writeBindedPresentation(String file)
```

Menulis presentasi yang terikat ke file.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | File presentasi. |