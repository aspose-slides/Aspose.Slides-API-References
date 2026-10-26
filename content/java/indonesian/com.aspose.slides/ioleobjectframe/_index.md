---
title: IOleObjectFrame
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili objek OLE pada slide.
type: docs
url: /id/com.aspose.slides/ioleobjectframe/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IGraphicalObject](../../com.aspose.slides/igraphicalobject)
```
public interface IOleObjectFrame extends IGraphicalObject
```

Mewakili objek OLE pada slide.
## Metode

| Method | Description |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Mengembalikan objek properti pengisian gambar OleObject. |
| [getObjectName()](#getObjectName--) | Mengembalikan atau mengatur nama suatu objek. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Mengembalikan atau mengatur nama suatu objek. |
| [getEmbeddedData()](#getEmbeddedData--) | Mengambil informasi tentang data tersemat OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Mengatur informasi tentang data tersemat OLE. |
| [getObjectProgId()](#getObjectProgId--) | Mengembalikan ProgID suatu objek. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Mengembalikan ProgID suatu objek. |
| [getLinkFileName()](#getLinkFileName--) | Mengembalikan jalur lengkap ke file yang ditautkan. |
| [getLinkPathLong()](#getLinkPathLong--) | Mengembalikan jalur lengkap ke file yang ditautkan. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Mengembalikan jalur lengkap ke file yang ditautkan. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Mengembalikan jalur relatif ke file yang ditautkan jika ada, jika tidak mengembalikan string kosong. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Mengembalikan nama file dari objek OLE yang tersemat |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Mengembalikan jalur objek OLE yang tersemat |
| [isObjectIcon()](#isObjectIcon--) | Menentukan apakah sebuah objek terlihat sebagai ikon. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Menentukan apakah sebuah objek terlihat sebagai ikon. |
| [isObjectLink()](#isObjectLink--) | Menentukan apakah sebuah objek ditautkan ke file eksternal. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Menentukan apakah objek tersemat yang ditautkan diperbarui secara otomatis ketika presentasi dibuka atau dicetak. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Menentukan apakah objek tersemat yang ditautkan diperbarui secara otomatis ketika presentasi dibuka atau dicetak. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Mengembalikan atau mengatur judul untuk ikon OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Mengembalikan atau mengatur judul untuk ikon OleObject. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Mengembalikan objek properti pengisian gambar OleObject. Baca-saja [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Mengembalikan:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```


Mengembalikan atau mengatur nama suatu objek. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```


Mengembalikan atau mengatur nama suatu objek. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```


Mengambil informasi tentang data tersemat OLE. Baca-saja [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Mengembalikan:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


Mengatur informasi tentang data tersemat OLE.

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(Files.readAllBytes(Paths.get("Picture.png")), "png");
>          oof.setEmbeddedData(newData);
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Data tersemat [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

Metode ini mengubah properti objek untuk mencerminkan data baru dan mengatur flag IsObjectLink menjadi false, menunjukkan bahwa objek OLE tertanam. |

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```


Mengembalikan ProgID suatu objek. Baca-saja String.

**Mengembalikan:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```


Mengembalikan ProgID suatu objek. Baca-saja String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```


Mengembalikan jalur lengkap ke file yang ditautkan. Nama file pendek akan digunakan. Baca-saja String.

**Mengembalikan:**
java.lang.String
### getLinkPathLong() {#getLinkPathLong--}
```
public abstract String getLinkPathLong()
```


Mengembalikan jalur lengkap ke file yang ditautkan. Nama file panjang akan digunakan. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public abstract void setLinkPathLong(String value)
```


Mengembalikan jalur lengkap ke file yang ditautkan. Nama file panjang akan digunakan. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public abstract String getLinkPathRelative()
```


Mengembalikan jalur relatif ke file yang ditautkan jika ada, jika tidak mengembalikan string kosong. Baca-saja String.

> ```
> Presentation presentation = new Presentation("demo.ppt");
>  try {
>      IOleObjectFrame oleFrame = (IOleObjectFrame)presentation.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oleFrame != null)
>      {
>          System.out.println("The relative path: " + oleFrame.getLinkPathRelative());
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


Dalam presentasi Ppt, beberapa tautan objek Ole mungkin memiliki representasi relatif.

**Mengembalikan:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```


Mengembalikan nama file dari objek OLE yang tersemat

**Mengembalikan:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```


Mengembalikan jalur objek OLE yang tersemat

**Mengembalikan:**
java.lang.String
### isObjectIcon() {#isObjectIcon--}
```
public abstract boolean isObjectIcon()
```


Menentukan apakah sebuah objek terlihat sebagai ikon. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public abstract void setObjectIcon(boolean value)
```


Menentukan apakah sebuah objek terlihat sebagai ikon. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public abstract boolean isObjectLink()
```


Menentukan apakah sebuah objek ditautkan ke file eksternal. Baca-saja boolean.

**Mengembalikan:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```


Menentukan apakah objek tersemat yang ditautkan diperbarui secara otomatis ketika presentasi dibuka atau dicetak. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```


Menentukan apakah objek tersemat yang ditautkan diperbarui secara otomatis ketika presentasi dibuka atau dicetak. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```


Mengembalikan atau mengatur judul untuk ikon OleObject. Baca/tulis String.

When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the OLE icon.

**Mengembalikan:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```


Mengembalikan atau mengatur judul untuk ikon OleObject. Baca/tulis String.

When IsObjectIcon == false this value is ignored. The string can be truncated according to the size of the OLE icon.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |