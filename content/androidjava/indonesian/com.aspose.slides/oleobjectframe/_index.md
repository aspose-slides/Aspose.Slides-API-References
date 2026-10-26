---
title: OleObjectFrame
second_title: Aspose.Slides untuk Android melalui Referensi API Java
description: Mewakili objek OLE pada slide.
type: docs
url: /id/com.aspose.slides/oleobjectframe/
---
**Pewarisan:**
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
>      // Mengubah shape menjadi OleObjectFrame
>      OleObjectFrame oleObjectFrame = (OleObjectFrame) sld.getShapes().get_Item(0);
>      // Membaca OLE Object dan menulisnya ke disk
>      if (oleObjectFrame != null) {
>          // Mendapatkan data file yang disematkan
>          byte[] data = oleObjectFrame.getEmbeddedData().getEmbeddedFileData();
>          // Mendapatkan ekstensi file yang disematkan
>          String fileExtension = oleObjectFrame.getEmbeddedData().getEmbeddedFileExtension();
>          // Membuat path untuk menyimpan file yang diekstrak
>          String extractedPath = "excelFromOLE_out" + fileExtension;
>          // Menyimpan data yang diekstrak
>          FileOutputStream fos = null;
>          try {
>              fos = new FileOutputStream(extractedPath);
>              fos.write(data);
>          } finally {
>              if (fos != null) fos.close();
>          }
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
| [getSubstitutePictureTitle()](#getSubstitutePictureTitle--) | Mengembalikan atau menetapkan judul untuk ikon OleObject. |
| [setSubstitutePictureTitle(String value)](#setSubstitutePictureTitle-java.lang.String-) | Mengembalikan atau menetapkan judul untuk ikon OleObject. |
| [getObjectName()](#getObjectName--) | Mengembalikan atau menetapkan nama sebuah objek. |
| [setObjectName(String value)](#setObjectName-java.lang.String-) | Mengembalikan atau menetapkan nama sebuah objek. |
| [getObjectProgId()](#getObjectProgId--) | Mengembalikan ProgID sebuah objek. |
| [setObjectProgId(String value)](#setObjectProgId-java.lang.String-) | Mengembalikan ProgID sebuah objek. |
| [getLinkFileName()](#getLinkFileName--) | Mengembalikan jalur lengkap ke file yang ditautkan. |
| [getLinkPathLong()](#getLinkPathLong--) | Mengembalikan jalur lengkap ke file yang ditautkan. |
| [setLinkPathLong(String value)](#setLinkPathLong-java.lang.String-) | Mengembalikan jalur lengkap ke file yang ditautkan. |
| [getLinkPathRelative()](#getLinkPathRelative--) | Mengembalikan jalur relatif ke file yang ditautkan jika ada, jika tidak mengembalikan string kosong. |
| [getEmbeddedFileLabel()](#getEmbeddedFileLabel--) | Mengembalikan nama file objek OLE yang disematkan |
| [getEmbeddedFileName()](#getEmbeddedFileName--) | Mengembalikan jalur objek OLE yang disematkan |
| [getEmbeddedData()](#getEmbeddedData--) | Mendapatkan atau menetapkan informasi tentang data OLE yang disematkan. |
| [setEmbeddedData(IOleEmbeddedDataInfo embeddedData)](#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-) | Menetapkan informasi tentang data OLE yang disematkan. |
| [isObjectIcon()](#isObjectIcon--) | Menentukan apakah sebuah objek terlihat sebagai ikon. |
| [setObjectIcon(boolean value)](#setObjectIcon-boolean-) | Menentukan apakah sebuah objek terlihat sebagai ikon. |
| [isObjectLink()](#isObjectLink--) | Menentukan apakah sebuah objek ditautkan ke file eksternal. |
| [getUpdateAutomatic()](#getUpdateAutomatic--) | Menentukan apakah objek yang ditautkan dan disematkan secara otomatis diperbarui ketika presentasi dibuka atau dicetak. |
| [setUpdateAutomatic(boolean value)](#setUpdateAutomatic-boolean-) | Menentukan apakah objek yang ditautkan dan disematkan secara otomatis diperbarui ketika presentasi dibuka atau dicetak. |

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

Mengembalikan atau menetapkan judul untuk ikon OleObject. Baca/tulis String.

--------------------

Ketika IsObjectIcon == false nilai ini diabaikan. String dapat dipotong sesuai dengan ukuran ikon Ole.

**Mengembalikan:**
java.lang.String
### setSubstitutePictureTitle(String value) {#setSubstitutePictureTitle-java.lang.String-}
```
public final void setSubstitutePictureTitle(String value)
```

Mengembalikan atau menetapkan judul untuk ikon OleObject. Baca/tulis String.

--------------------

Ketika IsObjectIcon == false nilai ini diabaikan. String dapat dipotong sesuai dengan ukuran ikon Ole.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectName() {#getObjectName--}
```
public final String getObjectName()
```

Mengembalikan atau menetapkan nama sebuah objek. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setObjectName(String value) {#setObjectName-java.lang.String-}
```
public final void setObjectName(String value)
```

Mengembalikan atau menetapkan nama sebuah objek. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getObjectProgId() {#getObjectProgId--}
```
public final String getObjectProgId()
```

Mengembalikan ProgID sebuah objek. Hanya-baca String.

**Mengembalikan:**
java.lang.String
### setObjectProgId(String value) {#setObjectProgId-java.lang.String-}
```
public final void setObjectProgId(String value)
```

Mengembalikan ProgID sebuah objek. Hanya-baca String.

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

Mengembalikan nama file objek OLE yang disematkan

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

Mendapatkan atau menetapkan informasi tentang data OLE yang disematkan. Baca/tulis [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo).

**Mengembalikan:**
[IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)
### setEmbeddedData(IOleEmbeddedDataInfo embeddedData) {#setEmbeddedData-com.aspose.slides.IOleEmbeddedDataInfo-}
```
public final void setEmbeddedData(IOleEmbeddedDataInfo embeddedData)
```

Menetapkan informasi tentang data OLE yang disematkan.

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
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
| embeddedData | [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo) | Data yang disematkan [IOleEmbeddedDataInfo](../../com.aspose.slides/ioleembeddeddatainfo)

Metode ini mengubah properti objek untuk mencerminkan data baru dan menetapkan flag IsObjectLink menjadi false, menandakan bahwa objek OLE disematkan. |

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

Menentukan apakah objek yang ditautkan dan disematkan secara otomatis diperbarui ketika presentasi dibuka atau dicetak. Baca/tulis boolean .

**Mengembalikan:**
boolean
### setUpdateAutomatic(boolean value) {#setUpdateAutomatic-boolean-}
```
public final void setUpdateAutomatic(boolean value)
```

Menentukan apakah objek yang ditautkan dan disematkan secara otomatis diperbarui ketika presentasi dibuka atau dicetak. Baca/tulis boolean .

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |