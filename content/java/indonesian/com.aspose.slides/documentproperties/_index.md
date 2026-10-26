---
title: DocumentProperties
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili properti presentasi.
type: docs
url: /id/com.aspose.slides/documentproperties/
---
**Pewarisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IDocumentProperties](../../com.aspose.slides/idocumentproperties), com.aspose.slides.IGenericCloneable, java.lang.Cloneable
```
public class DocumentProperties implements IDocumentProperties, IGenericCloneable<IDocumentProperties>, Cloneable
```

Mewakili properti sebuah presentasi.

--------------------

> ```
> The following example shows how to access built-in Properties of PowerPoint Presentation.
>  
>  // Instansiasi kelas Presentation yang mewakili presentasi
>  Presentation pres = new Presentation("AccessBuiltin Properties.pptx");
>  try {
>      // Buat referensi ke objek IDocumentProperties yang terkait dengan Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Tampilkan properti bawaan
>      System.out.println("Category : " + documentProperties.getCategory());
>      System.out.println("Current Status : " + documentProperties.getContentStatus());
>      System.out.println("Creation Date : " + documentProperties.getCreatedTime());
>      System.out.println("Author : " + documentProperties.getAuthor());
>      System.out.println("Description : " + documentProperties.getComments());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
>  
>  The following example shows how to modify built-in Properties of PowerPoint Presentation.
>  
>  // Instansiasi kelas Presentation yang mewakili Presentation
>  Presentation pres = new Presentation("ModifyBuiltinProperties.pptx");
>  try {
>      // Buat referensi ke objek IDocumentProperties yang terkait dengan Presentation
>      IDocumentProperties documentProperties = pres.getDocumentProperties();
>      // Setel properti bawaan
>      documentProperties.setAuthor("Aspose.Slides for Java");
>      documentProperties.setTitle("Modifying Presentation Properties");
>      documentProperties.setSubject("Aspose Subject");
>      // Simpan presentasi Anda ke file
>      pres.save("DocumentProperties_out.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [DocumentProperties()](#DocumentProperties--) | Menginisialisasi instansi baru dari kelas [DocumentProperties](../../com.aspose.slides/documentproperties). |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getAppVersion()](#getAppVersion--) | Mengembalikan versi aplikasi. |
| [getNameOfApplication()](#getNameOfApplication--) | Mengembalikan atau mengatur nama aplikasi. |
| [setNameOfApplication(String value)](#setNameOfApplication-java.lang.String-) | Mengembalikan atau mengatur nama aplikasi. |
| [getCompany()](#getCompany--) | Mengembalikan atau mengatur properti perusahaan. |
| [setCompany(String value)](#setCompany-java.lang.String-) | Mengembalikan atau mengatur properti perusahaan. |
| [getManager()](#getManager--) | Mengembalikan atau mengatur properti manajer. |
| [setManager(String value)](#setManager-java.lang.String-) | Mengembalikan atau mengatur properti manajer. |
| [getPresentationFormat()](#getPresentationFormat--) | Mengembalikan atau mengatur format yang dimaksudkan untuk sebuah presentasi. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Mengembalikan atau mengatur format yang dimaksudkan untuk sebuah presentasi. |
| [getSharedDoc()](#getSharedDoc--) | Menentukan apakah presentasi dibagikan antara beberapa orang. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Menentukan apakah presentasi dibagikan antara beberapa orang. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Mengembalikan atau mengatur templat sebuah aplikasi. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Mengembalikan atau mengatur templat sebuah aplikasi. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Waktu penyuntingan total sebuah presentasi. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Waktu penyuntingan total sebuah presentasi. |
| [getTitle()](#getTitle--) | Mengembalikan atau mengatur judul sebuah presentasi. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Mengembalikan atau mengatur judul sebuah presentasi. |
| [getSubject()](#getSubject--) | Mengembalikan atau mengatur subjek sebuah presentasi. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Mengembalikan atau mengatur subjek sebuah presentasi. |
| [getAuthor()](#getAuthor--) | Mengembalikan atau mengatur penulis sebuah presentasi. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Mengembalikan atau mengatur penulis sebuah presentasi. |
| [getKeywords()](#getKeywords--) | Mengembalikan atau mengatur kata kunci sebuah presentasi. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Mengembalikan atau mengatur kata kunci sebuah presentasi. |
| [getComments()](#getComments--) | Mengembalikan atau mengatur komentar sebuah presentasi. |
| [setComments(String value)](#setComments-java.lang.String-) | Mengembalikan atau mengatur komentar sebuah presentasi. |
| [getCategory()](#getCategory--) | Mengembalikan atau mengatur kategori sebuah presentasi. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Mengembalikan atau mengatur kategori sebuah presentasi. |
| [getCreatedTime()](#getCreatedTime--) | Mengembalikan tanggal presentasi dibuat. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Mengembalikan tanggal presentasi dibuat. |
| [getLastSavedTime()](#getLastSavedTime--) | Mengembalikan tanggal presentasi terakhir diubah. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Mengembalikan tanggal presentasi terakhir diubah. |
| [getLastPrinted()](#getLastPrinted--) | Mengembalikan tanggal presentasi terakhir dicetak. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Mengembalikan tanggal presentasi terakhir dicetak. |
| [getLastSavedBy()](#getLastSavedBy--) | Mengembalikan atau mengatur nama orang terakhir yang memodifikasi presentasi. |
| [setLastSavedBy(String value)](#setLastSavedBy-java.lang.String-) | Mengembalikan atau mengatur nama orang terakhir yang memodifikasi presentasi. |
| [getRevisionNumber()](#getRevisionNumber--) | Mengembalikan atau mengatur nomor revisi presentasi. |
| [setRevisionNumber(int value)](#setRevisionNumber-int-) | Mengembalikan atau mengatur nomor revisi presentasi. |
| [getContentStatus()](#getContentStatus--) | Mengembalikan atau mengatur status konten presentasi. |
| [setContentStatus(String value)](#setContentStatus-java.lang.String-) | Mengembalikan atau mengatur status konten presentasi. |
| [getContentType()](#getContentType--) | Mengembalikan atau mengatur tipe konten presentasi. |
| [setContentType(String value)](#setContentType-java.lang.String-) | Mengembalikan atau mengatur tipe konten presentasi. |
| [getHyperlinkBase()](#getHyperlinkBase--) | Mengembalikan atau mengatur properti dokumen HyperlinkBase. |
| [setHyperlinkBase(String value)](#setHyperlinkBase-java.lang.String-) | Mengembalikan atau mengatur properti dokumen HyperlinkBase. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Mengembalikan jumlah properti kustom yang sebenarnya terkandung dalam koleksi. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Mengembalikan nama properti kustom pada indeks yang ditentukan. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Menghapus properti kustom yang terkait dengan nama tertentu. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Memeriksa keberadaan properti kustom dengan nama tertentu. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Mengembalikan atau mengatur properti kustom yang terkait dengan nama tertentu. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Mengembalikan atau mengatur properti kustom yang terkait dengan nama tertentu. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Mendapatkan nilai boolean bernama dari properti kustom. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Mendapatkan nilai integer bernama dari properti kustom. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Mendapatkan nilai DateTime bernama dari properti kustom. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Mendapatkan nilai string bernama dari properti kustom. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Mendapatkan nilai float bernama dari properti kustom. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Mendapatkan nilai double bernama dari properti kustom. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Mengatur properti kustom boolean bernama. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Mengatur properti kustom integer bernama. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Mengatur properti kustom DateTime bernama. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Mengatur properti kustom string bernama. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Mengatur properti kustom float bernama. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Mengatur properti kustom double bernama. |
| [clearCustomProperties()](#clearCustomProperties--) | Menghapus semua properti kustom. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Mendapatkan array label sensitivitas dari properti dokumen kustom (Metadata Microsoft Information Protection SDK). |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Menghapus dan mengatur nilai default untuk semua properti bawaan. |
| [getScaleCrop()](#getScaleCrop--) | Menunjukkan mode tampilan thumbnail dokumen. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Menunjukkan mode tampilan thumbnail dokumen. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Menunjukkan apakah tautan dalam dokumen terbaru. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Menunjukkan apakah tautan dalam dokumen terbaru. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Menentukan bahwa satu atau lebih tautan dalam bagian ini hanya diperbarui dalam bagian ini oleh produsen. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Menentukan bahwa satu atau lebih tautan dalam bagian ini hanya diperbarui dalam bagian ini oleh produsen. |
| [getSlides()](#getSlides--) | Mengembalikan total jumlah slide dalam dokumen presentasi. |
| [getHiddenSlides()](#getHiddenSlides--) | Mengembalikan jumlah slide tersembunyi dalam dokumen presentasi. |
| [getNotes()](#getNotes--) | Mengembalikan jumlah slide dalam presentasi yang berisi catatan. |
| [getParagraphs()](#getParagraphs--) | Mengembalikan total jumlah paragraf yang ditemukan dalam dokumen jika berlaku. |
| [getWords()](#getWords--) | Mengembalikan total jumlah kata dalam dokumen. |
| [getMultimediaClips()](#getMultimediaClips--) | Mengembalikan total jumlah klip suara atau video yang ada dalam dokumen. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Menentukan judul setiap bagian dokumen. |
| [getHeadingPairs()](#getHeadingPairs--) | Menunjukkan pengelompokan bagian dokumen dan jumlah bagian dalam setiap grup. |
| [deepClone()](#deepClone--) | Menggandakan objek saat ini |
| [cloneT()](#cloneT--) | Menggandakan objek saat ini |
### DocumentProperties() {#DocumentProperties--}
```
public DocumentProperties()
```


Menginisialisasi instansi baru dari kelas [DocumentProperties](../../com.aspose.slides/documentproperties).

### getAppVersion() {#getAppVersion--}
```
public final String getAppVersion()
```


Mengembalikan versi aplikasi. String Hanya Baca.

**Mengembalikan:**
java.lang.String
### getNameOfApplication() {#getNameOfApplication--}
```
public final String getNameOfApplication()
```


Mengembalikan atau mengatur nama aplikasi. String Baca/Tulis.

**Mengembalikan:**
java.lang.String
### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public final void setNameOfApplication(String value)
```


Mengembalikan atau mengatur nama aplikasi. String Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public final String getCompany()
```


Mengembalikan atau mengatur properti perusahaan. String Baca/Tulis.

**Mengembalikan:**
java.lang.String
### setCompany(String value) {#setCompany-java.lang.String-}
```
public final void setCompany(String value)
```


Mengembalikan atau mengatur properti perusahaan. String Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public final String getManager()
```


Mengembalikan atau mengatur properti manajer. String Baca/Tulis.

**Mengembalikan:**
java.lang.String
### setManager(String value) {#setManager-java.lang.String-}
```
public final void setManager(String value)
```


Mengembalikan atau mengatur properti manajer. String Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public final String getPresentationFormat()
```


Mengembalikan atau mengatur format yang dimaksudkan untuk sebuah presentasi. String Baca/Tulis.

**Mengembalikan:**
java.lang.String
### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public final void setPresentationFormat(String value)
```


Mengembalikan atau mengatur format yang dimaksudkan untuk sebuah presentasi. String Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public final boolean getSharedDoc()
```


Menentukan apakah presentasi dibagikan antara beberapa orang. boolean Baca/Tulis.

**Mengembalikan:**
boolean
### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public final void setSharedDoc(boolean value)
```


Menentukan apakah presentasi dibagikan antara beberapa orang. boolean Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public final String getApplicationTemplate()
```


Mengembalikan atau mengatur templat sebuah aplikasi. String Baca/Tulis.

**Mengembalikan:**
java.lang.String
### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public final void setApplicationTemplate(String value)
```


Mengembalikan atau mengatur templat sebuah aplikasi. String Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public final double getTotalEditingTime()
```


Waktu penyuntingan total sebuah presentasi. double Baca/Tulis.

**Mengembalikan:**
double
### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public final void setTotalEditingTime(double value)
```


Waktu penyuntingan total sebuah presentasi. double Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public final String getTitle()
```


Mengembalikan atau mengatur judul sebuah presentasi. String Baca/Tulis.

**Mengembalikan:**
java.lang.String
### setTitle(String value) {#setTitle-java.lang.String-}
```
public final void setTitle(String value)
```


Mengembalikan atau mengatur judul sebuah presentasi. String Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public final String getSubject()
```


Mengembalikan atau mengatur subjek sebuah presentasi. String Baca/Tulis.

**Mengembalikan:**
java.lang.String
### setSubject(String value) {#setSubject-java.lang.String-}
```
public final void setSubject(String value)
```


Mengembalikan atau mengatur subjek sebuah presentasi. String Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public final String getAuthor()
```


Mengembalikan atau mengatur penulis sebuah presentasi. String Baca/Tulis.

**Mengembalikan:**
java.lang.String
### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public final void setAuthor(String value)
```


Mengembalikan atau mengatur penulis sebuah presentasi. String Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public final String getKeywords()
```


Mengembalikan atau mengatur kata kunci sebuah presentasi. String Baca/Tulis.

**Mengembalikan:**
java.lang.String
### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public final void setKeywords(String value)
```


Mengembalikan atau mengatur kata kunci sebuah presentasi. String Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public final String getComments()
```


Mengembalikan atau mengatur komentar sebuah presentasi. String Baca/Tulis.

**Mengembalikan:**
java.lang.String
### setComments(String value) {#setComments-java.lang.String-}
```
public final void setComments(String value)
```


Mengembalikan atau mengatur komentar sebuah presentasi. String Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public final String getCategory()
```


Mengembalikan atau mengatur kategori sebuah presentasi. String Baca/Tulis.

**Mengembalikan:**
java.lang.String
### setCategory(String value) {#setCategory-java.lang.String-}
```
public final void setCategory(String value)
```


Mengembalikan atau mengatur kategori sebuah presentasi. String Baca/Tulis.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public final Date getCreatedTime()
```
Mengembalikan tanggal pembuatan presentasi. Nilai dalam UTC. Baca/tulis java.util.Date.

**Mengembalikan:**
java.util.Date
### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public final void setCreatedTime(Date value)
```

Mengembalikan tanggal pembuatan presentasi. Nilai dalam UTC. Baca/tulis java.util.Date.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public final Date getLastSavedTime()
```

Mengembalikan tanggal terakhir presentasi diubah. Nilai dalam UTC. Baca-saja dalam kasus Presentation.DocumentProperties (karena akan diperbarui secara internal selama proses penyimpanan objek IPresentation). Dapat diubah melalui instance DocumentProperties yang dikembalikan oleh metode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Silakan lihat contoh pada ringkasan metode [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Mengembalikan:**
java.util.Date
### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public final void setLastSavedTime(Date value)
```

Mengembalikan tanggal terakhir presentasi diubah. Nilai dalam UTC. Baca-saja dalam kasus Presentation.DocumentProperties (karena akan diperbarui secara internal selama proses penyimpanan objek IPresentation). Dapat diubah melalui instance DocumentProperties yang dikembalikan oleh metode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Silakan lihat contoh pada ringkasan metode [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public final Date getLastPrinted()
```

Mengembalikan tanggal saat presentasi terakhir dicetak. Baca/tulis java.util.Date.

**Mengembalikan:**
java.util.Date
### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public final void setLastPrinted(Date value)
```

Mengembalikan tanggal saat presentasi terakhir dicetak. Baca/tulis java.util.Date.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public final String getLastSavedBy()
```

Mengembalikan atau mengatur nama orang terakhir yang mengubah presentasi. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public final void setLastSavedBy(String value)
```

Mengembalikan atau mengatur nama orang terakhir yang mengubah presentasi. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public final int getRevisionNumber()
```

Mengembalikan atau mengatur nomor revisi presentasi. Baca/tulis int.

**Mengembalikan:**
int
### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public final void setRevisionNumber(int value)
```

Mengembalikan atau mengatur nomor revisi presentasi. Baca/tulis int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public final String getContentStatus()
```

Mengembalikan atau mengatur status konten presentasi. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public final void setContentStatus(String value)
```

Mengembalikan atau mengatur status konten presentasi. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public final String getContentType()
```

Mengembalikan atau mengatur tipe konten presentasi. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setContentType(String value) {#setContentType-java.lang.String-}
```
public final void setContentType(String value)
```

Mengembalikan atau mengatur tipe konten presentasi. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public final String getHyperlinkBase()
```

Mengembalikan atau mengatur properti dokumen HyperlinkBase. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public final void setHyperlinkBase(String value)
```

Mengembalikan atau mengatur properti dokumen HyperlinkBase. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public final int getCountOfCustomProperties()
```

Mengembalikan jumlah properti khusus yang sebenarnya terdapat dalam koleksi. Baca-saja int.

**Mengembalikan:**
int
### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public final String getCustomPropertyName(int index)
```

Mengembalikan nama properti khusus pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari properti khusus yang akan diambil. |

**Mengembalikan:**
java.lang.String - Nama properti khusus pada indeks yang ditentukan.
### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public final boolean removeCustomProperty(String name)
```

Menghapus properti khusus yang terkait dengan nama tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan dihapus. |

**Mengembalikan:**
boolean - Mengembalikan true jika properti dihapus, false sebaliknya.
### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public final boolean containsCustomProperty(String name)
```

Memeriksa keberadaan properti khusus dengan nama tertentu.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diperiksa. |

**Mengembalikan:**
boolean - Mengembalikan true jika properti ada, false sebaliknya.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public final Object get_Item(String name)
```

Mengembalikan atau mengatur properti khusus yang terkait dengan nama tertentu. Baca/tulis Object.

Value can be **int**, **float**, **String**, **boolean** or **Date**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Mengembalikan:**
java.lang.Object
### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public final void set_Item(String name, Object value)
```

Mengembalikan atau mengatur properti khusus yang terkait dengan nama tertentu. Baca/tulis Object.

Value can be **int**, **float**, **String**, **boolean** or **Date**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public final void getCustomPropertyValue(String name, boolean[] value)
```

Mendapatkan nilai boolean bernama dari properti khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diambil |
| value | boolean[] | Nilai properti khusus |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public final void getCustomPropertyValue(String name, int[] value)
```

Mendapatkan nilai integer bernama dari properti khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diambil |
| value | int[] | Nilai properti khusus |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public final void getCustomPropertyValue(String name, Date[] value)
```

Mendapatkan nilai DateTime bernama dari properti khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diambil |
| value | java.util.Date[] | Nilai properti khusus |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public final void getCustomPropertyValue(String name, String[] value)
```

Mendapatkan nilai string bernama dari properti khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diambil |
| value | java.lang.String[] | Nilai properti khusus |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public final void getCustomPropertyValue(String name, float[] value)
```

Mendapatkan nilai float bernama dari properti khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diambil |
| value | float[] | Nilai properti khusus |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public final void getCustomPropertyValue(String name, double[] value)
```

Mendapatkan nilai double bernama dari properti khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diambil. |
| value | double[] | Nilai properti khusus |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public final void setCustomPropertyValue(String name, boolean value)
```

Mengatur properti khusus boolean bernama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diatur |
| value | boolean | Nilai properti khusus |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public final void setCustomPropertyValue(String name, int value)
```

Mengatur properti khusus integer bernama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diatur |
| value | int | Nilai properti khusus |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public final void setCustomPropertyValue(String name, Date value)
```

Mengatur properti khusus DateTime bernama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diatur |
| value | java.util.Date | Nilai properti khusus |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public final void setCustomPropertyValue(String name, String value)
```

Mengatur properti khusus string bernama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diatur |
| value | java.lang.String | Nilai properti khusus |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public final void setCustomPropertyValue(String name, float value)
```

Mengatur properti khusus float bernama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diatur |
| value | float | Nilai properti khusus |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public final void setCustomPropertyValue(String name, double value)
```

Mengatur properti khusus double bernama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diatur |
| value | double | Nilai properti khusus |

### clearCustomProperties() {#clearCustomProperties--}
```
public final void clearCustomProperties()
```

Menghapus semua properti khusus.

### getSensitivityLabels() {#getSensitivityLabels--}
```
public final ISensitivityLabel[] getSensitivityLabels()
```

Mengambil array label sensitivitas dari properti dokumen khusus (Metadata Microsoft Information Protection SDK).

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Dapatkan label sensitivitas dari properti dokumen khusus
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Tambahkan label ke dalam koleksi
>          // Di sini Anda dapat menambahkan pemeriksaan untuk validitas informasi label (label tersedia, dll)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
com.aspose.slides.ISensitivityLabel[]
### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public final void clearBuiltInProperties()
```

Menghapus dan mengatur nilai default untuk semua properti builtIn.

### getScaleCrop() {#getScaleCrop--}
```
public final boolean getScaleCrop()
```

Menunjukkan mode tampilan thumbnail dokumen. Atur elemen ini ke **true** untuk mengaktifkan penskalaan thumbnail dokumen ke tampilan. Atur elemen ini ke **false** untuk mengaktifkan pemotongan thumbnail dokumen sehingga hanya menampilkan bagian yang sesuai dengan tampilan. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public final void setScaleCrop(boolean value)
```

Menunjukkan mode tampilan thumbnail dokumen. Atur elemen ini ke **true** untuk mengaktifkan penskalaan thumbnail dokumen ke tampilan. Atur elemen ini ke **false** untuk mengaktifkan pemotongan thumbnail dokumen sehingga hanya menampilkan bagian yang sesuai dengan tampilan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public final boolean getLinksUpToDate()
```

Menunjukkan apakah hyperlink dalam dokumen sudah up-to-date. Atur elemen ini ke **true** untuk menandakan bahwa hyperlink telah diperbarui. Atur elemen ini ke **false** untuk menandakan bahwa hyperlink sudah usang. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public final void setLinksUpToDate(boolean value)
```
Menunjukkan apakah hyperlink dalam dokumen terkini. Atur elemen ini ke **true** untuk menunjukkan bahwa hyperlink diperbarui. Atur elemen ini ke **false** untuk menunjukkan bahwa hyperlink sudah usang. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public final boolean getHyperlinksChanged()
```

Menentukan bahwa satu atau lebih hyperlink dalam bagian ini diperbarui secara eksklusif di bagian ini oleh produser. Produser berikutnya yang membuka dokumen ini harus memperbarui hubungan hyperlink dengan hyperlink baru yang ditentukan dalam bagian ini. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public final void setHyperlinksChanged(boolean value)
```

Menentukan bahwa satu atau lebih hyperlink dalam bagian ini diperbarui secara eksklusif di bagian ini oleh produser. Produser berikutnya yang membuka dokumen ini harus memperbarui hubungan hyperlink dengan hyperlink baru yang ditentukan dalam bagian ini. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public final int getSlides()
```

Mengembalikan total jumlah slide dalam dokumen presentasi. Baca-saja int.

**Mengembalikan:**
int
### getHiddenSlides() {#getHiddenSlides--}
```
public final int getHiddenSlides()
```

Mengembalikan jumlah slide tersembunyi dalam dokumen presentasi. Baca-saja int.

**Mengembalikan:**
int
### getNotes() {#getNotes--}
```
public final int getNotes()
```

Mengembalikan jumlah slide dalam presentasi yang berisi catatan. Baca-saja int.

**Mengembalikan:**
int
### getParagraphs() {#getParagraphs--}
```
public final int getParagraphs()
```

Mengembalikan total jumlah paragraf yang ditemukan dalam dokumen jika berlaku. Baca-saja int.

**Mengembalikan:**
int
### getWords() {#getWords--}
```
public final int getWords()
```

Mengembalikan total jumlah kata yang terdapat dalam dokumen. Baca-saja int.

**Mengembalikan:**
int
### getMultimediaClips() {#getMultimediaClips--}
```
public final int getMultimediaClips()
```

Mengembalikan total jumlah klip suara atau video yang ada dalam dokumen. Baca-saja int.

**Mengembalikan:**
int
### getTitlesOfParts() {#getTitlesOfParts--}
```
public final String[] getTitlesOfParts()
```

Menentukan judul setiap bagian dokumen. Bagian-bagian ini bukan bagian dokumen melainkan representasi konseptual dari bagian dokumen. Baca-saja String[].

**Mengembalikan:**
java.lang.String[]
### getHeadingPairs() {#getHeadingPairs--}
```
public final IHeadingPair[] getHeadingPairs()
```

Menunjukkan pengelompokan bagian dokumen dan jumlah bagian dalam setiap grup. Baca-saja IHeadingPair[].

**Mengembalikan:**
com.aspose.slides.IHeadingPair[]
### deepClone() {#deepClone--}
```
public final Object deepClone()
```

Mengkloning objek saat ini

**Mengembalikan:**
java.lang.Object - Clone
### cloneT() {#cloneT--}
```
public final IDocumentProperties cloneT()
```

Mengkloning objek saat ini

**Mengembalikan:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties) - Clone