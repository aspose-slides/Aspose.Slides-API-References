---
title: OleObjectFrame
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili objek OLE pada slide.
type: docs
url: /id/com.aspose.slides/oleobjectframe/
---
**Warisan:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GraphicalObject](../../com.aspose.slides/graphicalobject)

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IOleObjectFrame](../../com.aspose.slides/ioleobjectframe)
```
public class OleObjectFrame extends GraphicalObject implements IOleObjectFrame
```

Mewakili objek OLE pada slide.

--------------------

> ```
> The following example shows how to accessing OLE Object frames.
>  
>  // Memuat PPTX ke objek presentasi
>  Presentation pres = new Presentation("AccessingOLEObjectFrame.pptx");
>  try {
>      // Mengakses slide pertama
>      ISlide sld = pres.getSlides().get_Item(0);
>      // Mengubah tipe shape menjadi OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Membaca OLE Object dan menuliskannya ke disk
>      if (oleObjectFrame != null) {
>          // Mendapatkan data file yang disematkan
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Mendapatkan ekstensi file yang disematkan
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Membuat jalur untuk menyimpan file yang diekstrak
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Menyimpan data yang diekstrak
>          Files.write(Paths.get(extractedPath), data);
>      }
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSubstitutePictureFormat()](#getSubstitutePictureFormat--) | Mengembalikan objek properti pengisian gambar OleObject. |
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Mengembalikan atau mengatur judul untuk ikon OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Mengembalikan atau mengatur judul untuk ikon OleObject. |
| [getObjectName()](#getObjectName--) | Mengembalikan atau mengatur nama sebuah objek. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Mengembalikan atau mengatur nama sebuah objek. |
| [getObjectProgId()](#getObjectProgId--) | Mengembalikan ProgID dari sebuah objek. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Mengembalikan ProgID dari sebuah objek. |
| [getLinkFileName()](#getLinkFileName--) | Mengembalikan jalur lengkap ke file yang ditautkan. |
| [getLinkPathLong()](#getLinkPathLong--) | Mengembalikan jalur lengkap ke file yang ditautkan. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Mengembalikan jalur lengkap ke file yang ditautkan. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Mengembalikan jalur relatif ke file yang ditautkan jika ada, jika tidak mengembalikan string kosong. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Mengembalikan nama file dari objek OLE yang disematkan |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Mengembalikan jalur objek OLE yang disematkan |
| [getEmbeddedData()](#getEmbeddedData--) | Mengambil atau mengatur informasi tentang data OLE yang disematkan. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Mengatur informasi tentang data OLE yang disematkan. |
| [isObjectIcon()](#isObjectIcon--) | Menentukan apakah sebuah objek terlihat sebagai ikon. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Menentukan apakah sebuah objek terlihat sebagai ikon. |
| [isObjectLink()](#isObjectLink--) | Menentukan apakah sebuah objek ditautkan ke file eksternal. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Menentukan apakah objek tersemat yang ditautkan diperbarui secara otomatis saat presentasi dibuka atau dicetak. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Menentukan apakah objek tersemat yang ditautkan diperbarui secara otomatis saat presentasi dibuka atau dicetak. |

### getSubstitutePictureFormat() {#getSubstitutePictureFormat--}
```
public final IPictureFillFormat getSubstitutePictureFormat()
```

Mengembalikan objek properti pengisian gambar OleObject. Hanya-baca [IPictureFillFormat](../../com.aspose.slides/ipicturefillformat).

**Mengembalikan:**
[IPictureFillFormat](../../com.aspose.slides/ipicturefillformat)

### getSubstitutePictureTitle() {#getSubstitutePictureTitle--}
```
public final String getSubstitutePictureTitle()
```

Mengembalikan atau mengatur judul untuk ikon OleObject. Baca/tulis String.

--------------------

Ketika IsObjectIcon == false nilai ini diabaikan. String dapat dipotong sesuai ukuran ikon Ole.

**Mengembalikan:**
java.lang.String

### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Mengembalikan atau mengatur judul untuk ikon OleObject. Baca/tulis String.

--------------------

Ketika IsObjectIcon == false nilai ini diabaikan. String dapat dipotong sesuai ukuran ikon Ole.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Mengembalikan atau mengatur nama sebuah objek. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Mengembalikan atau mengatur nama sebuah objek. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Mengembalikan ProgID dari sebuah objek. Hanya-baca String.

**Mengembalikan:**
java.lang.String

### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Mengembalikan ProgID dari sebuah objek. Hanya-baca String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkFileName() {#getLinkFileName--}
```
public final String getLinkFileName()
```

Mengembalikan jalur lengkap ke file yang ditautkan. Nama file pendek akan digunakan. Hanya-baca String.

**Mengembalikan:**
java.lang.String

### getLinkPathLong() {#getLinkPathLong--}
```
public final String getLinkPathLong()
```

Mengembalikan jalur lengkap ke file yang ditautkan. Nama file panjang akan digunakan. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setLinkPathLong(String value) {#setLinkPathLong-java.lang.String-}
```
public final void setLinkPathLong(String value)
```

Mengembalikan jalur lengkap ke file yang ditautkan. Nama file panjang akan digunakan. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getLinkPathRelative() {#getLinkPathRelative--}
```
public final String getLinkPathRelative()
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
public final String getEmbeddedFileLabel()
```

Mengembalikan nama file dari objek OLE yang disematkan

**Mengembalikan:**
java.lang.String

### getEmbeddedFileName() {#getEmbeddedFileName--}
```
public final String getEmbeddedFileName()
```

Mengembalikan jalur objek OLE yang disematkan

**Mengembalikan:**
java.lang.String

### getEmbeddedData() {#getEmbeddedData--}
```
public final IOleEmbeddedDataInfo getEmbeddedData()
```

Mengambil atau mengatur informasi tentang data OLE yang disematkan. Baca/tulis [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Mengembalikan:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Mengatur informasi tentang data OLE yang disematkan.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Data yang disematkan [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) |

Metode ini mengubah properti objek untuk mencerminkan data baru dan mengatur flag IsObjectLink menjadi false, menunjukkan bahwa objek OLE disematkan. |

### isObjectIcon() {#isObjectIcon--}
```
public final boolean isObjectIcon()
```

Menentukan apakah sebuah objek terlihat sebagai ikon. Baca/tulis boolean .

**Mengembalikan:**
boolean

### setObjectIcon(boolean value) {#setObjectIcon-boolean-}
```
public final void setObjectIcon(boolean value)
```

Menentukan apakah sebuah objek terlihat sebagai ikon. Baca/tulis boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### isObjectLink() {#isObjectLink--}
```
public final boolean isObjectLink()
```

Menentukan apakah sebuah objek ditautkan ke file eksternal. Hanya-baca boolean .

**Mengembalikan:**
boolean

### getUpdateAutomatic() {#getUpdateAutomatic--}
```
public final boolean getUpdateAutomatic()
```

Menentukan apakah objek tersemat yang ditautkan diperbarui secara otomatis saat presentasi dibuka atau dicetak. Baca/tulis boolean .

**Mengembalikan:**
boolean

### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Menentukan apakah objek tersemat yang ditautkan diperbarui secara otomatis saat presentasi dibuka atau dicetak. Baca/tulis boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |