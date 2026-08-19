---
title: IDocumentProperties
second_title: Aspose.Slides for Java API Reference
description: Mewakili properti presentasi.
type: docs
url: /id/com.aspose.slides/idocumentproperties/
---```
public interface IDocumentProperties
```

Mewakili properti presentasi.
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
| [getPresentationFormat()](#getPresentationFormat--) | Mengembalikan atau mengatur format yang dimaksud dari sebuah presentasi. |
| [setPresentationFormat(String value)](#setPresentationFormat-java.lang.String-) | Mengembalikan atau mengatur format yang dimaksud dari sebuah presentasi. |
| [getSharedDoc()](#getSharedDoc--) | Menentukan apakah presentasi dibagikan antara beberapa orang. |
| [setSharedDoc(boolean value)](#setSharedDoc-boolean-) | Menentukan apakah presentasi dibagikan antara beberapa orang. |
| [getApplicationTemplate()](#getApplicationTemplate--) | Mengembalikan atau mengatur templat aplikasi. |
| [setApplicationTemplate(String value)](#setApplicationTemplate-java.lang.String-) | Mengembalikan atau mengatur templat aplikasi. |
| [getTotalEditingTime()](#getTotalEditingTime--) | Total waktu pengeditan presentasi. |
| [setTotalEditingTime(double value)](#setTotalEditingTime-double-) | Total waktu pengeditan presentasi. |
| [getTitle()](#getTitle--) | Mengembalikan atau mengatur judul presentasi. |
| [setTitle(String value)](#setTitle-java.lang.String-) | Mengembalikan atau mengatur judul presentasi. |
| [getSubject()](#getSubject--) | Mengembalikan atau mengatur subjek presentasi. |
| [setSubject(String value)](#setSubject-java.lang.String-) | Mengembalikan atau mengatur subjek presentasi. |
| [getAuthor()](#getAuthor--) | Mengembalikan atau mengatur penulis presentasi. |
| [setAuthor(String value)](#setAuthor-java.lang.String-) | Mengembalikan atau mengatur penulis presentasi. |
| [getKeywords()](#getKeywords--) | Mengembalikan atau mengatur kata kunci presentasi. |
| [setKeywords(String value)](#setKeywords-java.lang.String-) | Mengembalikan atau mengatur kata kunci presentasi. |
| [getComments()](#getComments--) | Mengembalikan atau mengatur komentar presentasi. |
| [setComments(String value)](#setComments-java.lang.String-) | Mengembalikan atau mengatur komentar presentasi. |
| [getCategory()](#getCategory--) | Mengembalikan atau mengatur kategori presentasi. |
| [setCategory(String value)](#setCategory-java.lang.String-) | Mengembalikan atau mengatur kategori presentasi. |
| [getCreatedTime()](#getCreatedTime--) | Mengembalikan tanggal pembuatan presentasi. |
| [setCreatedTime(Date value)](#setCreatedTime-java.util.Date-) | Mengembalikan tanggal pembuatan presentasi. |
| [getLastSavedTime()](#getLastSavedTime--) | Mengembalikan tanggal terakhir modifikasi presentasi. |
| [setLastSavedTime(Date value)](#setLastSavedTime-java.util.Date-) | Mengembalikan tanggal terakhir modifikasi presentasi. |
| [getLastPrinted()](#getLastPrinted--) | Mengembalikan tanggal ketika presentasi terakhir dicetak. |
| [setLastPrinted(Date value)](#setLastPrinted-java.util.Date-) | Mengembalikan tanggal ketika presentasi terakhir dicetak. |
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
| [getScaleCrop()](#getScaleCrop--) | Menunjukkan mode tampilan thumbnail dokumen. |
| [setScaleCrop(boolean value)](#setScaleCrop-boolean-) | Menunjukkan mode tampilan thumbnail dokumen. |
| [getLinksUpToDate()](#getLinksUpToDate--) | Menunjukkan apakah hyperlink dalam dokumen sudah up-to-date. |
| [setLinksUpToDate(boolean value)](#setLinksUpToDate-boolean-) | Menunjukkan apakah hyperlink dalam dokumen sudah up-to-date. |
| [getHyperlinksChanged()](#getHyperlinksChanged--) | Menentukan bahwa satu atau lebih hyperlink dalam bagian ini diperbarui secara eksklusif dalam bagian ini oleh produsen. |
| [setHyperlinksChanged(boolean value)](#setHyperlinksChanged-boolean-) | Menentukan bahwa satu atau lebih hyperlink dalam bagian ini diperbarui secara eksklusif dalam bagian ini oleh produsen. |
| [getSlides()](#getSlides--) | Menentukan total jumlah slide dalam dokumen presentasi. |
| [getHiddenSlides()](#getHiddenSlides--) | Menentukan jumlah slide tersembunyi dalam dokumen presentasi. |
| [getNotes()](#getNotes--) | Menentukan jumlah slide dalam presentasi yang berisi catatan. |
| [getParagraphs()](#getParagraphs--) | Menentukan total jumlah paragraf yang ditemukan dalam dokumen jika berlaku. |
| [getWords()](#getWords--) | Menentukan total jumlah kata dalam dokumen. |
| [getMultimediaClips()](#getMultimediaClips--) | Menentukan total jumlah klip suara atau video yang ada dalam dokumen. |
| [getTitlesOfParts()](#getTitlesOfParts--) | Menentukan judul setiap bagian dokumen. |
| [getHeadingPairs()](#getHeadingPairs--) | Menunjukkan pengelompokan bagian dokumen dan jumlah bagian dalam setiap grup. |
| [getCountOfCustomProperties()](#getCountOfCustomProperties--) | Mengembalikan jumlah properti khusus yang sebenarnya ada dalam koleksi. |
| [getCustomPropertyName(int index)](#getCustomPropertyName-int-) | Mengembalikan nama properti khusus pada indeks yang ditentukan. |
| [removeCustomProperty(String name)](#removeCustomProperty-java.lang.String-) | Menghapus properti khusus yang terkait dengan nama tertentu. |
| [containsCustomProperty(String name)](#containsCustomProperty-java.lang.String-) | Memeriksa keberadaan properti khusus dengan nama tertentu. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Mengembalikan atau mengatur properti khusus yang terkait dengan nama tertentu. |
| [set_Item(String name, Object value)](#set-Item-java.lang.String-java.lang.Object-) | Mengembalikan atau mengatur properti khusus yang terkait dengan nama tertentu. |
| [clearCustomProperties()](#clearCustomProperties--) | Menghapus semua properti khusus. |
| [clearBuiltInProperties()](#clearBuiltInProperties--) | Menghapus dan mengatur nilai default untuk semua properti builtIn. |
| [getCustomPropertyValue(String name, boolean[] value)](#getCustomPropertyValue-java.lang.String-boolean---) | Gets a named boolean value from the custom properties. |
| [getCustomPropertyValue(String name, int[] value)](#getCustomPropertyValue-java.lang.String-int---) | Gets a named integer value from the custom properties. |
| [getCustomPropertyValue(String name, Date[] value)](#getCustomPropertyValue-java.lang.String-java.util.Date---) | Gets a named DateTime value from the custom properties. |
| [getCustomPropertyValue(String name, String[] value)](#getCustomPropertyValue-java.lang.String-java.lang.String---) | Gets a named string value from the custom properties. |
| [getCustomPropertyValue(String name, float[] value)](#getCustomPropertyValue-java.lang.String-float---) | Gets a named float value from the custom properties. |
| [getCustomPropertyValue(String name, double[] value)](#getCustomPropertyValue-java.lang.String-double---) | Gets a named double value from the custom properties. |
| [setCustomPropertyValue(String name, boolean value)](#setCustomPropertyValue-java.lang.String-boolean-) | Mengatur properti khusus boolean bernama. |
| [setCustomPropertyValue(String name, int value)](#setCustomPropertyValue-java.lang.String-int-) | Mengatur properti khusus integer bernama. |
| [setCustomPropertyValue(String name, Date value)](#setCustomPropertyValue-java.lang.String-java.util.Date-) | Mengatur properti khusus DateTime bernama. |
| [setCustomPropertyValue(String name, String value)](#setCustomPropertyValue-java.lang.String-java.lang.String-) | Mengatur properti khusus string bernama. |
| [setCustomPropertyValue(String name, float value)](#setCustomPropertyValue-java.lang.String-float-) | Mengatur properti khusus float bernama. |
| [setCustomPropertyValue(String name, double value)](#setCustomPropertyValue-java.lang.String-double-) | Mengatur properti khusus double bernama. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Mendapatkan array label sensitivitas dari properti dokumen khusus (Metadata Microsoft Information Protection SDK). |

### getAppVersion() {#getAppVersion--}
```
public abstract String getAppVersion()
```

Mengembalikan versi aplikasi. Hanya-baca String.

--------------------

Konten elemen ini harus dalam bentuk XX.YYYY, di mana X dan Y mewakili nilai numerik; jika tidak, dokumen dianggap tidak sesuai. Aspose.Slides menyajikan versinya dalam format XX.YY.ZZ, di mana: XX - versi utama YY - versi minor ZZ - versi patch. Misalnya, nilai 23.0105 berarti versi Aspose.Slides 23.1.5.

**Mengembalikan:**
java.lang.String

### getNameOfApplication() {#getNameOfApplication--}
```
public abstract String getNameOfApplication()
```

Mengembalikan atau mengatur nama aplikasi. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setNameOfApplication(String value) {#setNameOfApplication-java.lang.String-}
```
public abstract void setNameOfApplication(String value)
```

Mengembalikan atau mengatur nama aplikasi. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getCompany() {#getCompany--}
```
public abstract String getCompany()
```

Mengembalikan atau mengatur properti perusahaan. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setCompany(String value) {#setCompany-java.lang.String-}
```
public abstract void setCompany(String value)
```

Mengembalikan atau mengatur properti perusahaan. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getManager() {#getManager--}
```
public abstract String getManager()
```

Mengembalikan atau mengatur properti manajer. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setManager(String value) {#setManager-java.lang.String-}
```
public abstract void setManager(String value)
```

Mengembalikan atau mengatur properti manajer. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getPresentationFormat() {#getPresentationFormat--}
```
public abstract String getPresentationFormat()
```

Mengembalikan atau mengatur format yang dimaksud dari sebuah presentasi. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setPresentationFormat(String value) {#setPresentationFormat-java.lang.String-}
```
public abstract void setPresentationFormat(String value)
```

Mengembalikan atau mengatur format yang dimaksud dari sebuah presentasi. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getSharedDoc() {#getSharedDoc--}
```
public abstract boolean getSharedDoc()
```

Menentukan apakah presentasi dibagikan antara beberapa orang. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setSharedDoc(boolean value) {#setSharedDoc-boolean-}
```
public abstract void setSharedDoc(boolean value)
```

Menentukan apakah presentasi dibagikan antara beberapa orang. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getApplicationTemplate() {#getApplicationTemplate--}
```
public abstract String getApplicationTemplate()
```

Mengembalikan atau mengatur templat aplikasi. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setApplicationTemplate(String value) {#setApplicationTemplate-java.lang.String-}
```
public abstract void setApplicationTemplate(String value)
```

Mengembalikan atau mengatur templat aplikasi. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getTotalEditingTime() {#getTotalEditingTime--}
```
public abstract double getTotalEditingTime()
```

Total waktu pengeditan presentasi. Baca/tulis double.

**Mengembalikan:**
double

### setTotalEditingTime(double value) {#setTotalEditingTime-double-}
```
public abstract void setTotalEditingTime(double value)
```

Total waktu pengeditan presentasi. Baca/tulis double.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | double |  |

### getTitle() {#getTitle--}
```
public abstract String getTitle()
```

Mengembalikan atau mengatur judul presentasi. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setTitle(String value) {#setTitle-java.lang.String-}
```
public abstract void setTitle(String value)
```

Mengembalikan atau mengatur judul presentasi. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getSubject() {#getSubject--}
```
public abstract String getSubject()
```

Mengembalikan atau mengatur subjek presentasi. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setSubject(String value) {#setSubject-java.lang.String-}
```
public abstract void setSubject(String value)
```

Mengembalikan atau mengatur subjek presentasi. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getAuthor() {#getAuthor--}
```
public abstract String getAuthor()
```

Mengembalikan atau mengatur penulis presentasi. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setAuthor(String value) {#setAuthor-java.lang.String-}
```
public abstract void setAuthor(String value)
```

Mengembalikan atau mengatur penulis presentasi. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getKeywords() {#getKeywords--}
```
public abstract String getKeywords()
```

Mengembalikan atau mengatur kata kunci presentasi. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setKeywords(String value) {#setKeywords-java.lang.String-}
```
public abstract void setKeywords(String value)
```

Mengembalikan atau mengatur kata kunci presentasi. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getComments() {#getComments--}
```
public abstract String getComments()
```

Mengembalikan atau mengatur komentar presentasi. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setComments(String value) {#setComments-java.lang.String-}
```
public abstract void setComments(String value)
```

Mengembalikan atau mengatur komentar presentasi. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getCategory() {#getCategory--}
```
public abstract String getCategory()
```

Mengembalikan atau mengatur kategori presentasi. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setCategory(String value) {#setCategory-java.lang.String-}
```
public abstract void setCategory(String value)
```

Mengembalikan atau mengatur kategori presentasi. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |
| value | java.lang.String |  |

### getCreatedTime() {#getCreatedTime--}
```
public abstract Date getCreatedTime()
```

Mengembalikan tanggal pembuatan presentasi. Nilai dalam UTC. **Baca/tulis** java.util.Date.

**Mengembalikan:**
java.util.Date

### setCreatedTime(Date value) {#setCreatedTime-java.util.Date-}
```
public abstract void setCreatedTime(Date value)
```

Mengembalikan tanggal pembuatan presentasi. Nilai dalam UTC. **Baca/tulis** java.util.Date.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedTime() {#getLastSavedTime--}
```
public abstract Date getLastSavedTime()
```

Mengembalikan tanggal presentasi terakhir dimodifikasi. Nilai dalam UTC. **Baca-saja** dalam kasus Presentation.DocumentProperties (karena akan diperbarui secara internal selama proses penyimpanan objek IPresentation). Dapat diubah melalui instance DocumentProperties yang dikembalikan oleh metode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Lihat contoh pada ringkasan metode [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Mengembalikan:**
java.util.Date

### setLastSavedTime(Date value) {#setLastSavedTime-java.util.Date-}
```
public abstract void setLastSavedTime(Date value)
```

Mengembalikan tanggal presentasi terakhir dimodifikasi. Nilai dalam UTC. **Baca-saja** dalam kasus Presentation.DocumentProperties (karena akan diperbarui secara internal selama proses penyimpanan objek IPresentation). Dapat diubah melalui instance DocumentProperties yang dikembalikan oleh metode [IPresentationInfo.readDocumentProperties](../../com.aspose.slides/ipresentationinfo\#readDocumentProperties). Lihat contoh pada ringkasan metode [IPresentationInfo.updateDocumentProperties(IDocumentProperties)](../../com.aspose.slides/ipresentationinfo\#updateDocumentProperties-IDocumentProperties-).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastPrinted() {#getLastPrinted--}
```
public abstract Date getLastPrinted()
```

Mengembalikan tanggal presentasi terakhir dicetak. **Baca/tulis** java.util.Date.

**Mengembalikan:**
java.util.Date

### setLastPrinted(Date value) {#setLastPrinted-java.util.Date-}
```
public abstract void setLastPrinted(Date value)
```

Mengembalikan tanggal presentasi terakhir dicetak. **Baca/tulis** java.util.Date.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.util.Date |  |

### getLastSavedBy() {#getLastSavedBy--}
```
public abstract String getLastSavedBy()
```

Mengembalikan atau mengatur nama orang terakhir yang memodifikasi presentasi. **Baca/tulis** String.

**Mengembalikan:**
java.lang.String

### setLastSavedBy(String value) {#setLastSavedBy-java.lang.String-}
```
public abstract void setLastSavedBy(String value)
```

Mengembalikan atau mengatur nama orang terakhir yang memodifikasi presentasi. **Baca/tulis** String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getRevisionNumber() {#getRevisionNumber--}
```
public abstract int getRevisionNumber()
```

Mengembalikan atau mengatur nomor revisi presentasi. **Baca/tulis** int.

**Mengembalikan:**
int

### setRevisionNumber(int value) {#setRevisionNumber-int-}
```
public abstract void setRevisionNumber(int value)
```

Mengembalikan atau mengatur nomor revisi presentasi. **Baca/tulis** int.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getContentStatus() {#getContentStatus--}
```
public abstract String getContentStatus()
```

Mengembalikan atau mengatur status konten presentasi. **Baca/tulis** String.

**Mengembalikan:**
java.lang.String

### setContentStatus(String value) {#setContentStatus-java.lang.String-}
```
public abstract void setContentStatus(String value)
```

Mengembalikan atau mengatur status konten presentasi. **Baca/tulis** String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getContentType() {#getContentType--}
```
public abstract String getContentType()
```

Mengembalikan atau mengatur tipe konten presentasi. **Baca/tulis** String.

**Mengembalikan:**
java.lang.String

### setContentType(String value) {#setContentType-java.lang.String-}
```
public abstract void setContentType(String value)
```

Mengembalikan atau mengatur tipe konten presentasi. **Baca/tulis** String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getHyperlinkBase() {#getHyperlinkBase--}
```
public abstract String getHyperlinkBase()
```

Mengembalikan atau mengatur properti dokumen HyperlinkBase. **Baca/tulis** String.

**Mengembalikan:**
java.lang.String

### setHyperlinkBase(String value) {#setHyperlinkBase-java.lang.String-}
```
public abstract void setHyperlinkBase(String value)
```

Mengembalikan atau mengatur properti dokumen HyperlinkBase. **Baca/tulis** String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getScaleCrop() {#getScaleCrop--}
```
public abstract boolean getScaleCrop()
```

Menunjukkan mode tampilan thumbnail dokumen. Atur elemen ini ke **true** untuk mengaktifkan penskalaan thumbnail dokumen ke tampilan. Atur ke **false** untuk memotong thumbnail dokumen sehingga hanya menampilkan bagian yang pas dengan tampilan. **Baca/tulis** boolean.

**Mengembalikan:**
boolean

### setScaleCrop(boolean value) {#setScaleCrop-boolean-}
```
public abstract void setScaleCrop(boolean value)
```

Menunjukkan mode tampilan thumbnail dokumen. Atur elemen ini ke **true** untuk mengaktifkan penskalaan thumbnail dokumen ke tampilan. Atur ke **false** untuk memotong thumbnail dokumen sehingga hanya menampilkan bagian yang pas dengan tampilan. **Baca/tulis** boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getLinksUpToDate() {#getLinksUpToDate--}
```
public abstract boolean getLinksUpToDate()
```

Menunjukkan apakah hyperlink dalam dokumen mutakhir. Atur elemen ini ke **true** untuk menandakan bahwa hyperlink telah diperbarui. Atur ke **false** untuk menandakan bahwa hyperlink sudah usang. **Baca/tulis** boolean.

**Mengembalikan:**
boolean

### setLinksUpToDate(boolean value) {#setLinksUpToDate-boolean-}
```
public abstract void setLinksUpToDate(boolean value)
```

Menunjukkan apakah hyperlink dalam dokumen mutakhir. Atur elemen ini ke **true** untuk menandakan bahwa hyperlink telah diperbarui. Atur ke **false** untuk menandakan bahwa hyperlink sudah usang. **Baca/tulis** boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHyperlinksChanged() {#getHyperlinksChanged--}
```
public abstract boolean getHyperlinksChanged()
```

Menentukan bahwa satu atau lebih hyperlink di bagian ini diperbarui secara eksklusif di bagian ini oleh produsen. Produsen selanjutnya yang membuka dokumen ini harus memperbarui hubungan hyperlink dengan hyperlink baru yang ditentukan di bagian ini. **Baca/tulis** boolean.

**Mengembalikan:**
boolean

### setHyperlinksChanged(boolean value) {#setHyperlinksChanged-boolean-}
```
public abstract void setHyperlinksChanged(boolean value)
```

Menentukan bahwa satu atau lebih hyperlink di bagian ini diperbarui secara eksklusif di bagian ini oleh produsen. Produsen selanjutnya yang membuka dokumen ini harus memperbarui hubungan hyperlink dengan hyperlink baru yang ditentukan di bagian ini. **Baca/tulis** boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSlides() {#getSlides--}
```
public abstract int getSlides()
```

Menentukan total jumlah slide dalam dokumen presentasi. **Baca-saja** int.

**Mengembalikan:**
int

### getHiddenSlides() {#getHiddenSlides--}
```
public abstract int getHiddenSlides()
```

Menentukan jumlah slide tersembunyi dalam dokumen presentasi. **Baca-saja** int.

**Mengembalikan:**
int

### getNotes() {#getNotes--}
```
public abstract int getNotes()
```

Menentukan jumlah slide dalam presentasi yang berisi catatan. **Baca-saja** int.

**Mengembalikan:**
int

### getParagraphs() {#getParagraphs--}
```
public abstract int getParagraphs()
```

Menentukan total jumlah paragraf yang ditemukan dalam dokumen bila berlaku. **Baca-saja** int.

**Mengembalikan:**
int

### getWords() {#getWords--}
```
public abstract int getWords()
```

Menentukan total jumlah kata yang terdapat dalam dokumen. **Baca-saja** int.

**Mengembalikan:**
int

### getMultimediaClips() {#getMultimediaClips--}
```
public abstract int getMultimediaClips()
```

Menentukan total jumlah klip suara atau video yang terdapat dalam dokumen. **Baca-saja** int.

**Mengembalikan:**
int

### getTitlesOfParts() {#getTitlesOfParts--}
```
public abstract String[] getTitlesOfParts()
```

Menentukan judul setiap bagian dokumen. Bagian-bagian ini bukan bagian fisik dokumen melainkan representasi konseptual dari seksi dokumen. **Baca-saja** java.lang.String[].

**Mengembalikan:**
java.lang.String[]

### getHeadingPairs() {#getHeadingPairs--}
```
public abstract IHeadingPair[] getHeadingPairs()
```

Menunjukkan pengelompokan bagian dokumen dan jumlah bagian dalam tiap grup. **Baca-saja** com.aspose.slides.IHeadingPair[].

**Mengembalikan:**
com.aspose.slides.IHeadingPair[]

### getCountOfCustomProperties() {#getCountOfCustomProperties--}
```
public abstract int getCountOfCustomProperties()
```

Mengembalikan jumlah properti khusus yang sebenarnya terdapat dalam koleksi. **Baca-saja** int.

**Mengembalikan:**
int

### getCustomPropertyName(int index) {#getCustomPropertyName-int-}
```
public abstract String getCustomPropertyName(int index)
```

Mengembalikan nama properti khusus pada indeks yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | int | Indeks berbasis nol dari properti khusus yang ingin diambil. |

**Mengembalikan:**
java.lang.String - Nama properti khusus pada indeks yang ditentukan.

### removeCustomProperty(String name) {#removeCustomProperty-java.lang.String-}
```
public abstract boolean removeCustomProperty(String name)
```

Menghapus properti khusus yang terkait dengan nama yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan dihapus. |

**Mengembalikan:**
boolean - Mengembalikan true jika properti dihapus, false jika tidak.

### containsCustomProperty(String name) {#containsCustomProperty-java.lang.String-}
```
public abstract boolean containsCustomProperty(String name)
```

Memeriksa keberadaan properti khusus dengan nama yang ditentukan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diperiksa. |

**Mengembalikan:**
boolean - Mengembalikan true jika properti ada, false jika tidak.

### get_Item(String name) {#get-Item-java.lang.String-}
```
public abstract Object get_Item(String name)
```

Mengembalikan atau mengatur properti khusus yang terkait dengan nama yang ditentukan. **Baca/tulis** Object.

--------------------

Nilai dapat berupa **int**, **float**, **double**, **String**, **boolean** atau **Date**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |

**Mengembalikan:**
java.lang.Object

### set_Item(String name, Object value) {#set-Item-java.lang.String-java.lang.Object-}
```
public abstract void set_Item(String name, Object value)
```

Mengembalikan atau mengatur properti khusus yang terkait dengan nama yang ditentukan. **Baca/tulis** Object.

--------------------

Nilai dapat berupa **int**, **float**, **double**, **String**, **boolean** atau **Date**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String |  |
| value | java.lang.Object |  |

### clearCustomProperties() {#clearCustomProperties--}
```
public abstract void clearCustomProperties()
```

Menghapus semua properti khusus.

### clearBuiltInProperties() {#clearBuiltInProperties--}
```
public abstract void clearBuiltInProperties()
```

Menghapus dan menetapkan nilai default untuk semua properti bawaan.

### getCustomPropertyValue(String name, boolean[] value) {#getCustomPropertyValue-java.lang.String-boolean---}
```
public abstract void getCustomPropertyValue(String name, boolean[] value)
```

Mengambil nilai boolean yang dinamai dari properti khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diambil |
| value | boolean[] | Nilai properti khusus |

### getCustomPropertyValue(String name, int[] value) {#getCustomPropertyValue-java.lang.String-int---}
```
public abstract void getCustomPropertyValue(String name, int[] value)
```

Mengambil nilai integer yang dinamai dari properti khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diambil |
| value | int[] | Nilai properti khusus |

### getCustomPropertyValue(String name, Date[] value) {#getCustomPropertyValue-java.lang.String-java.util.Date---}
```
public abstract void getCustomPropertyValue(String name, Date[] value)
```

Mengambil nilai DateTime yang dinamai dari properti khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diambil |
| value | java.util.Date[] | Nilai properti khusus |

### getCustomPropertyValue(String name, String[] value) {#getCustomPropertyValue-java.lang.String-java.lang.String---}
```
public abstract void getCustomPropertyValue(String name, String[] value)
```

Mengambil nilai string yang dinamai dari properti khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diambil |
| value | java.lang.String[] | Nilai properti khusus |

### getCustomPropertyValue(String name, float[] value) {#getCustomPropertyValue-java.lang.String-float---}
```
public abstract void getCustomPropertyValue(String name, float[] value)
```

Mengambil nilai float yang dinamai dari properti khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diambil |
| value | float[] | Nilai properti khusus |

### getCustomPropertyValue(String name, double[] value) {#getCustomPropertyValue-java.lang.String-double---}
```
public abstract void getCustomPropertyValue(String name, double[] value)
```

Mengambil nilai double yang dinamai dari properti khusus.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diambil |
| value | double[] | Nilai properti khusus |
| nama | java.lang.String | Nama properti khusus yang akan diambil. |
| nilai | double[] | Nilai properti khusus |

### setCustomPropertyValue(String name, boolean value) {#setCustomPropertyValue-java.lang.String-boolean-}
```
public abstract void setCustomPropertyValue(String name, boolean value)
```

Mengatur properti khusus boolean dengan nama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diatur |
| value | boolean | Nilai properti khusus |

### setCustomPropertyValue(String name, int value) {#setCustomPropertyValue-java.lang.String-int-}
```
public abstract void setCustomPropertyValue(String name, int value)
```

Mengatur properti khusus integer dengan nama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diatur |
| value | int | Nilai properti khusus |

### setCustomPropertyValue(String name, Date value) {#setCustomPropertyValue-java.lang.String-java.util.Date-}
```
public abstract void setCustomPropertyValue(String name, Date value)
```

Mengatur properti khusus DateTime dengan nama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diatur |
| value | java.util.Date | Nilai properti khusus |

### setCustomPropertyValue(String name, String value) {#setCustomPropertyValue-java.lang.String-java.lang.String-}
```
public abstract void setCustomPropertyValue(String name, String value)
```

Mengatur properti khusus string dengan nama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diatur |
| value | java.lang.String | Nilai properti khusus |

### setCustomPropertyValue(String name, float value) {#setCustomPropertyValue-java.lang.String-float-}
```
public abstract void setCustomPropertyValue(String name, float value)
```

Mengatur properti khusus float dengan nama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diatur |
| value | float | Nilai properti khusus |

### setCustomPropertyValue(String name, double value) {#setCustomPropertyValue-java.lang.String-double-}
```
public abstract void setCustomPropertyValue(String name, double value)
```

Mengatur properti khusus double dengan nama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| name | java.lang.String | Nama properti khusus yang akan diatur |
| value | double | Nilai properti khusus |

### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabel[] getSensitivityLabels()
```

Mengambil array label sensitivitas dari properti dokumen khusus (Microsoft Information Protection SDK Metadata).

--------------------

> ```
> The following code shows how to move the sensitivity labels information from the custom document properties 
>   to the modern SensitivityLabels collection:
>   
>  Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      // Get sensitivity labels from the custom document properties
>      ISensitivityLabel[] mipSensitivityLabels = pres.getDocumentProperties().getSensitivityLabels();
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
>      for (ISensitivityLabel sensitivityLabel : mipSensitivityLabels)
>      {
>          // Add label to the collection
>          // Here you can add a check for the validity of the label information (the label is available, etc)
>          sensitivityLabels.add(sensitivityLabel);
>      }
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
com.aspose.slides.ISensitivityLabel[]