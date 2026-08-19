---
title: PresentationInfo
second_title: Referensi API Aspose.Slides untuk Java
description: Informasi tentang file presentasi
type: docs
url: /id/com.aspose.slides/presentationinfo/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPresentationInfo](../../com.aspose.slides/ipresentationinfo)
```
public final class PresentationInfo implements IPresentationInfo
```

Informasi tentang file presentasi
## Metode

| Metode | Deskripsi |
| --- | --- |
| [isEncrypted()](#isEncrypted--) | Mengembalikan True jika presentasi yang terikat terenkripsi, jika tidak False. |
| [isPasswordProtected()](#isPasswordProtected--) | Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi oleh kata sandi untuk dibuka. |
| [isWriteProtected()](#isWriteProtected--) | Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi dari penulisan. |
| [getLoadFormat()](#getLoadFormat--) | Mengembalikan format presentasi yang terikat. |
| [checkPassword(String password)](#checkPassword-java.lang.String-) | Memeriksa apakah kata sandi benar untuk sebuah presentasi yang dilindungi dengan kata sandi buka. |
| [checkWriteProtection(String password)](#checkWriteProtection-java.lang.String-) | Memeriksa apakah kata sandi untuk mengubah benar untuk presentasi yang dilindungi dari penulisan. |
| [readDocumentProperties()](#readDocumentProperties--) | Mengembalikan properti dokumen dari presentasi yang terikat. |
| [updateDocumentProperties(IDocumentProperties documentProperties)](#updateDocumentProperties-com.aspose.slides.IDocumentProperties-) | Memperbarui properti presentasi yang terikat. |
| [writeBindedPresentation(OutputStream stream)](#writeBindedPresentation-java.io.OutputStream-) | Menulis presentasi yang terikat ke aliran. |
| [writeBindedPresentation(String file)](#writeBindedPresentation-java.lang.String-) | Menulis presentasi yang terikat ke file. |
### isEncrypted() {#isEncrypted--}
```
public final boolean isEncrypted()
```

Mengembalikan True jika presentasi yang terikat terenkripsi, jika tidak False. Boolean hanya-baca.

**Mengembalikan:**
boolean
### isPasswordProtected() {#isPasswordProtected--}
```
public final boolean isPasswordProtected()
```

Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi oleh kata sandi untuk dibuka.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isPasswordProtected())
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


**Mengembalikan:**
boolean
### isWriteProtected() {#isWriteProtected--}
```
public final byte isWriteProtected()
```

Mengembalikan nilai yang menunjukkan apakah presentasi yang terikat dilindungi dari penulisan.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      System.out.println("The presentation '" + presentationFilePath + "' is protected by password to open.");
>  }
> ```


--------------------

Jika presentasi dilindungi oleh kata sandi untuk dibuka, nilai properti sama dengan NotDefined.

**Mengembalikan:**
byte
### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Mengembalikan format presentasi yang terikat. Hanya-baca [LoadFormat](../../com.aspose.slides/loadformat).

**Mengembalikan:**
int
### checkPassword(String password) {#checkPassword-java.lang.String-}
```
public final boolean checkPassword(String password)
```

Memeriksa apakah kata sandi benar untuk sebuah presentasi yang dilindungi dengan kata sandi buka.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  boolean isPasswordCorrect = info.checkPassword("my_password");
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandi untuk diperiksa. |
--------------------

Ketika kata sandi bernilai null atau kosong, metode ini mengembalikan false. |

**Mengembalikan:**
boolean - True jika presentasi dilindungi dengan kata sandi buka dan kata sandi tersebut benar, serta false jika tidak.
### checkWriteProtection(String password) {#checkWriteProtection-java.lang.String-}
```
public final boolean checkWriteProtection(String password)
```

Memeriksa apakah kata sandi untuk mengubah benar untuk sebuah presentasi yang dilindungi dari penulisan.

--------------------

> ```
> IPresentationInfo info = PresentationFactory.getInstance().getPresentationInfo(presentationFilePath);
>  if (info.isWriteProtected() == NullableBool.True)
>  {
>      boolean isWriteProtectedByPassword = info.checkWriteProtection("my_password");
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| password | java.lang.String | Kata sandi untuk diperiksa. |
--------------------

1. Anda harus memeriksa properti (\#isWriteProtected.isWriteProtected) sebelum memanggil metode ini. 2. Ketika kata sandi bernilai null atau kosong, metode ini mengembalikan false. |

**Mengembalikan:**
boolean - True jika presentasi dilindungi dari penulisan dan kata sandi benar. False jika tidak.
### readDocumentProperties() {#readDocumentProperties--}
```
public final IDocumentProperties readDocumentProperties()
```

Mengembalikan properti dokumen dari presentasi yang terikat.

**Mengembalikan:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### updateDocumentProperties(IDocumentProperties documentProperties) {#updateDocumentProperties-com.aspose.slides.IDocumentProperties-}
```
public final void updateDocumentProperties(IDocumentProperties documentProperties)
```

Memperbarui properti presentasi yang terikat.

--------------------

> ``` 
> Contoh ini menunjukkan cara memanggil metode #updateDocumentProperties(IDocumentProperties).updateDocumentProperties(IDocumentProperties) untuk
>  memperbarui properti dokumen yang dikembalikan oleh pemanggilan metode #readDocumentProperties.readDocumentProperties.
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
| documentProperties | [IDocumentProperties](../../com.aspose.slides/idocumentproperties) |  |
### writeBindedPresentation(OutputStream stream) {#writeBindedPresentation-java.io.OutputStream-}
```
public final void writeBindedPresentation(OutputStream stream)
```

Menulis presentasi yang terikat ke aliran.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran harus dapat dicari dan dapat ditulis. |
### writeBindedPresentation(String file) {#writeBindedPresentation-java.lang.String-}
```
public final void writeBindedPresentation(String file)
```

Menulis presentasi yang terikat ke file.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| file | java.lang.String | File presentasi. |