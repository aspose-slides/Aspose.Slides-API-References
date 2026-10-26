---
title: Hyperlink
second_title: Referensi API Aspose.Slides untuk Java
description: Mewakili sebuah hyperlink.
type: docs
url: /id/com.aspose.slides/hyperlink/
---
**Pewarisan:**
java.lang.Object, [com.aspose.slides.PVIObject](../../com.aspose.slides/pviobject)

**Semua Interface yang Diimplementasikan:**
[com.aspose.slides.IHyperlink](../../com.aspose.slides/ihyperlink), com.aspose.slides.IDOMObject
```
public final class Hyperlink extends PVIObject implements IHyperlink, IDOMObject
```

Mewakili sebuah hyperlink.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [Hyperlink(String url)](#Hyperlink-java.lang.String-) | Creates an instance of a hyperlink. |
| [Hyperlink(ISlide slide)](#Hyperlink-com.aspose.slides.ISlide-) | Creates an instance of a hyperlink which points to specific slide. |
| [Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)](#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-) | Creates an instance of a hyperlink using another hyperlink as source, overriding secondary properties. |
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getVersion()](#getVersion--) |  |
| [getNoAction()](#getNoAction--) | Mengembalikan sebuah hyperlink khusus “do nothing”. |
| [getMedia()](#getMedia--) | Mengembalikan sebuah hyperlink khusus “play mediafile”. |
| [getNextSlide()](#getNextSlide--) | Mengembalikan hyperlink ke slide berikutnya. |
| [getPreviousSlide()](#getPreviousSlide--) | Mengembalikan hyperlink ke slide sebelumnya. |
| [getFirstSlide()](#getFirstSlide--) | Mengembalikan hyperlink ke slide pertama presentasi. |
| [getLastSlide()](#getLastSlide--) | Mengembalikan hyperlink ke slide terakhir presentasi. |
| [getLastVievedSlide()](#getLastVievedSlide--) | Mengembalikan hyperlink ke slide terakhir yang dilihat. |
| [getEndShow()](#getEndShow--) | Mengembalikan hyperlink yang mengakhiri pertunjukan. |
| [getActionType()](#getActionType--) | Mengembalikan tipe aksi Hyperlink. |
| [getExternalUrl()](#getExternalUrl--) | Menentukan URL eksternal. |
| [getTargetSlide()](#getTargetSlide--) | Jika Hyperlink menargetkan slide tertentu, mengembalikan slide tersebut. |
| [getExternalUrlOriginal()](#getExternalUrlOriginal--) | Mewakili sebuah hyperlink yang diatur untuk bagian ini tanpa memperhatikan konten sebenarnya. |
| [getTargetFrame()](#getTargetFrame--) | Mengembalikan frame dalam frameset HTML induk untuk target hyperlink induk bila ada. |
| [setTargetFrame(String value)](#setTargetFrame-java.lang.String-) | Mengembalikan frame dalam frameset HTML induk untuk target hyperlink induk bila ada. |
| [getTooltip()](#getTooltip--) | Mengembalikan string yang mungkin ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink induk. |
| [setTooltip(String value)](#setTooltip-java.lang.String-) | Mengembalikan string yang mungkin ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink induk. |
| [getHistory()](#getHistory--) | Menentukan apakah target hyperlink induk harus ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. |
| [setHistory(boolean value)](#setHistory-boolean-) | Menentukan apakah target hyperlink induk harus ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. |
| [getHighlightClick()](#getHighlightClick--) | Menentukan apakah hyperlink harus disorot saat diklik. |
| [setHighlightClick(boolean value)](#setHighlightClick-boolean-) | Menentukan apakah hyperlink harus disorot saat diklik. |
| [getStopSoundOnClick()](#getStopSoundOnClick--) | Menentukan apakah suara harus dihentikan saat hyperlink diklik. |
| [setStopSoundOnClick(boolean value)](#setStopSoundOnClick-boolean-) | Menentukan apakah suara harus dihentikan saat hyperlink diklik. |
| [getSound()](#getSound--) | Mewakili suara yang diputar pada hyperlink. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Mewakili suara yang diputar pada hyperlink. |
| [getColorSource()](#getColorSource--) | Mewakili sumber warna hyperlink — baik style maupun format bagian. |
| [setColorSource(int value)](#setColorSource-int-) | Mewakili sumber warna hyperlink — baik style maupun format bagian. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah dua instance Hyperlink sama. |
| [equals(IHyperlink hlink)](#equals-com.aspose.slides.IHyperlink-) | Menentukan apakah dua instance Hyperlink sama. |
| [op_Equality(Hyperlink hlink1, Hyperlink hlink2)](#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Menguji dua hyperlink untuk kesamaan. |
| [op_Inequality(Hyperlink hlink1, Hyperlink hlink2)](#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-) | Menguji dua hyperlink untuk ketidaksamaan. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu, cocok digunakan dalam algoritma hashing dan struktur data seperti tabel hash. |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### Hyperlink(String url) {#Hyperlink-java.lang.String-}
```
public Hyperlink(String url)
```

Membuat sebuah instance hyperlink.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| url | java.lang.String | URL Hyperlink. |

### Hyperlink(ISlide slide) {#Hyperlink-com.aspose.slides.ISlide-}
```
public Hyperlink(ISlide slide)
```

Membuat sebuah instance hyperlink yang mengarah ke slide tertentu. Catatan: hyperlink yang dibuat harus ditetapkan ke objek dalam presentasi yang sama, jika tidak tautan akan disimpan sebagai NoAction.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| slide | [ISlide](../../com.aspose.slides/islide) | Slide target. |

### Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick) {#Hyperlink-com.aspose.slides.Hyperlink-java.lang.String-java.lang.String-boolean-boolean-boolean-}
```
public Hyperlink(Hyperlink source, String targetFrame, String tooltip, boolean history, boolean stopSoundsOnClick, boolean highlightClick)
```

Membuat sebuah instance hyperlink menggunakan hyperlink lain sebagai sumber, menggantikan properti sekunder.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| source | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlink sumber |
| targetFrame | java.lang.String | Frame target |
| tooltip | java.lang.String | Teks tooltip |
| history | boolean | Menentukan apakah target hyperlink induk harus ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. |
| stopSoundsOnClick | boolean | Menentukan apakah suara harus dihentikan ketika hyperlink diklik. |
| highlightClick | boolean | Menentukan apakah hyperlink harus disorot saat diklik. |

### getVersion() {#getVersion--}
```
public long getVersion()
```

Versi. Baca-saja long.

**Mengembalikan:**
long
### getNoAction() {#getNoAction--}
```
public static Hyperlink getNoAction()
```

Mengembalikan sebuah hyperlink khusus “do nothing”. Baca-saja [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getMedia() {#getMedia--}
```
public static Hyperlink getMedia()
```

Mengembalikan sebuah hyperlink khusus “play mediafile”. Digunakan di AudioFrame dan VideoFrame. Baca-saja [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getNextSlide() {#getNextSlide--}
```
public static Hyperlink getNextSlide()
```

Mengembalikan hyperlink ke slide berikutnya. Baca-saja [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getPreviousSlide() {#getPreviousSlide--}
```
public static Hyperlink getPreviousSlide()
```

Mengembalikan hyperlink ke slide sebelumnya. Baca-saja [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getFirstSlide() {#getFirstSlide--}
```
public static Hyperlink getFirstSlide()
```

Mengembalikan hyperlink ke slide pertama presentasi. Baca-saja [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastSlide() {#getLastSlide--}
```
public static Hyperlink getLastSlide()
```

Mengembalikan hyperlink ke slide terakhir presentasi. Baca-saja [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getLastVievedSlide() {#getLastVievedSlide--}
```
public static Hyperlink getLastVievedSlide()
```

Mengembalikan hyperlink ke slide terakhir yang dilihat. Baca-saja [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getEndShow() {#getEndShow--}
```
public static Hyperlink getEndShow()
```

Mengembalikan hyperlink yang mengakhiri pertunjukan. Baca-saja [Hyperlink](../../com.aspose.slides/hyperlink).

**Mengembalikan:**
[Hyperlink](../../com.aspose.slides/hyperlink)
### getActionType() {#getActionType--}
```
public final int getActionType()
```

Mengembalikan tipe aksi Hyperlink. Baca-saja [HyperlinkActionType](../../com.aspose.slides/hyperlinkactiontype).

**Mengembalikan:**
int
### getExternalUrl() {#getExternalUrl--}
```
public final String getExternalUrl()
```

Menentukan URL eksternal. Baca-saja String.

**Mengembalikan:**
java.lang.String
### getTargetSlide() {#getTargetSlide--}
```
public final ISlide getTargetSlide()
```

Jika Hyperlink menargetkan slide tertentu, mengembalikan slide tersebut. Baca-saja [ISlide](../../com.aspose.slides/islide).

**Mengembalikan:**
[ISlide](../../com.aspose.slides/islide)
### getExternalUrlOriginal() {#getExternalUrlOriginal--}
```
public final String getExternalUrlOriginal()
```

Mewakili sebuah hyperlink yang diatur untuk bagian ini tanpa memperhatikan konten sebenarnya.

--------------------

PowerPoint memiliki perilaku khusus untuk tautan dan teks yang bersesuaian dalam suatu bagian. Ia memperbolehkan pembuatan teks untuk hyperlink dalam bentuk URL yang valid, berbeda dari alamat nyata tautan. Dalam kasus ini, ketika Anda melihat tautan di jendela penyuntingan, teksnya akan diubah agar cocok dengan bagian teks. Properti ini mewakili nilai asli hyperlink.

**Mengembalikan:**
java.lang.String
### getTargetFrame() {#getTargetFrame--}
```
public final String getTargetFrame()
```

Mengembalikan frame dalam frameset HTML induk untuk target hyperlink induk bila ada. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setTargetFrame(String value) {#setTargetFrame-java.lang.String-}
```
public final void setTargetFrame(String value)
```

Mengembalikan frame dalam frameset HTML induk untuk target hyperlink induk bila ada. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getTooltip() {#getTooltip--}
```
public final String getTooltip()
```

Mengembalikan string yang mungkin ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink induk. Baca/tulis String.

**Mengembalikan:**
java.lang.String
### setTooltip(String value) {#setTooltip-java.lang.String-}
```
public final void setTooltip(String value)
```

Mengembalikan string yang mungkin ditampilkan dalam antarmuka pengguna yang terkait dengan hyperlink induk. Baca/tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getHistory() {#getHistory--}
```
public final boolean getHistory()
```

Menentukan apakah target hyperlink induk harus ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setHistory(boolean value) {#setHistory-boolean-}
```
public final void setHistory(boolean value)
```

Menentukan apakah target hyperlink induk harus ditambahkan ke daftar hyperlink yang telah dilihat ketika dipanggil. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getHighlightClick() {#getHighlightClick--}
```
public final boolean getHighlightClick()
```

Menentukan apakah hyperlink harus disorot saat diklik. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setHighlightClick(boolean value) {#setHighlightClick-boolean-}
```
public final void setHighlightClick(boolean value)
```

Menentukan apakah hyperlink harus disorot saat diklik. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getStopSoundOnClick() {#getStopSoundOnClick--}
```
public final boolean getStopSoundOnClick()
```

Menentukan apakah suara harus dihentikan saat hyperlink diklik. Baca/tulis boolean.

**Mengembalikan:**
boolean
### setStopSoundOnClick(boolean value) {#setStopSoundOnClick-boolean-}
```
public final void setStopSoundOnClick(boolean value)
```

Menentukan apakah suara harus dihentikan saat hyperlink diklik. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Mewakili suara yang diputar pada hyperlink. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Dapatkan hyperlink shape pertama
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Ekstrak suara hyperlink dalam array byte
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Mewakili suara yang diputar pada hyperlink. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Dapatkan hyperlink shape pertama
>      IHyperlink link = presentation.getSlides().get_Item(0).getShapes().get_Item(0).getHyperlinkClick();
> 
>      if (link.getSound() != null)
>      {
>          // Ekstrak suara hyperlink dalam array byte
>          byte[] audioData = link.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```


**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getColorSource() {#getColorSource--}
```
public final int getColorSource()
```

Mewakili sumber warna hyperlink — baik style maupun format bagian. Baca/tulis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Mengembalikan:**
int
### setColorSource(int value) {#setColorSource-int-}
```
public final void setColorSource(int value)
```

Mewakili sumber warna hyperlink — baik style maupun format bagian. Baca/tulis [HyperlinkColorSource](../../com.aspose.slides/hyperlinkcolorsource).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah dua instance Hyperlink sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | Hyperlink yang dibandingkan dengan Hyperlink saat ini. |

**Mengembalikan:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### equals(IHyperlink hlink) {#equals-com.aspose.slides.IHyperlink-}
```
public final boolean equals(IHyperlink hlink)
```

Menentukan apakah dua instance Hyperlink sama.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hlink | [IHyperlink](../../com.aspose.slides/ihyperlink) | Hyperlink yang dibandingkan dengan Hyperlink saat ini. |

**Mengembalikan:**
boolean - **true** if the specified Hyperlink is equal to the current Hyperlink; otherwise, **false**.
### op_Equality(Hyperlink hlink1, Hyperlink hlink2) {#op-Equality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Equality(Hyperlink hlink1, Hyperlink hlink2)
```

Menguji dua hyperlink untuk kesamaan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlink pertama yang diuji. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlink kedua yang diuji. |

**Mengembalikan:**
boolean - **true** if hyperlinks are equal.
### op_Inequality(Hyperlink hlink1, Hyperlink hlink2) {#op-Inequality-com.aspose.slides.Hyperlink-com.aspose.slides.Hyperlink-}
```
public static boolean op_Inequality(Hyperlink hlink1, Hyperlink hlink2)
```

Menguji dua hyperlink untuk ketidaksamaan.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| hlink1 | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlink pertama yang diuji. |
| hlink2 | [Hyperlink](../../com.aspose.slides/hyperlink) | Hyperlink kedua yang diuji. |

**Mengembalikan:**
boolean - **false** if hyperlinks are equal.
### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu, cocok digunakan dalam algoritma hashing dan struktur data seperti tabel hash.

**Mengembalikan:**
int - Hash code for an URL.
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

Mengembalikan objek Parent_Immediate. Baca-saja IDOMObject.

**Mengembalikan:**
com.aspose.slides.IDOMObject