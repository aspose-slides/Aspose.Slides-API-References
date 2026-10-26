---
title: IOleObjectFrame
second_title: Referensi API Java Aspose.Slides untuk Android
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

| Metode | Deskripsi |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Mengembalikan objek properti isi gambar OleObject. |
| [getObjectName()](#getObjectName--) | Mengembalikan atau mengatur nama sebuah objek. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Mengembalikan atau mengatur nama sebuah objek. |
| [getEmbeddedData()](#getEmbeddedData--) | Mendapatkan informasi tentang data tertanam OLE. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Mengatur informasi tentang data tertanam OLE. |
| [getObjectProgId()](#getObjectProgId--) | Mengembalikan ProgID sebuah objek. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Mengembalikan ProgID sebuah objek. |
| [getLinkFileName()](#getLinkFileName--) | Mengembalikan jalur lengkap ke file yang ditautkan. |
| [getLinkPathLong()](#getLinkPathLong--) | Mengembalikan jalur lengkap ke file yang ditautkan. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Mengembalikan jalur lengkap ke file yang ditautkan. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Mengembalikan jalur relatif ke file yang ditautkan jika ada, jika tidak mengembalikan string kosong. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Mengembalikan nama file dari objek OLE yang tertanam |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Mengembalikan jalur dari objek OLE yang tertanam |
| [isObjectIcon()](#isObjectIcon--) | Menentukan apakah sebuah objek terlihat sebagai ikon. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Menentukan apakah sebuah objek terlihat sebagai ikon. |
| [isObjectLink()](#isObjectLink--) | Menentukan apakah sebuah objek ditautkan ke file eksternal. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Menentukan apakah objek tertanam yang ditautkan diperbarui secara otomatis ketika presentasi dibuka atau dicetak. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Menentukan apakah objek tertanam yang ditautkan diperbarui secara otomatis ketika presentasi dibuka atau dicetak. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Mengembalikan atau mengatur judul untuk ikon OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Mengembalikan atau mengatur judul untuk ikon OleObject. |
### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public abstract IPictureFillFormat getSubstitutePictureFormat()
```


Mengembalikan objek properti isi gambar OleObject. Hanya-baca [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Mengembalikan:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)
### getObjectName() {#getObjectName--}
```
public abstract String getObjectName()
```


Mengembalikan atau mengatur nama sebuah objek. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public abstract void setObjectName(String value)
```


Mengembalikan atau mengatur nama sebuah objek. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getEmbeddedData() {#getEmbeddedData--}
```
public abstract IOleEmbeddedDataInfo getEmbeddedData()
```


Mendapatkan informasi tentang data tertanam OLE. Hanya-baca [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Mengembalikan:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public abstract void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```


Mengatur informasi tentang data tertanam OLE.

--------------------

> ```
> Following example demonstrates how to change OLE embedded data
>  and its type for existing [IOleObjectFrame](../../com.aspose.slides/ioleobjectframe) object 
>  
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      OleObjectFrame oof = (OleObjectFrame) pres.getSlides().get_Item(0).getShapes().get_Item(0);
>      if (oof != null)
>      {
>          BufferedInputStream bis = null;
>          DataInputStream dis = null;
>          try {
>              File file = new File("Picture.png");
>              byte[] bytes = new byte[(int) file.length()];
>              bis = new BufferedInputStream(new FileInputStream(file));
>              dis = new DataInputStream(bis);
>              dis.readFully(bytes);
>              IOleEmbeddedDataInfo newData = new OleEmbeddedDataInfo(bytes, "png");
>              oof.setEmbeddedData(newData);
>          } finally {
>              if (dis != null) {
>                  dis.close();
>              if (bis != null)
>                  bis.close();
>              }
>          }
>      }
>  } catch (IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Data tertanam [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

--------------------

Metode ini mengubah properti objek untuk mencerminkan data baru dan mengatur flag IsObjectLink menjadi false, menunjukkan bahwa objek OLE tertanam. |

### getObjectProgId() {#getObjectProgId--}
```
public abstract String getObjectProgId()
```


Mengembalikan ProgID sebuah objek. Hanya-baca String.

**Mengembalikan:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public abstract void setObjectProgId(String value)
```


Mengembalikan ProgID sebuah objek. Hanya-baca String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public abstract String getLinkFileName()
```


Mengembalikan jalur lengkap ke file yang ditautkan. Nama file pendek akan digunakan. Hanya-baca String.

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


Mengembalikan jalur relatif ke file yang ditautkan jika ada, jika tidak mengembalikan string kosong. Hanya-baca String.

--------------------

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

--------------------

Dalam presentasi Ppt, beberapa tautan objek Ole mungkin memiliki representasi relatif.

**Mengembalikan:**
java.lang.String
### getEmbeddedFileLabel() {#getEmbeddedFileLabel--}
```
public abstract String getEmbeddedFileLabel()
```


Mengembalikan nama file dari objek OLE yang tertanam

**Mengembalikan:**
java.lang.String
### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public abstract String getEmbeddedFileName()
```


Mengembalikan jalur dari objek OLE yang tertanam

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


Menentukan apakah sebuah objek ditautkan ke file eksternal. Hanya-baca boolean.

**Mengembalikan:**
boolean
### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public abstract boolean getUpdateAutomatic()
```


Menentukan apakah objek tertanam yang ditautkan diperbarui secara otomatis ketika presentasi dibuka atau dicetak. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public abstract void setUpdateAutomatic(boolean value)
```


Menentukan apakah objek tertanam yang ditautkan diperbarui secara otomatis ketika presentasi dibuka atau dicetak. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public abstract String getSubstitutePictureTitle()
```


Mengembalikan atau mengatur judul untuk ikon OleObject. Baca/tulis String.

--------------------

Ketika IsObjectIcon == false nilai ini diabaikan. String dapat dipotong sesuai ukuran ikon OLE.

**Mengembalikan:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public abstract void setSubstitutePictureTitle(String value)
```


Mengembalikan atau mengatur judul untuk ikon OleObject. Baca/tulis String.

--------------------

Ketika IsObjectIcon == false nilai ini diabaikan. String dapat dipotong sesuai ukuran ikon OLE.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |