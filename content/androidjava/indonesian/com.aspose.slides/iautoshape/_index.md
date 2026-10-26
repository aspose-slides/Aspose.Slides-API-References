---
title: IAutoShape
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili sebuah AutoShape.
type: docs
url: /id/com.aspose.slides/iautoshape/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Mewakili AutoShape.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Mengembalikan kunci AutoShape. |
| [getTextFrame()](#getTextFrame--) | Mengembalikan objek TextFrame untuk AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Menentukan apakah autoshape ini harus diisi dengan latar belakang slide alih-alih ditentukan oleh gaya atau format isian. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Menentukan apakah autoshape ini harus diisi dengan latar belakang slide alih-alih ditentukan oleh gaya atau format isian. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Menambahkan TextFrame baru ke sebuah shape. |
| [isTextBox()](#isTextBox--) | Menentukan apakah shape merupakan kotak teks. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Mengembalikan kunci AutoShape. Baca-saja [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Mengembalikan:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Mengembalikan objek TextFrame untuk AutoShape. Baca-saja [ITextFrame](../../com.aspose.slides/itextframe).

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Menentukan apakah autoshape ini harus diisi dengan latar belakang slide alih-alih ditentukan oleh gaya atau format isian. Boolean baca/tulis.

**Mengembalikan:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Menentukan apakah autoshape ini harus diisi dengan latar belakang slide alih-alih ditentukan oleh gaya atau format isian. Boolean baca/tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Menambahkan TextFrame baru ke sebuah shape. Jika shape sudah memiliki TextFrame maka cukup mengubah teksnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks default untuk TextFrame baru. |

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe) - Objek [ITextFrame](../../com.aspose.slides/itextframe) baru.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Menentukan apakah shape merupakan kotak teks.

--------------------

Jika shape tidak ditentukan sebagai kotak teks, itu tidak berarti bahwa shape tersebut tidak dapat memiliki teks yang terlampir. Kotak teks hanyalah shape khusus dengan properti tertentu.

**Mengembalikan:**
boolean