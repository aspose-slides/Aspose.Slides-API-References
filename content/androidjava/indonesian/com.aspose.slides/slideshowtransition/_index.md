---
title: SlideShowTransition
second_title: Referensi API Java Aspose.Slides untuk Android
description: Mewakili transisi pertunjukan slide.
type: docs
url: /id/com.aspose.slides/slideshowtransition/
---
**Warisan:**
java.lang.Object, com.aspose.slides.DomObject

**Semua Antarmuka yang Diimplementasikan:**
[com.aspose.slides.ISlideShowTransition](../../com.aspose.slides/islideshowtransition)
```
public class SlideShowTransition extends DomObject<BaseSlide> implements ISlideShowTransition
```

Mewakili transisi pertunjukan slide.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSound()](#getSound--) | Mengembalikan atau mengatur data audio yang disematkan. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Mengembalikan atau mengatur data audio yang disematkan. |
| [getSoundMode()](#getSoundMode--) | Mengatur atau mengembalikan mode suara untuk transisi slide. |
| [setSoundMode(int value)](#setSoundMode-int-) | Mengatur atau mengembalikan mode suara untuk transisi slide. |
| [getSoundLoop()](#getSoundLoop--) | Atribut ini menentukan apakah suara akan berulang sampai peristiwa suara berikutnya terjadi dalam pertunjukan slide. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Atribut ini menentukan apakah suara akan berulang sampai peristiwa suara berikutnya terjadi dalam pertunjukan slide. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Menentukan apakah klik mouse akan melanjutkan slide atau tidak. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Menentukan apakah klik mouse akan melanjutkan slide atau tidak. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Atribut ini menentukan apakah pertunjukan slide akan berpindah ke slide berikutnya setelah waktu tertentu. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Atribut ini menentukan apakah pertunjukan slide akan berpindah ke slide berikutnya setelah waktu tertentu. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Menentukan waktu, dalam milidetik, setelah itu transisi harus dimulai. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Menentukan waktu, dalam milidetik, setelah itu transisi harus dimulai. |
| [getSpeed()](#getSpeed--) | Menentukan kecepatan transisi yang akan digunakan saat berpindah dari slide saat ini ke slide berikutnya. |
| [setSpeed(int value)](#setSpeed-int-) | Menentukan kecepatan transisi yang akan digunakan saat berpindah dari slide saat ini ke slide berikutnya. |
| [getValue()](#getValue--) | Nilai transisi pertunjukan slide. |
| [getType()](#getType--) | Jenis transisi. |
| [setType(int value)](#setType-int-) | Jenis transisi. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Menentukan apakah suara ini adalah suara bawaan atau tidak. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Menentukan apakah suara ini adalah suara bawaan atau tidak. |
| [getSoundName()](#getSoundName--) | Menentukan nama yang dapat dibaca manusia untuk suara transisi. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Menentukan nama yang dapat dibaca manusia untuk suara transisi. |
| [getDuration()](#getDuration--) | Mendapatkan atau mengatur durasi efek transisi slide dalam milidetik. |
| [setDuration(int value)](#setDuration-int-) | Mendapatkan atau mengatur durasi efek transisi slide dalam milidetik. |
| [equals(Object obj)](#equals-java.lang.Object-) | Menentukan apakah dua instance SlideShowTransition sama. |
| [hashCode()](#hashCode--) | Berfungsi sebagai fungsi hash untuk tipe tertentu, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash. |

### getSound() {#getSound--}
```
public final IAudio getSound()
```

Mengembalikan atau mengatur data audio yang disematkan. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public final void setSound(IAudio value)
```

Mengembalikan atau mengatur data audio yang disematkan. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public final int getSoundMode()
```

Mengatur atau mengembalikan mode suara untuk transisi slide. Baca/tulis [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Mengembalikan:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public final void setSoundMode(int value)
```

Mengatur atau mengembalikan mode suara untuk transisi slide. Baca/tulis [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public final boolean getSoundLoop()
```

Atribut ini menentukan apakah suara akan berulang sampai peristiwa suara berikutnya terjadi dalam pertunjukan slide. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public final void setSoundLoop(boolean value)
```

Atribut ini menentukan apakah suara akan berulang sampai peristiwa suara berikutnya terjadi dalam pertunjukan slide. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public final boolean getAdvanceOnClick()
```

Menentukan apakah klik mouse akan melanjutkan slide atau tidak. Jika atribut ini tidak ditentukan maka nilai true diasumsikan. Baca/tulis boolean.

**Mengembalikan:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public final void setAdvanceOnClick(boolean value)
```

Menentukan apakah klik mouse akan melanjutkan slide atau tidak. Jika atribut ini tidak ditentukan maka nilai true diasumsikan. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public final boolean getAdvanceAfter()
```

Atribut ini menentukan apakah pertunjukan slide akan berpindah ke slide berikutnya setelah waktu tertentu. Baca/tulis boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Dapatkan transisi slide pertama
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Periksa apakah flag Advance Slide After diaktifkan
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Dapatkan nilai Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**Mengembalikan:**
boolean

### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public final void setAdvanceAfter(boolean value)
```

Atribut ini menentukan apakah pertunjukan slide akan berpindah ke slide berikutnya setelah waktu tertentu. Baca/tulis boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Dapatkan transisi slide pertama
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Periksa apakah flag Advance Slide After diaktifkan
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Dapatkan nilai Advance Slide After Time
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public final long getAdvanceAfterTime()
```

Menentukan waktu, dalam milidetik, setelah itu transisi harus dimulai. Pengaturan ini dapat digunakan bersamaan dengan atribut advClick. Jika atribut ini tidak ditentukan maka diasumsikan tidak ada auto-lanjutan yang terjadi. Baca/tulis long.

**Mengembalikan:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public final void setAdvanceAfterTime(long value)
```

Menentukan waktu, dalam milidetik, setelah itu transisi harus dimulai. Pengaturan ini dapat digunakan bersamaan dengan atribut advClick. Jika atribut ini tidak ditentukan maka diasumsikan tidak ada auto-lanjutan yang terjadi. Baca/tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public final int getSpeed()
```

Menentukan kecepatan transisi yang akan digunakan saat berpindah dari slide saat ini ke slide berikutnya. Baca/tulis [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Mengembalikan:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public final void setSpeed(int value)
```

Menentukan kecepatan transisi yang akan digunakan saat berpindah dari slide saat ini ke slide berikutnya. Baca/tulis [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public final ITransitionValueBase getValue()
```

Nilai transisi pertunjukan slide. Baca-saja [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Mengembalikan:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public final int getType()
```

Jenis transisi. Baca/tulis [TransitionType](../../com.aspose.slides/transitiontype).

**Mengembalikan:**
int

### setType(int value) {#setType-int-}
```
public final void setType(int value)
```

Jenis transisi. Baca/tulis [TransitionType](../../com.aspose.slides/transitiontype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public final boolean getSoundIsBuiltIn()
```

Menentukan apakah suara ini adalah suara bawaan atau tidak. Jika atribut ini diatur ke true maka aplikasi pembuat akan diperingatkan untuk memeriksa atribut name yang ditentukan untuk suara ini dalam daftar suara bawaan dan kemudian dapat menampilkan nama khusus atau UI sesuai kebutuhan. Baca-tulis boolean.

**Mengembalikan:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public final void setSoundIsBuiltIn(boolean value)
```

Menentukan apakah suara ini adalah suara bawaan atau tidak. Jika atribut ini diatur ke true maka aplikasi pembuat akan diperingatkan untuk memeriksa atribut name yang ditentukan untuk suara ini dalam daftar suara bawaan dan kemudian dapat menampilkan nama khusus atau UI sesuai kebutuhan. Baca-tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public final String getSoundName()
```

Menentukan nama yang dapat dibaca manusia untuk suara transisi. Properti Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) harus ditetapkan untuk mendapatkan atau mengatur nama suara. Baca-tulis String.

**Mengembalikan:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public final void setSoundName(String value)
```

Menentukan nama yang dapat dibaca manusia untuk suara transisi. Properti Sound (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) harus ditetapkan untuk mendapatkan atau mengatur nama suara. Baca-tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public final int getDuration()
```

Mendapatkan atau mengatur durasi efek transisi slide dalam milidetik. Baca/tulis int.

Berkorespondensi dengan atribut p14:dur pada elemen p:transition dalam skema PresentationML. Jika tidak diatur, durasi ditentukan secara otomatis berdasarkan properti \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) dan jenis transisi.

**Mengembalikan:**
int

### setDuration(int value) {#setDuration-int-}
```
public final void setDuration(int value)
```

Mendapatkan atau mengatur durasi efek transisi slide dalam milidetik. Baca/tulis int.

Berkorespondensi dengan atribut p14:dur pada elemen p:transition dalam skema PresentationML. Jika tidak diatur, durasi ditentukan secara otomatis berdasarkan properti \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) dan jenis transisi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```

Menentukan apakah dua instance SlideShowTransition sama. Baca/tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| obj | java.lang.Object | SlideShowTransition yang dibandingkan dengan SlideShowTransition saat ini. |

**Mengembalikan:**
boolean - **true** jika SlideShowTransition yang ditentukan sama dengan SlideShowTransition saat ini; sebaliknya, **false**.

### hashCode() {#hashCode--}
```
public int hashCode()
```

Berfungsi sebagai fungsi hash untuk tipe tertentu, cocok untuk digunakan dalam algoritma hashing dan struktur data seperti tabel hash.

**Mengembalikan:**
int - 23454

Ditimpa untuk membuat compiler senang. Selalu mengembalikan nilai konstan karena objek bersifat mutable.