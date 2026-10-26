---
title: IAutoShape
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili sebuah AutoShape.
type: docs
url: /id/com.aspose.slides/iautoshape/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IAutoShape extends IGeometryShape
```

Mewakili sebuah AutoShape.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAutoShapeLock()](#getAutoShapeLock--) | Mengembalikan locks AutoShape. |
| [getTextFrame()](#getTextFrame--) | Mengembalikan objek TextFrame untuk AutoShape. |
| [getUseBackgroundFill()](#getUseBackgroundFill--) | Menentukan apakah autoshape ini harus diisi dengan isi latar belakang slide alih-alih yang ditentukan oleh gaya atau format isi. |
| [setUseBackgroundFill(boolean value)](#setUseBackgroundFill-boolean-) | Menentukan apakah autoshape ini harus diisi dengan isi latar belakang slide alih-alih yang ditentukan oleh gaya atau format isi. |
| [addTextFrame(String text)](#addTextFrame-java.lang.String-) | Menambahkan TextFrame baru ke sebuah shape. |
| [isTextBox()](#isTextBox--) | Menentukan apakah shape adalah text box. |
### getAutoShapeLock() {#getAutoShapeLock--}
```
public abstract IAutoShapeLock getAutoShapeLock()
```


Mengembalikan locks AutoShape. Hanya-baca [IAutoShapeLock](../../com.aspose.slides/iautoshapelock).

**Mengembalikan:**
[IAutoShapeLock](../../com.aspose.slides/iautoshapelock)
### getTextFrame() {#getTextFrame--}
```
public abstract ITextFrame getTextFrame()
```


Mengembalikan objek TextFrame untuk AutoShape. Hanya-baca [ITextFrame](../../com.aspose.slides/itextframe).

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe)
### getUseBackgroundFill() {#getUseBackgroundFill--}
```
public abstract boolean getUseBackgroundFill()
```


Menentukan apakah autoshape ini harus diisi dengan isi latar belakang slide alih-alih yang ditentukan oleh gaya atau format isi. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setUseBackgroundFill(boolean value) {#setUseBackgroundFill-boolean-}
```
public abstract void setUseBackgroundFill(boolean value)
```


Menentukan apakah autoshape ini harus diisi dengan isi latar belakang slide alih-alih yang ditentukan oleh gaya atau format isi. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### addTextFrame(String text) {#addTextFrame-java.lang.String-}
```
public abstract ITextFrame addTextFrame(String text)
```


Menambahkan TextFrame baru ke sebuah shape. Jika shape sudah memiliki TextFrame maka hanya mengubah teksnya.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| text | java.lang.String | Teks bawaan untuk TextFrame baru. |

**Mengembalikan:**
[ITextFrame](../../com.aspose.slides/itextframe) - Objek [ITextFrame](../../com.aspose.slides/itextframe) baru.
### isTextBox() {#isTextBox--}
```
public abstract boolean isTextBox()
```


Menentukan apakah shape adalah text box.

--------------------

Jika shape tidak ditentukan sebagai text box tidak berarti bahwa ia tidak dapat memiliki teks yang terlampir padanya. Text box hanyalah shape khusus dengan properti tertentu.

**Mengembalikan:**
boolean