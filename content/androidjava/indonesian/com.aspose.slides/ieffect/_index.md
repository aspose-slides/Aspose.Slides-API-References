---
title: IEffect
second_title: Aspose.Slides for Android via Java API Reference
description: Represents animation effect.
type: docs
url: /id/com.aspose.slides/ieffect/
---```
public interface IEffect
```

Mewakili efek animasi.
## Metode

| Metode | Deskripsi |
| --- | --- |
| [getSequence()](#getSequence--) | Mengembalikan urutan untuk sebuah efek. |
| [getTextAnimation()](#getTextAnimation--) | Mengembalikan animasi teks. |
| [getPresetClassType()](#getPresetClassType--) | Mendefinisikan kelas efek. |
| [setPresetClassType(int value)](#setPresetClassType-int-) | Mendefinisikan kelas efek. |
| [getType()](#getType--) | Mendefinisikan tipe efek. |
| [setType(int value)](#setType-int-) | Mendefinisikan tipe efek. |
| [getSubtype()](#getSubtype--) | Mendefinisikan subtipe efek. |
| [setSubtype(int value)](#setSubtype-int-) | Mendefinisikan subtipe efek. |
| [getBehaviors()](#getBehaviors--) | Mengembalikan koleksi perilaku untuk efek. |
| [setBehaviors(IBehaviorCollection value)](#setBehaviors-com.aspose.slides.IBehaviorCollection-) | Mengembalikan koleksi perilaku untuk efek. |
| [getTiming()](#getTiming--) | Mendefinisikan nilai penundaan untuk efek. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Mendefinisikan nilai penundaan untuk efek. |
| [getTargetShape()](#getTargetShape--) | Mengembalikan bentuk target untuk efek. |
| [getSound()](#getSound--) | Mendefinisikan suara tersemat untuk efek. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | Mendefinisikan suara tersemat untuk efek. |
| [getStopPreviousSound()](#getStopPreviousSound--) | Atribut ini menentukan apakah efek animasi menghentikan suara sebelumnya. |
| [setStopPreviousSound(boolean value)](#setStopPreviousSound-boolean-) | Atribut ini menentukan apakah efek animasi menghentikan suara sebelumnya. |
| [getAfterAnimationType()](#getAfterAnimationType--) | Mendefinisikan tipe animasi setelah efek. |
| [setAfterAnimationType(int value)](#setAfterAnimationType-int-) | Mendefinisikan tipe animasi setelah efek. |
| [getAfterAnimationColor()](#getAfterAnimationColor--) | Mendefinisikan warna animasi setelah efek. |
| [setAfterAnimationColor(IColorFormat value)](#setAfterAnimationColor-com.aspose.slides.IColorFormat-) | Mendefinisikan warna animasi setelah efek. |
| [getAnimateTextType()](#getAnimateTextType--) | Mendefinisikan tipe teks animasi untuk efek. |
| [setAnimateTextType(int value)](#setAnimateTextType-int-) | Mendefinisikan tipe teks animasi untuk efek. |
| [getDelayBetweenTextParts()](#getDelayBetweenTextParts--) | Mendefinisikan jeda antara bagian teks yang dianimasikan (kata atau huruf). |
| [setDelayBetweenTextParts(float value)](#setDelayBetweenTextParts-float-) | Mendefinisikan jeda antara bagian teks yang dianimasikan (kata atau huruf). |
### getSequence() {#getSequence--}
```
public abstract ISequence getSequence()
```


Mengembalikan urutan untuk sebuah efek. Baca-saja [ISequence](../../com.aspose.slides/isequence).

**Mengembalikan:**
[ISequence](../../com.aspose.slides/isequence)
### getTextAnimation() {#getTextAnimation--}
```
public abstract ITextAnimation getTextAnimation()
```


Mengembalikan animasi teks. Baca-saja [ITextAnimation](../../com.aspose.slides/itextanimation).

**Mengembalikan:**
[ITextAnimation](../../com.aspose.slides/itextanimation)
### getPresetClassType() {#getPresetClassType--}
```
public abstract int getPresetClassType()
```


Mendefinisikan kelas efek. Baca/tulis [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Mengembalikan:**
int
### setPresetClassType(int value) {#setPresetClassType-int-}
```
public abstract void setPresetClassType(int value)
```


Mendefinisikan kelas efek. Baca/tulis [EffectPresetClassType](../../com.aspose.slides/effectpresetclasstype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getType() {#getType--}
```
public abstract int getType()
```


Mendefinisikan tipe efek. Baca/tulis [EffectType](../../com.aspose.slides/effecttype).

**Mengembalikan:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```


Mendefinisikan tipe efek. Baca/tulis [EffectType](../../com.aspose.slides/effecttype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getSubtype() {#getSubtype--}
```
public abstract int getSubtype()
```


Mendefinisikan subtipe efek. Baca/tulis [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Mengembalikan:**
int
### setSubtype(int value) {#setSubtype-int-}
```
public abstract void setSubtype(int value)
```


Mendefinisikan subtipe efek. Baca/tulis [EffectSubtype](../../com.aspose.slides/effectsubtype).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getBehaviors() {#getBehaviors--}
```
public abstract IBehaviorCollection getBehaviors()
```


Mengembalikan koleksi perilaku untuk efek. Baca/tulis [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Mengembalikan:**
[IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection)
### setBehaviors(IBehaviorCollection value) {#setBehaviors-com.aspose.slides.IBehaviorCollection-}
```
public abstract void setBehaviors(IBehaviorCollection value)
```


Mengembalikan koleksi perilaku untuk efek. Baca/tulis [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IBehaviorCollection](../../com.aspose.slides/ibehaviorcollection) |  |
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```


Mendefinisikan nilai penundaan untuk efek. Baca/tulis [ITiming](../../com.aspose.slides/itiming).

**Mengembalikan:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```


Mendefinisikan nilai penundaan untuk efek. Baca/tulis [ITiming](../../com.aspose.slides/itiming).

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |
### getTargetShape() {#getTargetShape--}
```
public abstract IShape getTargetShape()
```


Mengembalikan bentuk target untuk efek. Baca-saja [IShape](../../com.aspose.slides/ishape).

**Mengembalikan:**
[IShape](../../com.aspose.slides/ishape)
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```


Mendefinisikan suara tersemat untuk efek. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Mendapatkan urutan efek untuk slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Mengekstrak suara efek dalam array byte
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```


Mendefinisikan suara tersemat untuk efek. Baca/tulis [IAudio](../../com.aspose.slides/iaudio).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      ISlide slide = presentation.getSlides().get_Item(0);
> 
>      // Mendapatkan urutan efek untuk slide
>      ISequence effectsSequence = slide.getTimeline().getMainSequence();
> 
>      for (IEffect effect : effectsSequence)
>      {
>          if (effect.getSound() == null)
>              continue;
> 
>          // Mengekstrak suara efek dalam array byte
>          byte[] audio = effect.getSound().getBinaryData();
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getStopPreviousSound() {#getStopPreviousSound--}
```
public abstract boolean getStopPreviousSound()
```


Atribut ini menentukan apakah efek animasi menghentikan suara sebelumnya. Baca/tulis boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Dapatkan efek pertama dari slide pertama.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Dapatkan efek pertama dari slide kedua.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Ubah Enhancements/Sound pada efek kedua menjadi "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
boolean
### setStopPreviousSound(boolean value) {#setStopPreviousSound-boolean-}
```
public abstract void setStopPreviousSound(boolean value)
```


Atribut ini menentukan apakah efek animasi menghentikan suara sebelumnya. Baca/tulis boolean .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Dapatkan efek pertama dari slide pertama.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Dapatkan efek pertama dari slide kedua.
>      IEffect secondSlideEffect = presentation.getSlides().get_Item(1).getTimeline().getMainSequence().get_Item(0);
> 
>      if (firstSlideEffect.getSound() != null)
>      {
>          // Ubah Enhancements/Sound pada efek kedua menjadi "Stop Previous Sound"
>          secondSlideEffect.setStopPreviousSound(true);
>      }
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | boolean |  |
### getAfterAnimationType() {#getAfterAnimationType--}
```
public abstract int getAfterAnimationType()
```


Mendefinisikan tipe animasi setelah efek. Baca/tulis AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Dapatkan efek pertama dari slide pertama.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ubah animasi setelah efek menjadi "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
int
### setAfterAnimationType(int value) {#setAfterAnimationType-int-}
```
public abstract void setAfterAnimationType(int value)
```


Mendefinisikan tipe animasi setelah efek. Baca/tulis AfterAnimationType (\#getAfterAnimationType.getAfterAnimationType/\#setAfterAnimationType(int).setAfterAnimationType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Dapatkan efek pertama dari slide pertama.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ubah animasi setelah efek menjadi "Hide on Next Mouse Click"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.HideOnNextMouseClick);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getAfterAnimationColor() {#getAfterAnimationColor--}
```
public abstract IColorFormat getAfterAnimationColor()
```


Mendefinisikan warna animasi setelah efek. Baca/tulis [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Dapatkan efek pertama dari slide pertama.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ubah tipe animasi setelah efek menjadi "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Tetapkan warna animasi setelah efek.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
[IColorFormat](../../com.aspose.slides/icolorformat)
### setAfterAnimationColor(IColorFormat value) {#setAfterAnimationColor-com.aspose.slides.IColorFormat-}
```
public abstract void setAfterAnimationColor(IColorFormat value)
```


Mendefinisikan warna animasi setelah efek. Baca/tulis [IColorFormat](../../com.aspose.slides/icolorformat).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>      // Dapatkan efek pertama dari slide pertama.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ubah tipe animasi setelah efek menjadi "Color"
>      firstSlideEffect.setAfterAnimationType(AfterAnimationType.Color);
> 
>      // Tetapkan warna animasi setelah efek.
>      firstSlideEffect.getAfterAnimationColor().setColor(Color.BLUE);
>  }finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | [IColorFormat](../../com.aspose.slides/icolorformat) |  |
### getAnimateTextType() {#getAnimateTextType--}
```
public abstract int getAnimateTextType()
```


Mendefinisikan tipe teks animasi untuk efek. Teks shape dapat dianimasikan per huruf, per kata, atau sekaligus. Baca/tulis AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Dapatkan efek pertama dari slide pertama.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ubah tipe animasi teks efek menjadi "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
int
### setAnimateTextType(int value) {#setAnimateTextType-int-}
```
public abstract void setAnimateTextType(int value)
```


Mendefinisikan tipe teks animasi untuk efek. Teks shape dapat dianimasikan per huruf, per kata, atau sekaligus. Baca/tulis AnimateTextType (\#getAnimateTextType.getAnimateTextType/\#setAnimateTextType(int).setAnimateTextType(int)).

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Dapatkan efek pertama dari slide pertama.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ubah tipe animasi teks efek menjadi "By letter"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByLetter);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | int |  |
### getDelayBetweenTextParts() {#getDelayBetweenTextParts--}
```
public abstract float getDelayBetweenTextParts()
```


Mendefinisikan jeda antara bagian teks yang dianimasikan (kata atau huruf). Nilai positif menentukan persentase durasi efek. Nilai negatif menentukan jeda dalam detik. Baca/tulis float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Dapatkan efek pertama dari slide pertama.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ubah tipe animasi teks efek menjadi "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Atur jeda antara bagian teks yang dianimasikan menjadi 20% dari durasi efek.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Mengembalikan:**
float
### setDelayBetweenTextParts(float value) {#setDelayBetweenTextParts-float-}
```
public abstract void setDelayBetweenTextParts(float value)
```


Mendefinisikan jeda antara bagian teks yang dianimasikan (kata atau huruf). Nilai positif menentukan persentase durasi efek. Nilai negatif menentukan jeda dalam detik. Baca/tulis float .

--------------------

> ```
> Presentation presentation = new Presentation("demo.pptx");
>  try {
>     // Dapatkan efek pertama dari slide pertama.
>      IEffect firstSlideEffect = presentation.getSlides().get_Item(0).getTimeline().getMainSequence().get_Item(0);
> 
>      // Ubah tipe animasi teks efek menjadi "By word"
>      firstSlideEffect.setAnimateTextType(AnimateTextType.ByWord);
> 
>      // Atur jeda antara bagian teks yang dianimasikan menjadi 20% dari durasi efek.
>      firstSlideEffect.setDelayBetweenTextParts(20f);
>  } finally {
>      if (presentation != null) presentation.dispose();
>  }
> ```

**Parameter:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| value | float |  |