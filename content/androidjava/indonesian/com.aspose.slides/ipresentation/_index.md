---
title: IPresentation
second_title: Referensi API Java Aspose.Slides untuk Android
description: Dokumen presentasi
type: docs
url: /id/com.aspose.slides/ipresentation/
---
**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.IPresentationComponent](../../com.aspose.slides/ipresentationcomponent), com.aspose.ms.System.IDisposable
```
public interface IPresentation extends IPresentationComponent, System.IDisposable
```

Dokumen Presentasi
## Metode

| Method | Description |
| --- | --- |
| [getCurrentDateTime()](#getCurrentDateTime--) | Mengembalikan atau mengatur tanggal dan waktu yang akan menggantikan konten bidang datetime. |
| [setCurrentDateTime(Date value)](#setCurrentDateTime-java.util.Date-) | Mengembalikan atau mengatur tanggal dan waktu yang akan menggantikan konten bidang datetime. |
| [getHeaderFooterManager()](#getHeaderFooterManager--) | Mengembalikan manajer HeaderFooter dari presentasi. |
| [getProtectionManager()](#getProtectionManager--) | Mendapatkan manajer izin untuk presentasi ini. |
| [getSlides()](#getSlides--) | Mengembalikan daftar semua slide yang didefinisikan dalam presentasi. |
| [getSections()](#getSections--) | Mengembalikan daftar semua bagian slide yang didefinisikan dalam presentasi. |
| [getSlideSize()](#getSlideSize--) | Mengembalikan objek ukuran slide. |
| [getNotesSize()](#getNotesSize--) | Mengembalikan objek ukuran slide catatan. |
| [getLayoutSlides()](#getLayoutSlides--) | Mengembalikan daftar semua slide tata letak yang didefinisikan dalam presentasi. |
| [getMasters()](#getMasters--) | Mengembalikan daftar semua master slide yang didefinisikan dalam presentasi. |
| [getMasterNotesSlideManager()](#getMasterNotesSlideManager--) | Mengembalikan manajer master catatan. |
| [getMasterHandoutSlideManager()](#getMasterHandoutSlideManager--) | Mengembalikan manajer master handout. |
| [getFontsManager()](#getFontsManager--) | Mengembalikan manajer font. |
| [getDefaultTextStyle()](#getDefaultTextStyle--) | Mengembalikan gaya teks default untuk shape. |
| [getCommentAuthors()](#getCommentAuthors--) | Mengembalikan koleksi penulis komentar. |
| [getDocumentProperties()](#getDocumentProperties--) | Mengembalikan objek DocumentProperties yang berisi properti dokumen standar dan custom. |
| [getImages()](#getImages--) | Mengembalikan koleksi semua gambar dalam presentasi. |
| [getAudios()](#getAudios--) | Mengembalikan koleksi semua file audio yang disematkan dalam presentasi. |
| [getVideos()](#getVideos--) | Mengembalikan koleksi semua file video yang disematkan dalam presentasi. |
| [getCustomData()](#getCustomData--) | Mengembalikan data khusus presentasi. |
| [getVbaProject()](#getVbaProject--) | Mendapatkan proyek VBA dengan makro presentasi. |
| [setVbaProject(IVbaProject value)](#setVbaProject-com.aspose.slides.IVbaProject-) | Mendapatkan proyek VBA dengan makro presentasi. |
| [getSourceFormat()](#getSourceFormat--) | Mengembalikan informasi tentang format asal presentasi dimuat. |
| [getMasterTheme()](#getMasterTheme--) | Mengembalikan tema master dari presentasi. |
| [getHyperlinkQueries()](#getHyperlinkQueries--) | Memberikan akses mudah ke semua hyperlink yang terdapat dalam semua slide presentasi (tidak termasuk master, layout, slide catatan). |
| [getViewProperties()](#getViewProperties--) | Mendapatkan properti tampilan seluruh presentasi. |
| [getFirstSlideNumber()](#getFirstSlideNumber--) | Mewakili nomor slide pertama dalam presentasi. |
| [setFirstSlideNumber(int value)](#setFirstSlideNumber-int-) | Mewakili nomor slide pertama dalam presentasi. |
| [getAllCustomXmlParts()](#getAllCustomXmlParts--) | Mengembalikan semua bagian data khusus dalam presentasi. |
| [getDigitalSignatures()](#getDigitalSignatures--) | Mengembalikan koleksi tanda tangan yang digunakan untuk menandatangani presentasi. |
| [getSensitivityLabels()](#getSensitivityLabels--) | Mengembalikan koleksi label sensitivitas yang diterapkan pada dokumen presentasi. |
| [save(String fname, int format)](#save-java.lang.String-int-) | Menyimpan semua slide presentasi ke file dengan format yang ditentukan. |
| [save(OutputStream stream, int format)](#save-java.io.OutputStream-int-) | Menyimpan semua slide presentasi ke aliran dengan format yang ditentukan. |
| [save(String fname, int format, ISaveOptions options)](#save-java.lang.String-int-com.aspose.slides.ISaveOptions-) | Menyimpan semua slide presentasi ke file dengan format yang ditentukan dan dengan opsi tambahan. |
| [save(OutputStream stream, int format, ISaveOptions options)](#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-) | Menyimpan semua slide presentasi ke aliran dengan format yang ditentukan dan dengan opsi tambahan. |
| [save(String fname, int[] slides, int format)](#save-java.lang.String-int---int-) | Menyimpan slide yang ditentukan dari presentasi ke file dengan format yang ditentukan. |
| [save(String fname, int[] slides, int format, ISaveOptions options)](#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-) | Menyimpan slide yang ditentukan dari presentasi ke file dengan format yang ditentukan. |
| [save(OutputStream stream, int[] slides, int format)](#save-java.io.OutputStream-int---int-) | Menyimpan slide yang ditentukan dari presentasi ke aliran dengan format yang ditentukan. |
| [save(OutputStream stream, int[] slides, int format, ISaveOptions options)](#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-) | Menyimpan slide yang ditentukan dari presentasi ke aliran dengan format yang ditentukan. |
| [save(IXamlOptions options)](#save-com.aspose.slides.IXamlOptions-) | Menyimpan semua slide presentasi ke sekumpulan file yang mewakili markup XAML. |
| [getImages(IRenderingOptions options)](#getImages-com.aspose.slides.IRenderingOptions-) | Mengembalikan objek Gambar Thumbnail untuk semua slide presentasi. |
| [getImages(IRenderingOptions options, int[] slides)](#getImages-com.aspose.slides.IRenderingOptions-int---) | Mengembalikan objek IImage Thumbnail untuk slide yang ditentukan dari presentasi. |
| [getImages(IRenderingOptions options, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-float-float-) | Mengembalikan objek Gambar Thumbnail untuk semua slide presentasi dengan skala khusus. |
| [getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)](#getImages-com.aspose.slides.IRenderingOptions-int---float-float-) | Mengembalikan objek Gambar Thumbnail untuk slide yang ditentukan dari presentasi dengan skala khusus. |
| [getImages(IRenderingOptions options, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-) | Mengembalikan objek Gambar Thumbnail untuk semua slide presentasi dengan ukuran tertentu. |
| [getImages(IRenderingOptions options, int[] slides, Size imageSize)](#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-) | Mengembalikan objek Gambar Thumbnail untuk slide yang ditentukan dari presentasi dengan ukuran tertentu. |
| [getSlideById(long id)](#getSlideById-long-) | Mengembalikan Slide, MasterSlide atau LayoutSlide berdasarkan Id. |
| [joinPortionsWithSameFormatting()](#joinPortionsWithSameFormatting--) | Menggabungkan bagian teks dengan format yang sama di semua paragraf dalam semua shape yang dapat diterima di semua slide. |
| [highlightText(String text, Integer highlightColor)](#highlightText-java.lang.String-java.lang.Integer-) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)](#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Menyorot semua kecocokan teks contoh dengan warna yang ditentukan. |
| [highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)](#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-) | Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan. |
| [replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)](#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-) | Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan. |
| [replaceRegex(Pattern regex, String newText, IFindResultCallback callback)](#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-) | Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan. |
### getCurrentDateTime() {#getCurrentDateTime--}
```
public abstract Date getCurrentDateTime()
```

Mengembalikan atau mengatur tanggal dan waktu yang akan menggantikan konten bidang datetime. Waktu pembuatan objek Presentation ini secara default. Baca/tulis java.util.Date.

**Mengembalikan:**
java.util.Date
### setCurrentDateTime(Date value) {#setCurrentDateTime-java.util.Date-}
```
public abstract void setCurrentDateTime(Date value)
```

Mengembalikan atau mengatur tanggal dan waktu yang akan menggantikan konten bidang datetime. Waktu pembuatan objek Presentation ini secara default. Baca/tulis java.util.Date.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date |  |
### getHeaderFooterManager() {#getHeaderFooterManager--}
```
public abstract IPresentationHeaderFooterManager getHeaderFooterManager()
```

Mengembalikan manajer HeaderFooter dari presentasi. Hanya baca [IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager).

**Mengembalikan:**
[IPresentationHeaderFooterManager](../../com.aspose.slides/ipresentationheaderfootermanager)
### getProtectionManager() {#getProtectionManager--}
```
public abstract IProtectionManager getProtectionManager()
```

Mendapatkan manajer izin untuk presentasi ini. Hanya baca [IProtectionManager](../../com.aspose.slides/iprotectionmanager).

**Mengembalikan:**
[IProtectionManager](../../com.aspose.slides/iprotectionmanager)
### getSlides() {#getSlides--}
```
public abstract ISlideCollection getSlides()
```

Mengembalikan daftar semua slide yang didefinisikan dalam presentasi. Hanya baca [ISlideCollection](../../com.aspose.slides/islidecollection).

**Mengembalikan:**
[ISlideCollection](../../com.aspose.slides/islidecollection)
### getSections() {#getSections--}
```
public abstract ISectionCollection getSections()
```

Mengembalikan daftar semua bagian slide yang didefinisikan dalam presentasi. Hanya baca [ISectionCollection](../../com.aspose.slides/isectioncollection).

**Mengembalikan:**
[ISectionCollection](../../com.aspose.slides/isectioncollection)
### getSlideSize() {#getSlideSize--}
```
public abstract ISlideSize getSlideSize()
```

Mengembalikan objek ukuran slide. Hanya baca [ISlideSize](../../com.aspose.slides/islidesize).

**Mengembalikan:**
[ISlideSize](../../com.aspose.slides/islidesize)
### getNotesSize() {#getNotesSize--}
```
public abstract INotesSize getNotesSize()
```

Mengembalikan objek ukuran slide catatan. Hanya baca [INotesSize](../../com.aspose.slides/inotessize).

**Mengembalikan:**
[INotesSize](../../com.aspose.slides/inotessize)
### getLayoutSlides() {#getLayoutSlides--}
```
public abstract IGlobalLayoutSlideCollection getLayoutSlides()
```

Mengembalikan daftar semua slide tata letak yang didefinisikan dalam presentasi. Hanya baca [IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection).

--------------------

Anda dapat mengakses API alternatif untuk menambah/menyisipkan/menghapus/menduplikasi slide tata letak dengan menggunakan properti IMasterSlide.LayoutSlides.

**Mengembalikan:**
[IGlobalLayoutSlideCollection](../../com.aspose.slides/igloballayoutslidecollection)
### getMasters() {#getMasters--}
```
public abstract IMasterSlideCollection getMasters()
```

Mengembalikan daftar semua master slide yang didefinisikan dalam presentasi. Hanya baca [IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection).

**Mengembalikan:**
[IMasterSlideCollection](../../com.aspose.slides/imasterslidecollection)
### getMasterNotesSlideManager() {#getMasterNotesSlideManager--}
```
public abstract IMasterNotesSlideManager getMasterNotesSlideManager()
```

Mengembalikan manajer master catatan. Hanya baca [IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager).

**Mengembalikan:**
[IMasterNotesSlideManager](../../com.aspose.slides/imasternotesslidemanager)
### getMasterHandoutSlideManager() {#getMasterHandoutSlideManager--}
```
public abstract IMasterHandoutSlideManager getMasterHandoutSlideManager()
```

Mengembalikan manajer master handout. Hanya baca [IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager).

**Mengembalikan:**
[IMasterHandoutSlideManager](../../com.aspose.slides/imasterhandoutslidemanager)
### getFontsManager() {#getFontsManager--}
```
public abstract IFontsManager getFontsManager()
```

Mengembalikan manajer font. Hanya baca [IFontsManager](../../com.aspose.slides/ifontsmanager).

**Mengembalikan:**
[IFontsManager](../../com.aspose.slides/ifontsmanager)
### getDefaultTextStyle() {#getDefaultTextStyle--}
```
public abstract ITextStyle getDefaultTextStyle()
```

Mengembalikan gaya teks default untuk shape. Hanya baca [ITextStyle](../../com.aspose.slides/itextstyle).

**Mengembalikan:**
[ITextStyle](../../com.aspose.slides/itextstyle)
### getCommentAuthors() {#getCommentAuthors--}
```
public abstract ICommentAuthorCollection getCommentAuthors()
```

Mengembalikan koleksi penulis komentar. Hanya baca [ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection).

**Mengembalikan:**
[ICommentAuthorCollection](../../com.aspose.slides/icommentauthorcollection)
### getDocumentProperties() {#getDocumentProperties--}
```
public abstract IDocumentProperties getDocumentProperties()
```

Mengembalikan objek DocumentProperties yang berisi properti dokumen standar dan custom. Hanya baca [IDocumentProperties](../../com.aspose.slides/idocumentproperties).

**Mengembalikan:**
[IDocumentProperties](../../com.aspose.slides/idocumentproperties)
### getImages() {#getImages--}
```
public abstract IImageCollection getImages()
```

Mengembalikan koleksi semua gambar dalam presentasi. Hanya baca [IImageCollection](../../com.aspose.slides/iimagecollection).

**Mengembalikan:**
[IImageCollection](../../com.aspose.slides/iimagecollection)
### getAudios() {#getAudios--}
```
public abstract IAudioCollection getAudios()
```

Mengembalikan koleksi semua file audio yang disematkan dalam presentasi. Hanya baca [IAudioCollection](../../com.aspose.slides/iaudiocollection).

**Mengembalikan:**
[IAudioCollection](../../com.aspose.slides/iaudiocollection)
### getVideos() {#getVideos--}
```
public abstract IVideoCollection getVideos()
```

Mengembalikan koleksi semua file video yang disematkan dalam presentasi. Hanya baca [IVideoCollection](../../com.aspose.slides/ivideocollection).

**Mengembalikan:**
[IVideoCollection](../../com.aspose.slides/ivideocollection)
### getCustomData() {#getCustomData--}
```
public abstract ICustomData getCustomData()
```

Mengembalikan data khusus presentasi. Hanya baca [ICustomData](../../com.aspose.slides/icustomdata).

**Mengembalikan:**
[ICustomData](../../com.aspose.slides/icustomdata)
### getVbaProject() {#getVbaProject--}
```
public abstract IVbaProject getVbaProject()
```

Mendapatkan proyek VBA dengan makro presentasi. Baca/tulis [IVbaProject](../../com.aspose.slides/ivbaproject).

**Mengembalikan:**
[IVbaProject](../../com.aspose.slides/ivbaproject)
### setVbaProject(IVbaProject value) {#setVbaProject-com.aspose.slides.IVbaProject-}
```
public abstract void setVbaProject(IVbaProject value)
```

Mendapatkan proyek VBA dengan makro presentasi. Baca/tulis [IVbaProject](../../com.aspose.slides/ivbaproject).

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IVbaProject](../../com.aspose.slides/ivbaproject) |  |
### getSourceFormat() {#getSourceFormat--}
```
public abstract int getSourceFormat()
```

Mengembalikan informasi tentang format asal presentasi dimuat. Hanya baca [SourceFormat](../../com.aspose.slides/sourceformat).

**Mengembalikan:**
int
### getMasterTheme() {#getMasterTheme--}
```
public abstract IMasterTheme getMasterTheme()
```

Mengembalikan tema master dari presentasi. Hanya baca [IMasterTheme](../../com.aspose.slides/imastertheme).

**Mengembalikan:**
[IMasterTheme](../../com.aspose.slides/imastertheme)
### getHyperlinkQueries() {#getHyperlinkQueries--}
```
public abstract IHyperlinkQueries getHyperlinkQueries()
```

Memberikan akses mudah ke semua hyperlink yang terdapat dalam semua slide presentasi (tidak termasuk master, layout, slide catatan). Hanya baca [IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries).

**Mengembalikan:**
[IHyperlinkQueries](../../com.aspose.slides/ihyperlinkqueries)
### getViewProperties() {#getViewProperties--}
```
public abstract IViewProperties getViewProperties()
```

Mendapatkan properti tampilan seluruh presentasi. Hanya baca [IViewProperties](../../com.aspose.slides/iviewproperties).

**Mengembalikan:**
[IViewProperties](../../com.aspose.slides/iviewproperties)
### getFirstSlideNumber() {#getFirstSlideNumber--}
```
public abstract int getFirstSlideNumber()
```

Mewakili nomor slide pertama dalam presentasi. Baca/tulis int.

**Mengembalikan:**
int
### setFirstSlideNumber(int value) {#setFirstSlideNumber-int-}
```java
public abstract void setFirstSlideNumber(int value)
```

Mewakili nomor slide pertama dalam presentasi. Baca/tulis int.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |
### getAllCustomXmlParts() {#getAllCustomXmlParts--}
```
public abstract ICustomXmlPart[] getAllCustomXmlParts()
```

Mengembalikan semua bagian data khusus dalam presentasi. Hanya baca ICustomXmlPart[].

**Mengembalikan:**
com.aspose.slides.ICustomXmlPart[]
### getDigitalSignatures() {#getDigitalSignatures--}
```
public abstract IDigitalSignatureCollection getDigitalSignatures()
```

Mengembalikan koleksi tanda tangan yang digunakan untuk menandatangani presentasi. Hanya baca [IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentationSigned.pptx");
>  try
>  {
>      if (pres.getDigitalSignatures().size() > 0)
>      {
>          boolean allSignaturesAreValid = true;
>          System.out.println("Signatures used to sign the presentation: ");
>          for (IDigitalSignature signature : pres.getDigitalSignatures())
>          {
>             System.out.println(signature.getCertificate().hashCode() + ", "
>                    + signature.getSignTime().toString() + " -- " + (signature.isValid() ? "VALID" : "INVALID"));
>             allSignaturesAreValid &= signature.isValid();
>          }
>          if (allSignaturesAreValid)
>             System.out.println("Presentation is genuine, all signatures are valid.");
>          else
>             System.out.println("Presentation has been modified since signing.");
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[IDigitalSignatureCollection](../../com.aspose.slides/idigitalsignaturecollection)
### getSensitivityLabels() {#getSensitivityLabels--}
```
public abstract ISensitivityLabelCollection getSensitivityLabels()
```

Mengembalikan koleksi label sensitivitas yang diterapkan pada dokumen presentasi. Hanya baca [ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection).

--------------------

> ```
> Presentation pres = new Presentation("SomePresentation.pptx");
>  try {
>      ISensitivityLabelCollection sensitivityLabels = pres.getSensitivityLabels();
> 
>      // Cetak label yang diterapkan
>      for (ISensitivityLabel sensitivityLabel : sensitivityLabels)
>          System.out.println("Label Id " + sensitivityLabel.getId() + " from Azure AD site " + sensitivityLabel.getSiteId());
> 
>      // Tambahkan label baru
>      String labelIdString = "{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"; // Dapatkan Id label sensitivitas dari kebijakan
>      UUID siteIdGuid = UUID.fromString("{xxxxxxxx-xxxx-xxxx-xxxx-xxxxxxxxxxxx}"); // Dapatkan pengenal situs Azure AD dari kebijakan
>      ISensitivityLabel label = sensitivityLabels.add(labelIdString, siteIdGuid, true, SensitivityLabelAssignmentType.Privileged);
>      label.getContentMarkTypes().addItem(SensitivityLabelContentType.Footer);
> 
>      pres.save("SensitivityLabel.pptx", SaveFormat.Pptx);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
[ISensitivityLabelCollection](../../com.aspose.slides/isensitivitylabelcollection)
### save(String fname, int format) {#save-java.lang.String-int-}
```
public abstract void save(String fname, int format)
```

Menyimpan semua slide presentasi ke file dengan format yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path ke file yang dibuat. |
| format | int | Format data yang diekspor. |
### save(OutputStream stream, int format) {#save-java.io.OutputStream-int-}
```
public abstract void save(OutputStream stream, int format)
```

Menyimpan semua slide presentasi ke aliran dengan format yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran keluaran. |
| format | int | Format data yang diekspor. |
### save(String fname, int format, ISaveOptions options) {#save-java.lang.String-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int format, ISaveOptions options)
```

Menyimpan semua slide presentasi ke file dengan format yang ditentukan dan dengan opsi tambahan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path ke file yang dibuat. |
| format | int | Format data yang diekspor. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opsi format tambahan. |
### save(OutputStream stream, int format, ISaveOptions options) {#save-java.io.OutputStream-int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int format, ISaveOptions options)
```

Menyimpan semua slide presentasi ke aliran dengan format yang ditentukan dan dengan opsi tambahan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran keluaran. |
| format | int | Format data yang diekspor. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opsi format tambahan. |
### save(String fname, int[] slides, int format) {#save-java.lang.String-int---int-}
```
public abstract void save(String fname, int[] slides, int format)
```

Menyimpan slide yang ditentukan dari presentasi ke file dengan format yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path ke file yang dibuat. |
| slides | int[] | Array dengan posisi slide, dimulai dari 1. |
| format | int | Format data yang diekspor. |
### save(String fname, int[] slides, int format, ISaveOptions options) {#save-java.lang.String-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(String fname, int[] slides, int format, ISaveOptions options)
```

Menyimpan slide yang ditentukan dari presentasi ke file dengan format yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| fname | java.lang.String | Path ke file yang dibuat. |
| slides | int[] | Array dengan posisi slide, dimulai dari 1. |
| format | int | Format data yang diekspor. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opsi format tambahan. |
### save(OutputStream stream, int[] slides, int format) {#save-java.io.OutputStream-int---int-}
```
public abstract void save(OutputStream stream, int[] slides, int format)
```

Menyimpan slide yang ditentukan dari presentasi ke aliran dengan format yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran keluaran. |
| slides | int[] | Array dengan posisi slide, dimulai dari 1. |
| format | int | Format data yang diekspor. |
### save(OutputStream stream, int[] slides, int format, ISaveOptions options) {#save-java.io.OutputStream-int---int-com.aspose.slides.ISaveOptions-}
```
public abstract void save(OutputStream stream, int[] slides, int format, ISaveOptions options)
```

Menyimpan slide yang ditentukan dari presentasi ke aliran dengan format yang ditentukan.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| stream | java.io.OutputStream | Aliran keluaran. |
| slides | int[] | Array dengan posisi slide, dimulai dari 1. |
| format | int | Format data yang diekspor. |
| options | [ISaveOptions](../../com.aspose.slides/isaveoptions) | Opsi format tambahan. |
### save(IXamlOptions options) {#save-com.aspose.slides.IXamlOptions-}
```
public abstract void save(IXamlOptions options)
```

Menyimpan semua slide presentasi ke sekumpulan file yang mewakili markup XAML.

--------------------

> ```
> Presentation pres = new Presentation("pres.pptx");
>  try {
>      XamlOptions xamlOptions = new XamlOptions();
>      xamlOptions.setExportHiddenSlides(true);
> 
>      pres.save(xamlOptions);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IXamlOptions](../../com.aspose.slides/ixamloptions) | Opsi format XAML. |
### getImages(IRenderingOptions options) {#getImages-com.aspose.slides.IRenderingOptions-}
```
public abstract IImage[] getImages(IRenderingOptions options)
```

Mengembalikan objek Gambar Thumbnail untuk semua slide presentasi.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi rendering. |

**Mengembalikan:**
com.aspose.slides.IImage[] - objek IImage.
### getImages(IRenderingOptions options, int[] slides) {#getImages-com.aspose.slides.IRenderingOptions-int---}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides)
```

Mengembalikan objek IImage Thumbnail untuk slide yang ditentukan dari presentasi.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi rendering. |
| slides | int[] | Array dengan posisi slide, dimulai dari 1. |

**Mengembalikan:**
com.aspose.slides.IImage[] - objek IImage.
### getImages(IRenderingOptions options, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, float scaleX, float scaleY)
```

Mengembalikan objek Gambar Thumbnail untuk semua slide presentasi dengan skala khusus.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi rendering. |
| scaleX | float | Nilai yang digunakan untuk mengubah skala Thumbnail ini pada arah sumbu x. |
| scaleY | float | Nilai yang digunakan untuk mengubah skala Thumbnail ini pada arah sumbu y. |

**Mengembalikan:**
com.aspose.slides.IImage[] - objek Bitmap.
### getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY) {#getImages-com.aspose.slides.IRenderingOptions-int---float-float-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, float scaleX, float scaleY)
```

Mengembalikan objek Gambar Thumbnail untuk slide yang ditentukan dari presentasi dengan skala khusus.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi rendering. |
| slides | int[] | Array dengan posisi slide, dimulai dari 1. |
| scaleX | float | Nilai yang digunakan untuk mengubah skala Thumbnail ini pada arah sumbu x. |
| scaleY | float | Nilai yang digunakan untuk mengubah skala Thumbnail ini pada arah sumbu y. |

**Mengembalikan:**
com.aspose.slides.IImage[] - objek IImage.
### getImages(IRenderingOptions options, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, Size imageSize)
```

Mengembalikan objek Gambar Thumbnail untuk semua slide presentasi dengan ukuran tertentu.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi rendering. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Ukuran gambar yang akan dibuat. |

**Mengembalikan:**
com.aspose.slides.IImage[] - objek IImage.
### getImages(IRenderingOptions options, int[] slides, Size imageSize) {#getImages-com.aspose.slides.IRenderingOptions-int---com.aspose.slides.android.Size-}
```
public abstract IImage[] getImages(IRenderingOptions options, int[] slides, Size imageSize)
```

Mengembalikan objek Gambar Thumbnail untuk slide yang ditentukan dari presentasi dengan ukuran tertentu.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [IRenderingOptions](../../com.aspose.slides/irenderingoptions) | Opsi rendering. |
| slides | int[] | Array dengan posisi slide, dimulai dari 1. |
| imageSize | [Size](../../com.aspose.slides.android/size) | Ukuran gambar yang akan dibuat. |

**Mengembalikan:**
com.aspose.slides.IImage[] - objek IImage.
### getSlideById(long id) {#getSlideById-long-}
```
public abstract IBaseSlide getSlideById(long id)
```

Mengembalikan Slide, MasterSlide atau LayoutSlide berdasarkan Id.

**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| id | long | Id dari slide. |

**Mengembalikan:**
[IBaseSlide](../../com.aspose.slides/ibaseslide) - objek IBaseSlide.
### joinPortionsWithSameFormatting() {#joinPortionsWithSameFormatting--}
```
public abstract void joinPortionsWithSameFormatting()
```

Menggabungkan bagian teks dengan format yang sama di semua paragraf dalam semua shape yang dapat diterima di semua slide.
### highlightText(String text, Integer highlightColor) {#highlightText-java.lang.String-java.lang.Integer-}
```
public abstract void highlightText(String text, Integer highlightColor)
```

Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // menyoroti semua kemunculan 'the' terpisah
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan disorot. |
| highlightColor | java.lang.Integer | Warna untuk menyorot teks. |
### highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback) {#highlightText-java.lang.String-java.lang.Integer-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightText(String text, Integer highlightColor, ITextSearchOptions options, IFindResultCallback callback)
```

Menyorot semua kecocokan teks contoh dengan warna yang ditentukan.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint presentation.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // menyoroti semua kemunculan terpisah 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| text | java.lang.String | Teks yang akan disorot. |
| highlightColor | java.lang.Integer | Warna untuk menyorot teks. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opsi pencarian teks [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback) {#highlightRegex-java.util.regex.Pattern-java.lang.Integer-com.aspose.slides.IFindResultCallback-}
```
public abstract void highlightRegex(Pattern regex, Integer highlightColor, IFindResultCallback callback)
```

Menyorot semua kecocokan ekspresi reguler dengan warna yang ditentukan.

--------------------

> ```
> The following code sample shows how to highlight text in a PowerPoint Presentation using a regular expression.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx");
>  try {
>      // menyoroti semua kemunculan terpisah 'the'
>      presentation.highlightText("the", Color.MAGENTA);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Ekspresi reguler java.util.regex.Pattern untuk mendapatkan string yang akan disorot. |
| highlightColor | java.lang.Integer | Warna untuk menyorot teks. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback) {#replaceText-java.lang.String-java.lang.String-com.aspose.slides.ITextSearchOptions-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceText(String oldText, String newText, ITextSearchOptions options, IFindResultCallback callback)
```

Mengganti semua kemunculan teks yang ditentukan dengan teks lain yang ditentukan.

--------------------

> ```
> The following sample code shows how to replace one specified string with another specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Ganti semua kemunculan terpisah 'the' dengan '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| oldText | java.lang.String | String yang akan diganti. |
| newText | java.lang.String | String untuk mengganti semua kemunculan oldText. |
| options | [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions) | Opsi pencarian teks [ITextSearchOptions](../../com.aspose.slides/itextsearchoptions). |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |
### replaceRegex(Pattern regex, String newText, IFindResultCallback callback) {#replaceRegex-java.util.regex.Pattern-java.lang.String-com.aspose.slides.IFindResultCallback-}
```
public abstract void replaceRegex(Pattern regex, String newText, IFindResultCallback callback)
```

Mengganti semua kecocokan ekspresi reguler dengan string yang ditentukan.

--------------------

> ```
> The following code sample shows how to replace text using regular expression with the specified string.
>  
>  Presentation presentation = new Presentation("SomePresentation.pptx")
>  try {
>      TextSearchOptions textSearchOptions = new TextSearchOptions();
>      textSearchOptions.setWholeWordsOnly(true);
>      // Ganti semua kemunculan terpisah 'the' dengan '***'
>      presentation.replaceText("the", "***", textSearchOptions, null);
>      presentation.save("SomePresentation-out2.pptx", SaveFormat.Pptx);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Type | Description |
| --- | --- | --- |
| regex | java.util.regex.Pattern | Ekspresi reguler java.util.regex.Pattern untuk mendapatkan string yang akan diganti. |
| newText | java.lang.String | String untuk mengganti semua kemunculan string yang akan diganti. |
| callback | [IFindResultCallback](../../com.aspose.slides/ifindresultcallback) | Objek callback untuk menerima hasil pencarian [IFindResultCallback](../../com.aspose.slides/ifindresultcallback). |