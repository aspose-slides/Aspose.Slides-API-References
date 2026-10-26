---
title: LoadOptions
second_title: Referensi API Java Aspose.Slides untuk Android
description: Memungkinkan untuk menentukan opsi tambahan seperti format atau font default saat memuat presentasi.
type: docs
url: /id/com.aspose.slides/loadoptions/
---
**Warisan:**
java.lang.Object

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ILoadOptions](../../com.aspose.slides/iloadoptions)
```
public class LoadOptions implements ILoadOptions
```

Memungkinkan untuk menentukan opsi tambahan (seperti format atau font default) saat memuat presentasi.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [LoadOptions()](#LoadOptions--) | Membuat opsi muat default baru. |
| [LoadOptions(int loadFormat)](#LoadOptions-int-) | Membuat opsi muat baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLoadFormat()](#getLoadFormat--) | Mengembalikan atau mengatur format presentasi yang akan dimuat. |
| [setLoadFormat(int value)](#setLoadFormat-int-) | Mengembalikan atau mengatur format presentasi yang akan dimuat. |
| [getDefaultRegularFont()](#getDefaultRegularFont--) | Mengembalikan atau mengatur font Reguler yang digunakan bila font sumber tidak ditemukan. |
| [setDefaultRegularFont(String value)](#setDefaultRegularFont-java.lang.String-) | Mengembalikan atau mengatur font Reguler yang digunakan bila font sumber tidak ditemukan. |
| [getDefaultSymbolFont()](#getDefaultSymbolFont--) | Mengembalikan atau mengatur font Simbol yang digunakan bila font sumber tidak ditemukan. |
| [setDefaultSymbolFont(String value)](#setDefaultSymbolFont-java.lang.String-) | Mengembalikan atau mengatur font Simbol yang digunakan bila font sumber tidak ditemukan. |
| [getDefaultAsianFont()](#getDefaultAsianFont--) | Mengembalikan atau mengatur font Asia yang digunakan bila font sumber tidak ditemukan. |
| [setDefaultAsianFont(String value)](#setDefaultAsianFont-java.lang.String-) | Mengembalikan atau mengatur font Asia yang digunakan bila font sumber tidak ditemukan. |
| [getPassword()](#getPassword--) | Mengambil atau mengatur kata sandi. |
| [setPassword(String value)](#setPassword-java.lang.String-) | Mengambil atau mengatur kata sandi. |
| [getOnlyLoadDocumentProperties()](#getOnlyLoadDocumentProperties--) | Properti ini masuk akal jika berkas presentasi dilindungi kata sandi. |
| [setOnlyLoadDocumentProperties(boolean value)](#setOnlyLoadDocumentProperties-boolean-) | Properti ini masuk akal jika berkas presentasi dilindungi kata sandi. |
| [getWarningCallback()](#getWarningCallback--) | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. |
| [setWarningCallback(IWarningCallback value)](#setWarningCallback-com.aspose.slides.IWarningCallback-) | Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. |
| [getBlobManagementOptions()](#getBlobManagementOptions--) | Mewakili opsi yang dapat digunakan untuk mengelola perilaku penanganan Binary Large Objects (BLOBs), seperti penggunaan file sementara atau maksimum byte BLOBs di memori. |
| [setBlobManagementOptions(IBlobManagementOptions value)](#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-) | Mewakili opsi yang dapat digunakan untuk mengelola perilaku penanganan Binary Large Objects (BLOBs), seperti penggunaan file sementara atau maksimum byte BLOBs di memori. |
| [getDocumentLevelFontSources()](#getDocumentLevelFontSources--) | Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi. |
| [setDocumentLevelFontSources(IFontSources value)](#setDocumentLevelFontSources-com.aspose.slides.IFontSources-) | Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi. |
| [getInterruptionToken()](#getInterruptionToken--) | Token untuk memantau permintaan interupsi. |
| [setInterruptionToken(IInterruptionToken value)](#setInterruptionToken-com.aspose.slides.IInterruptionToken-) | Token untuk memantau permintaan interupsi. |
| [getResourceLoadingCallback()](#getResourceLoadingCallback--) | Mengembalikan atau mengatur antarmuka callback yang mengelola pemuatan sumber daya eksternal. |
| [setResourceLoadingCallback(IResourceLoadingCallback value)](#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-) | Mengembalikan atau mengatur antarmuka callback yang mengelola pemuatan sumber daya eksternal. |
| [getSpreadsheetOptions()](#getSpreadsheetOptions--) | Mengambil opsi untuk spreadsheet. |
| [setSpreadsheetOptions(ISpreadsheetOptions value)](#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-) | Mengambil opsi untuk spreadsheet. |
| [getDefaultTextLanguage()](#getDefaultTextLanguage--) | Mengembalikan atau mengatur bahasa default untuk teks presentasi. |
| [setDefaultTextLanguage(String value)](#setDefaultTextLanguage-java.lang.String-) | Mengembalikan atau mengatur bahasa default untuk teks presentasi. |
| [getDeleteEmbeddedBinaryObjects()](#getDeleteEmbeddedBinaryObjects--) | Menentukan apakah Aspose.Slides akan menghapus semua objek biner yang disematkan saat memuat presentasi. |
| [setDeleteEmbeddedBinaryObjects(boolean value)](#setDeleteEmbeddedBinaryObjects-boolean-) | Menentukan apakah Aspose.Slides akan menghapus semua objek biner yang disematkan saat memuat presentasi. |

### LoadOptions() {#LoadOptions--}
```
public LoadOptions()
```

Membuat opsi muat default baru.

### LoadOptions(int loadFormat) {#LoadOptions-int-}
```
public LoadOptions(int loadFormat)
```

Membuat opsi muat baru.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| loadFormat | int | Format presentasi yang akan dimuat. |

### getLoadFormat() {#getLoadFormat--}
```
public final int getLoadFormat()
```

Mengembalikan atau mengatur format presentasi yang akan dimuat. Baca/tulis [LoadFormat](../../com.aspose.slides/loadformat).

**Mengembalikan:**
int

### setLoadFormat(int value) {#setLoadFormat-int-}
```
public final void setLoadFormat(int value)
```

Mengembalikan atau mengatur format presentasi yang akan dimuat. Baca/tulis [LoadFormat](../../com.aspose.slides/loadformat).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getDefaultRegularFont() {#getDefaultRegularFont--}
```
public final String getDefaultRegularFont()
```

Mengembalikan atau mengatur font Reguler yang digunakan bila font sumber tidak ditemukan. Baca/tulis String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Mengembalikan:**
java.lang.String

### setDefaultRegularFont(String value) {#setDefaultRegularFont-java.lang.String-}
```
public final void setDefaultRegularFont(String value)
```

Mengembalikan atau mengatur font Reguler yang digunakan bila font sumber tidak ditemukan. Baca/tulis String.

--------------------

> ```
> The following example shows how to set default fonts for rendering PowerPoint Presentation.
>  
>  // Use load options to define the default regular and asian fonts
>  LoadOptions loadOptions = new LoadOptions(LoadFormat.Auto);
>  loadOptions.setDefaultRegularFont("Wingdings");
>  loadOptions.setDefaultAsianFont("Wingdings");
>  // Load the presentation
>  Presentation pres = new Presentation("DefaultFonts.pptx", loadOptions);
>  try {
>      // Generate slide thumbnail
>      android.graphics.Bitmap slideImage = pres.getSlides().get_Item(0).getThumbnail(1, 1);
>      FileOutputStream fos = null;
>      try {
>          fos = new FileOutputStream("output_out.png");
>          slideImage.compress(android.graphics.Bitmap.CompressFormat.PNG, 100, fos);
>      } catch (IOException e) {
>          throw new RuntimeException(e);
>      } finally {
>          if (fos != null) {
>              try {
>                  fos.close();
>              } catch (IOException e) {
>                  e.printStackTrace();
>              }
>          }
>      }
>      // Generate PDF
>      pres.save("output_out.pdf", SaveFormat.Pdf);
>      // Generate XPS
>      pres.save("output_out.xps", SaveFormat.Xps);
>  } catch(IOException e) {
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultSymbolFont() {#getDefaultSymbolFont--}
```
public final String getDefaultSymbolFont()
```

Mengembalikan atau mengatur font Simbol yang digunakan bila font sumber tidak ditemukan. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setDefaultSymbolFont(String value) {#setDefaultSymbolFont-java.lang.String-}
```
public final void setDefaultSymbolFont(String value)
```

Mengembalikan atau mengatur font Simbol yang digunakan bila font sumber tidak ditemukan. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getDefaultAsianFont() {#getDefaultAsianFont--}
```
public final String getDefaultAsianFont()
```

Mengembalikan atau mengatur font Asia yang digunakan bila font sumber tidak ditemukan. Baca/tulis String.

**Mengembalikan:**
java.lang.String

### setDefaultAsianFont(String value) {#setDefaultAsianFont-java.lang.String-}
```
public final void setDefaultAsianFont(String value)
```

Mengembalikan atau mengatur font Asia yang digunakan bila font sumber tidak ditemukan. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getPassword() {#getPassword--}
```
public final String getPassword()
```

Mengambil atau mengatur kata sandi. Baca/tulis String.

--------------------

> ```
> The following sample code shows how to open password protected PowerPoint Presentation.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // kerja dengan presentasi yang didekripsi
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Nilai: Kata sandi.

**Mengembalikan:**
java.lang.String

### setPassword(String value) {#setPassword-java.lang.String-}
```
public final void setPassword(String value)
```

Mengambil atau mengatur kata sandi. Baca/tulis String.

--------------------

> ```
> Contoh kode berikut menunjukkan cara membuka PowerPoint Presentation yang dilindungi kata sandi.
>  
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.setPassword("YOUR_PASSWORD");
>  Presentation pres = new Presentation("pres.pptx", loadOptions);
>  try {
>  // kerja dengan presentasi yang didekripsi
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


Nilai: Kata sandi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getOnlyLoadDocumentProperties() {#getOnlyLoadDocumentProperties--}
```
public final boolean getOnlyLoadDocumentProperties()
```

Properti ini masuk akal jika berkas presentasi dilindungi kata sandi. Nilai true berarti hanya properti dokumen yang harus dimuat dari berkas presentasi yang terenkripsi dan kata sandi diabaikan. Nilai false berarti seluruh presentasi yang terenkripsi harus dimuat dengan menggunakan kata sandi yang benar. Jika presentasi tidak terenkripsi maka nilai properti selalu diabaikan. Jika properti dokumen dari berkas terenkripsi tidak bersifat publik dan nilai properti true maka properti dokumen tidak dapat dimuat dan pengecualian akan dilempar. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setOnlyLoadDocumentProperties(boolean value) {#setOnlyLoadDocumentProperties-boolean-}
```
public final void setOnlyLoadDocumentProperties(boolean value)
```

Properti ini masuk akal jika berkas presentasi dilindungi kata sandi. Nilai true berarti hanya properti dokumen yang harus dimuat dari berkas presentasi yang terenkripsi dan kata sandi diabaikan. Nilai false berarti seluruh presentasi yang terenkripsi harus dimuat dengan menggunakan kata sandi yang benar. Jika presentasi tidak terenkripsi maka nilai properti selalu diabaikan. Jika properti dokumen dari berkas terenkripsi tidak bersifat publik dan nilai properti true maka properti dokumen tidak dapat dimuat dan pengecualian akan dilempar. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getWarningCallback() {#getWarningCallback--}
```
public final IWarningCallback getWarningCallback()
```

Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Baca/tulis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Mengembalikan:**
[IWarningCallback](../../com.aspose.slides/iwarningcallback)

### setWarningCallback(IWarningCallback value) {#setWarningCallback-com.aspose.slides.IWarningCallback-}
```
public final void setWarningCallback(IWarningCallback value)
```

Mengembalikan atau mengatur objek yang menerima peringatan dan memutuskan apakah proses pemuatan akan dilanjutkan atau dibatalkan. Baca/tulis [IWarningCallback](../../com.aspose.slides/iwarningcallback).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IWarningCallback](../../com.aspose.slides/iwarningcallback) |  |

### getBlobManagementOptions() {#getBlobManagementOptions--}
```
public final IBlobManagementOptions getBlobManagementOptions()
```

Mewakili opsi yang dapat digunakan untuk mengelola perilaku penanganan Binary Large Objects (BLOBs), seperti penggunaan file sementara atau maksimum byte BLOBs di memori. Opsi-opsi ini dimaksudkan untuk menyiapkan rasio kinerja/ konsumsi memori terbaik untuk lingkungan atau kebutuhan tertentu.

--------------------

Binary Large Object (BLOB) adalah data biner yang disimpan sebagai satu entitas – yaitu BLOB dapat berupa audio, video, atau presentasi itu sendiri.

**Mengembalikan:**
[IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions)

### setBlobManagementOptions(IBlobManagementOptions value) {#setBlobManagementOptions-com.aspose.slides.IBlobManagementOptions-}
```
public final void setBlobManagementOptions(IBlobManagementOptions value)
```

Mewakili opsi yang dapat digunakan untuk mengelola perilaku penanganan Binary Large Objects (BLOBs), seperti penggunaan file sementara atau maksimum byte BLOBs di memori. Opsi-opsi ini dimaksudkan untuk menyiapkan rasio kinerja/ konsumsi memori terbaik untuk lingkungan atau kebutuhan tertentu.

--------------------

Binary Large Object (BLOB) adalah data biner yang disimpan sebagai satu entitas – yaitu BLOB dapat berupa audio, video, atau presentasi itu sendiri.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IBlobManagementOptions](../../com.aspose.slides/iblobmanagementoptions) |  |

### getDocumentLevelFontSources() {#getDocumentLevelFontSources--}
```
public final IFontSources getDocumentLevelFontSources()
```

Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi. Font ini tersedia untuk presentasi selama masa hidupnya dan tidak dibagikan dengan presentasi lain.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //work with the presentation
>  //CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
[IFontSources](../../com.aspose.slides/ifontsources)

### setDocumentLevelFontSources(IFontSources value) {#setDocumentLevelFontSources-com.aspose.slides.IFontSources-}
```
public final void setDocumentLevelFontSources(IFontSources value)
```

Menentukan sumber untuk font eksternal yang akan digunakan oleh presentasi. Font ini tersedia untuk presentasi selama masa hidupnya dan tidak dibagikan dengan presentasi lain.

--------------------

> ```
> The following example shows how to specify custom fonts used with PowerPoint Presentation.
>  
>  File file = new File("customfonts/CustomFont1.ttf");
>  byte memoryFont1[] = new byte[(int) file.length()];
>  BufferedInputStream bis = new BufferedInputStream(new FileInputStream(file));
>  DataInputStream dis = new DataInputStream(bis);
>  dis.readFully(memoryFont1);
>  file = new File("customfonts/CustomFont2.ttf");
>  byte memoryFont2[] = new byte[(int) file.length()];
>  bis = new BufferedInputStream(new FileInputStream(file));
>  dis = new DataInputStream(bis);
>  dis.readFully(memoryFont2);
>  LoadOptions loadOptions = new LoadOptions();
>  loadOptions.getDocumentLevelFontSources().setFontFolders(new String[] { "assets\\fonts", "global\\fonts" });
>  loadOptions.getDocumentLevelFontSources().setMemoryFonts(new byte[][] { memoryFont1, memoryFont2 });
>  IPresentation presentation = new Presentation("MyPresentation.pptx", loadOptions);
>  try {
>  //work with the presentation
>  //CustomFont1, CustomFont2 as well as fonts from assets\fonts & global\fonts folders and their subfolders are available to the presentation
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IFontSources](../../com.aspose.slides/ifontsources) |  |

### getInterruptionToken() {#getInterruptionToken--}
```
public final IInterruptionToken getInterruptionToken()
```

Token untuk memantau permintaan interupsi.

--------------------

Token ini mengelola seluruh masa hidup instance [IPresentation](../../com.aspose.slides/ipresentation). Operasi yang memakan waktu lama, seperti memuat atau menyimpan presentasi, akan terinterupsi melalui pemanggilan metode [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) pada [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Mengembalikan:**
[IInterruptionToken](../../com.aspose.slides/iinterruptiontoken)

### setInterruptionToken(IInterruptionToken value) {#setInterruptionToken-com.aspose.slides.IInterruptionToken-}
```
public final void setInterruptionToken(IInterruptionToken value)
```

Token untuk memantau permintaan interupsi.

--------------------

Token ini mengelola seluruh masa hidup instance [IPresentation](../../com.aspose.slides/ipresentation). Operasi yang memakan waktu lama, seperti memuat atau menyimpan presentasi, akan terinterupsi melalui pemanggilan metode [InterruptionTokenSource.interrupt](../../com.aspose.slides/interruptiontokensource\#interrupt) pada [InterruptionTokenSource](../../com.aspose.slides/interruptiontokensource).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IInterruptionToken](../../com.aspose.slides/iinterruptiontoken) |  |

### getResourceLoadingCallback() {#getResourceLoadingCallback--}
```
public final IResourceLoadingCallback getResourceLoadingCallback()
```

Mengembalikan atau mengatur antarmuka callback yang mengelola pemuatan sumber daya eksternal. Baca/tulis [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Mengembalikan:**
[IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback)

### setResourceLoadingCallback(IResourceLoadingCallback value) {#setResourceLoadingCallback-com.aspose.slides.IResourceLoadingCallback-}
```
public final void setResourceLoadingCallback(IResourceLoadingCallback value)
```

Mengembalikan atau mengatur antarmuka callback yang mengelola pemuatan sumber daya eksternal. Baca/tulis [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IResourceLoadingCallback](../../com.aspose.slides/iresourceloadingcallback) |  |

### getSpreadsheetOptions() {#getSpreadsheetOptions--}
```
public final ISpreadsheetOptions getSpreadsheetOptions()
```

Mengambil opsi untuk spreadsheet. Misalnya, opsi-opsi ini memengaruhi perhitungan rumus untuk diagram.

**Mengembalikan:**
[ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions)

### setSpreadsheetOptions(ISpreadsheetOptions value) {#setSpreadsheetOptions-com.aspose.slides.ISpreadsheetOptions-}
```
public final void setSpreadsheetOptions(ISpreadsheetOptions value)
```

Mengambil opsi untuk spreadsheet. Misalnya, opsi-opsi ini memengaruhi perhitungan rumus untuk diagram.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ISpreadsheetOptions](../../com.aspose.slides/ispreadsheetoptions) |  |

### getDefaultTextLanguage() {#getDefaultTextLanguage--}
```
public final String getDefaultTextLanguage()
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
public final void setDefaultTextLanguage(String value)
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
public final boolean getDeleteEmbeddedBinaryObjects()
```

Menentukan apakah Aspose.Slides akan menghapus semua objek biner yang disematkan saat memuat presentasi.

Jenis-jenis objek biner yang disematkan:

Baca/tulis boolean.

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
public final void setDeleteEmbeddedBinaryObjects(boolean value)
```

Menentukan apakah Aspose.Slides akan menghapus semua objek biner yang disematkan saat memuat presentasi.

Jenis-jenis objek biner yang disematkan:

Baca/tulis boolean.

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