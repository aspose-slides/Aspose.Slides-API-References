---
title: ILoadOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Memungkinkan untuk menentukan opsi tambahan seperti format atau font default saat memuat sebuah presentasi.
type: docs
url: /id/com.aspose.slides/iloadoptions/
---```
public interface ILoadOptions
```

Memungkinkan untuk menentukan opsi tambahan (seperti format atau font default) saat memuat sebuah presentasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Mengembalikan atau mengatur format presentasi yang akan dimuat. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Mengembalikan atau mengatur format presentasi yang akan dimuat. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Mengembalikan atau mengatur font Regular yang digunakan bila font sumber tidak ditemukan. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Mengembalikan atau mengatur font Regular yang digunakan bila font sumber tidak ditemukan. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Mengembalikan atau mengatur font Symbol yang digunakan bila font sumber tidak ditemukan. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Mengembalikan atau mengatur font Symbol yang digunakan bila font sumber tidak ditemukan. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Mengembalikan atau mengatur font Asian yang digunakan bila font sumber tidak ditemukan. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Mengembalikan atau mengatur font Asian yang digunakan bila font sumber tidak ditemukan. |
| [getPassword()](#getPassword--) | Mengambil atau mengatur kata sandi. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Mengambil atau mengatur kata sandi. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Properti ini relevan jika file presentasi dilindungi kata sandi. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Properti ini relevan jika file presentasi dilindungi kata sandi. |
| [getWarningCallback()](#getWarningCallback--) | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Mewakili opsi yang dapat digunakan untuk mengelola perilaku penanganan Binary Large Objects (BLOB), seperti penggunaan file sementara atau batas byte BLOB dalam memori. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Mewakili opsi yang dapat digunakan untuk mengelola perilaku penanganan Binary Large Objects (BLOB), seperti penggunaan file sementara atau batas byte BLOB dalam memori. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi. |
| [getInterruptionToken()](#getInterruptionToken--) | Token untuk memantau permintaan interupsi. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Token untuk memantau permintaan interupsi. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Mengembalikan atau mengatur antarmuka callback yang mengelola pemuatan sumber daya eksternal. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Mengembalikan atau mengatur antarmuka callback yang mengelola pemuatan sumber daya eksternal. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Mewakili opsi yang dapat digunakan untuk menentukan perilaku lembar kerja tambahan. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Mewakili opsi yang dapat digunakan untuk menentukan perilaku lembar kerja tambahan. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Mengembalikan atau mengatur bahasa default untuk teks presentasi. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Mengembalikan atau mengatur bahasa default untuk teks presentasi. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Menentukan apakah Aspose.Slides akan menghapus semua objek biner tersemat saat pemuatan presentasi. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Menentukan apakah Aspose.Slides akan menghapus semua objek biner tersemat saat pemuatan presentasi. |

### getLoadFormat() {#getLoadFormat--}
```
public abstract int getLoadFormat()
```

Mengembalikan atau mengatur format presentasi yang akan dimuat. Baca/tulis [LoadFormat](../../com.aspose.slides/loadformat).

**Mengembalikan:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public abstract void setLoadFormat(int value)
```

Mengembalikan atau mengatur format presentasi yang akan dimuat. Baca/tulis [LoadFormat](../../com.aspose.slides/loadformat).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public abstract String getDefaultRegularFont()
```

Mengembalikan atau mengatur font Regular yang digunakan bila font sumber tidak ditemukan. Baca-tulis String.

**Mengembalikan:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public abstract void setDefaultRegularFont(String value)
```

Mengembalikan atau mengatur font Regular yang digunakan bila font sumber tidak ditemukan. Baca-tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public abstract String getDefaultSymbolFont()
```

Mengembalikan atau mengatur font Symbol yang digunakan bila font sumber tidak ditemukan. Baca-tulis String.

**Mengembalikan:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public abstract void setDefaultSymbolFont(String value)
```

Mengembalikan atau mengatur font Symbol yang digunakan bila font sumber tidak ditemukan. Baca-tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public abstract String getDefaultAsianFont()
```

Mengembalikan atau mengatur font Asian yang digunakan bila font sumber tidak ditemukan. Baca-tulis String.

**Mengembalikan:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public abstract void setDefaultAsianFont(String value)
```

Mengembalikan atau mengatur font Asian yang digunakan bila font sumber tidak ditemukan. Baca-tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public abstract String getPassword()
```

Mengambil atau mengatur kata sandi. Baca-tulis String.

Nilai: Kata sandi.

**Mengembalikan:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public abstract void setPassword(String value)
```

Mengambil atau mengatur kata sandi. Baca-tulis String.

Nilai: Kata sandi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public abstract boolean getOnlyLoadDocumentProperties()
```

Properti ini relevan jika file presentasi dilindungi kata sandi. Nilai true berarti hanya properti dokumen yang harus dimuat dari file presentasi yang terenkripsi dan kata sandi diabaikan. Nilai false berarti seluruh presentasi yang terenkripsi harus dimuat dengan menggunakan kata sandi yang tepat. Jika presentasi tidak terenkripsi maka nilai properti selalu diabaikan. Jika properti dokumen dari file terenkripsi tidak publik dan nilai properti true maka properti dokumen tidak dapat dimuat dan pengecualian akan dilempar. Baca-tulis boolean.

**Mengembalikan:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public abstract void setOnlyLoadDocumentProperties(boolean value)
```

Properti ini relevan jika file presentasi dilindungi kata sandi. Nilai true berarti hanya properti dokumen yang harus dimuat dari file presentasi yang terenkripsi dan kata sandi diabaikan. Nilai false berarti seluruh presentasi yang terenkripsi harus dimuat dengan menggunakan kata sandi yang tepat. Jika presentasi tidak terenkripsi maka nilai properti selalu diabaikan. Jika properti dokumen dari file terenkripsi tidak publik dan nilai properti true maka properti dokumen tidak dapat dimuat dan pengecualian akan dilempar. Baca-tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public abstract IWarningCallback getWarningCallback()
```

Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Baca/tulis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Mengembalikan:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public abstract void setWarningCallback(IWarningCallback value)
```

Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Baca/tulis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public abstract IBlobManagementOptions getBlobManagementOptions()
```

Mewakili opsi yang dapat digunakan untuk mengelola perilaku penanganan Binary Large Objects (BLOB), seperti penggunaan file sementara atau batas byte BLOB dalam memori. Opsi-opsi ini dimaksudkan untuk mengatur rasio kinerja/konsumsi memori terbaik untuk lingkungan atau persyaratan tertentu.

--------------------

Binary Large Object (BLOB) adalah data biner yang disimpan sebagai entitas tunggal – misalnya BLOB dapat berupa audio, video, atau presentasi itu sendiri.

**Mengembalikan:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public abstract void setBlobManagementOptions(IBlobManagementOptions value)
```

Mewakili opsi yang dapat digunakan untuk mengelola perilaku penanganan Binary Large Objects (BLOB), seperti penggunaan file sementara atau batas byte BLOB dalam memori. Opsi-opsi ini dimaksudkan untuk mengatur rasio kinerja/konsumsi memori terbaik untuk lingkungan atau persyaratan tertentu.

--------------------

Binary Large Object (BLOB) adalah data biner yang disimpan sebagai entitas tunggal – misalnya BLOB dapat berupa audio, video, atau presentasi itu sendiri.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public abstract IFontSources getDocumentLevelFontSources()
```

Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi. Font-font ini tersedia untuk presentasi selama masa hidupnya dan tidak dibagikan dengan presentasi lain.

**Mengembalikan:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public abstract void setDocumentLevelFontSources(IFontSources value)
```

Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi. Font-font ini tersedia untuk presentasi selama masa hidupnya dan tidak dibagikan dengan presentasi lain.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public abstract IInterruptionToken getInterruptionToken()
```

Token untuk memantau permintaan interupsi.

--------------------

Token ini mengelola seluruh siklus hidup instance [IPresentation](../../com.aspose.slides/ipresentation). Setiap operasi yang memakan waktu lama, seperti pemuatan atau penyimpanan presentasi, akan diinterupsi melalui pemanggilan metode [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) dari [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Mengembalikan:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public abstract void setInterruptionToken(IInterruptionToken value)
```

Token untuk memantau permintaan interupsi.

--------------------

Token ini mengelola seluruh siklus hidup instance [IPresentation](../../com.aspose.slides/ipresentation). Setiap operasi yang memakan waktu lama, seperti pemuatan atau penyimpanan presentasi, akan diinterupsi melalui pemanggilan metode [IInterruptionTokenSource.interrupt](../../com.aspose.slides/iinterruptiontokensource\#interrupt) dari [IInterruptionTokenSource](../../com.aspose.slides/iinterruptiontokensource).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public abstract IResourceLoadingCallback getResourceLoadingCallback()
```

Mengembalikan atau mengatur antarmuka callback yang mengelola pemuatan sumber daya eksternal. Baca/tulis [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Mengembalikan:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public abstract void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Mengembalikan atau mengatur antarmuka callback yang mengelola pemuatan sumber daya eksternal. Baca/tulis [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public abstract ISpreadsheetOptions getSpreadsheetOptions()
```

Mewakili opsi yang dapat digunakan untuk menentukan perilaku lembar kerja tambahan.

**Mengembalikan:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public abstract void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Mewakili opsi yang dapat digunakan untuk menentukan perilaku lembar kerja tambahan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public abstract String getDefaultTextLanguage()
```

Mengembalikan atau mengatur bahasa default untuk teks presentasi. Baca/tulis String.

--------------------

> ```
> Example:
>   
>  // Gunakan opsi muat untuk menentukan budaya teks default
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Tambahkan bentuk persegi panjang baru dengan teks
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Periksa bahasa bagian pertama
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
java.lang.String

### setDefaultTextLanguage(String value) {#setDefaultTextLanguage-java.lang.String-}
```
public abstract void setDefaultTextLanguage(String value)
```

Mengembalikan atau mengatur bahasa default untuk teks presentasi. Baca/tulis String.

--------------------

> ```
> Example:
>   
>  // Gunakan opsi muat untuk menentukan budaya teks default
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDefaultTextLanguage("en-US");
>  Presentation pres = new Presentation(loadOptions);
>  try {
>      // Tambahkan bentuk persegi panjang baru dengan teks
>      IAutoShape shp = pres.getSlides().get_Item(0).getShapes().addAutoShape(ShapeType.Rectangle, 50, 50, 150, 50);
>      shp.getTextFrame().setText("New Text");
>      // Periksa bahasa bagian pertama
>      System.out.println(shp.getTextFrame().getParagraphs().get_Item(0).getPortions().get_Item(0).getPortionFormat().getLanguageId());
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getDeleteEmbeddedBinaryObjects() {#getDeleteEmbeddedBinaryObjects--}
```
public abstract boolean getDeleteEmbeddedBinaryObjects()
```

Menentukan apakah Aspose.Slides akan menghapus semua objek biner tersemat saat pemuatan presentasi.

Jenis-jenis objek biner tersemat:

 *  
 *  
 *  

Baca-tulis boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Default adalah **false**.

**Mengembalikan:**
boolean

### setDeleteEmbeddedBinaryObjects(boolean value) {#setDeleteEmbeddedBinaryObjects-boolean-}
```
public abstract void setDeleteEmbeddedBinaryObjects(boolean value)
```

Menentukan apakah Aspose.Slides akan menghapus semua objek biner tersemat saat pemuatan presentasi.

Jenis-jenis objek biner tersemat:

 *  
 *  
 *  

Baca-tulis boolean.

--------------------

> ```
> The following example shows how to load the presentation without any embedded binary objects.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setDeleteEmbeddedBinaryObjects(true);
>  Presentation pres = new Presentation("pres.ppt", loadOptions);
>  try {
>      pres.save("output_WithoutBinaryObjects.ppt", SaveFormat.Ppt);
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

--------------------

Default adalah **false**.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |