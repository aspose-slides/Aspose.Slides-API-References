---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Represents slide show transition.
type: docs
url: /id/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

Mewakili transisi pertunjukan slide.
## Metode

| Method | Description |
| --- | --- |
| [getSound()](#getSound--) | Mengembalikan atau mengatur data audio yang disematkan. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Mengembalikan atau mengatur data audio yang disematkan. |
| [getSoundMode()](#getSoundMode--) | Mengatur atau mengembalikan mode suara untuk transisi slide. |
| [setSoundMode(int value)](#setSoundMode-int-) | Mengatur atau mengembalikan mode suara untuk transisi slide. |
| [getSoundLoop()](#getSoundLoop--) | Atribut ini menentukan apakah suara akan berulang hingga peristiwa suara berikutnya terjadi dalam pertunjukan slide. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | Atribut ini menentukan apakah suara akan berulang hingga peristiwa suara berikutnya terjadi dalam pertunjukan slide. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | Menentukan apakah klik mouse akan melanjutkan slide atau tidak. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | Menentukan apakah klik mouse akan melanjutkan slide atau tidak. |
| [getAdvanceAfter()](#getAdvanceAfter--) | Atribut ini menentukan apakah pertunjukan slide akan berpindah ke slide berikutnya setelah waktu tertentu. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | Atribut ini menentukan apakah pertunjukan slide akan berpindah ke slide berikutnya setelah waktu tertentu. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | Menentukan waktu, dalam milidetik, setelah itu transisi harus dimulai. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | Menentukan waktu, dalam milidetik, setelah itu transisi harus dimulai. |
| [getSpeed()](#getSpeed--) | Menentukan kecepatan transisi yang akan digunakan saat beralih dari slide saat ini ke slide berikutnya. |
| [setSpeed(int value)](#setSpeed-int-) | Menentukan kecepatan transisi yang akan digunakan saat beralih dari slide saat ini ke slide berikutnya. |
| [getValue()](#getValue--) | Nilai transisi pertunjukan slide. |
| [getType()](#getType--) | Jenis transisi. |
| [setType(int value)](#setType-int-) | Jenis transisi. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | Menentukan apakah suara ini merupakan suara bawaan atau tidak. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | Menentukan apakah suara ini merupakan suara bawaan atau tidak. |
| [getSoundName()](#getSoundName--) | Menentukan nama yang dapat dibaca manusia untuk suara transisi. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | Menentukan nama yang dapat dibaca manusia untuk suara transisi. |
| [getDuration()](#getDuration--) | Mendapatkan atau mengatur durasi efek transisi slide dalam milidetik. |
| [setDuration(int value)](#setDuration-int-) | Mendapatkan atau mengatur durasi efek transisi slide dalam milidetik. |

### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

Mengembalikan atau mengatur data audio yang disematkan. Baca-tulis [IAudio](../../com.aspose.slides/iaudio).

**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio)

### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

Mengembalikan atau mengatur data audio yang disematkan. Baca-tulis [IAudio](../../com.aspose.slides/iaudio).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |

### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

Mengatur atau mengembalikan mode suara untuk transisi slide. Baca-tulis [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Mengembalikan:**
int

### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

Mengatur atau mengembalikan mode suara untuk transisi slide. Baca-tulis [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

Atribut ini menentukan apakah suara akan berulang hingga peristiwa suara berikutnya terjadi dalam pertunjukan slide. Baca-tulis boolean.

**Mengembalikan:**
boolean

### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

Atribut ini menentukan apakah suara akan berulang hingga peristiwa suara berikutnya terjadi dalam pertunjukan slide. Baca-tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

Menentukan apakah klik mouse akan melanjutkan slide atau tidak. Jika atribut ini tidak ditentukan maka nilai true diasumsikan. Baca-tulis boolean.

**Mengembalikan:**
boolean

### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

Menentukan apakah klik mouse akan melanjutkan slide atau tidak. Jika atribut ini tidak ditentukan maka nilai true diasumsikan. Baca-tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

Atribut ini menentukan apakah pertunjukan slide akan berpindah ke slide berikutnya setelah waktu tertentu. Baca/tulis boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Dapatkan transisi slide pertama
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Periksa apakah flag Advance Slide After dicentang
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Dapatkan nilai waktu Advance Slide After
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
public abstract void setAdvanceAfter(boolean value)
```

Atribut ini menentukan apakah pertunjukan slide akan berpindah ke slide berikutnya setelah waktu tertentu. Baca/tulis boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // Dapatkan transisi slide pertama
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // Periksa apakah flag Advance Slide After dicentang
>      if (slideTransition.getAdvanceAfter())
>      {
>          // Dapatkan nilai waktu Advance Slide After
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
public abstract long getAdvanceAfterTime()
```

Menentukan waktu, dalam milidetik, setelah itu transisi harus dimulai. Pengaturan ini dapat digunakan bersama dengan atribut advClick. Jika atribut ini tidak ditentukan maka diasumsikan tidak ada perpindahan otomatis. Baca-tulis long.

**Mengembalikan:**
long

### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

Menentukan waktu, dalam milidetik, setelah itu transisi harus dimulai. Pengaturan ini dapat digunakan bersama dengan atribut advClick. Jika atribut ini tidak ditentukan maka diasumsikan tidak ada perpindahan otomatis. Baca-tulis long.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | long |  |

### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

Menentukan kecepatan transisi yang akan digunakan saat beralih dari slide saat ini ke slide berikutnya. Baca-tulis [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Mengembalikan:**
int

### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

Menentukan kecepatan transisi yang akan digunakan saat beralih dari slide saat ini ke slide berikutnya. Baca-tulis [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

Nilai transisi pertunjukan slide. Baca-saja [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**Mengembalikan:**
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)

### getType() {#getType--}
```
public abstract int getType()
```

Jenis transisi. Baca-tulis [TransitionType](../../com.aspose.slides/transitiontype).

**Mengembalikan:**
int

### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

Jenis transisi. Baca-tulis [TransitionType](../../com.aspose.slides/transitiontype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |

### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

Menentukan apakah suara ini merupakan suara bawaan atau tidak. Jika atribut ini diset ke true maka aplikasi pembuat akan diberitahu untuk memeriksa atribut nama yang ditentukan untuk suara ini dalam daftar suara bawaan dan kemudian dapat menampilkan nama khusus atau UI sesuai kebutuhan. Baca-tulis boolean.

**Mengembalikan:**
boolean

### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

Menentukan apakah suara ini merupakan suara bawaan atau tidak. Jika atribut ini diset ke true maka aplikasi pembuat akan diberitahu untuk memeriksa atribut nama yang ditentukan untuk suara ini dalam daftar suara bawaan dan kemudian dapat menampilkan nama khusus atau UI sesuai kebutuhan. Baca-tulis boolean.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |

### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

Menentukan nama yang dapat dibaca manusia untuk suara transisi. Properti (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) harus ditetapkan untuk mendapatkan atau mengatur nama suara. Baca-tulis String.

**Mengembalikan:**
java.lang.String

### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

Menentukan nama yang dapat dibaca manusia untuk suara transisi. Properti \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) harus ditetapkan untuk mendapatkan atau mengatur nama suara. Baca-tulis String.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | java.lang.String |  |

### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

Mendapatkan atau mengatur durasi efek transisi slide dalam milidetik. Baca/tulis int.

--------------------

Berkaitan dengan atribut p14:dur dari elemen p:transition dalam skema PresentationML. Jika tidak disetel, durasi ditentukan secara otomatis berdasarkan properti \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) dan jenis transisi.

**Mengembalikan:**
int

### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

Mendapatkan atau mengatur durasi efek transisi slide dalam milidetik. Baca/tulis int.

--------------------

Berkaitan dengan atribut p14:dur dari elemen p:transition dalam skema PresentationML. Jika tidak disetel, durasi ditentukan secara otomatis berdasarkan properti \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) dan jenis transisi.

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |