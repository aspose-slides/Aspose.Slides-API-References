---
title: ISlideShowTransition
second_title: Aspose.Slides for Android via Java API Reference
description: Represents slide show transition.
type: docs
url: /fa/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

نمایانگر انتقال نمایش اسلاید را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getSound()](#getSound--) | داده‌های صوتی توکار را باز می‌گرداند یا تنظیم می‌کند. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | داده‌های صوتی توکار را باز می‌گرداند یا تنظیم می‌کند. |
| [getSoundMode()](#getSoundMode--) | حالت صدا را برای انتقال اسلاید تنظیم یا بازمی‌گرداند. |
| [setSoundMode(int value)](#setSoundMode-int-) | حالت صدا را برای انتقال اسلاید تنظیم یا بازمی‌گرداند. |
| [getSoundLoop()](#getSoundLoop--) | این ویژگی مشخص می‌کند که صدا تا وقوع رویداد صوتی بعدی در نمایش اسلاید چرخه بزند. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | این ویژگی مشخص می‌کند که صدا تا وقوع رویداد صوتی بعدی در نمایش اسلاید چرخه بزند. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | مشخص می‌کند آیا کلیک ماوس اسلاید را پیش می‌برد یا خیر. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | مشخص می‌کند آیا کلیک ماوس اسلاید را پیش می‌برد یا خیر. |
| [getAdvanceAfter()](#getAdvanceAfter--) | این ویژگی مشخص می‌کند که پس از مدت زمان معین، نمایش اسلاید به اسلاید بعدی منتقل شود. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | این ویژگی مشخص می‌کند که پس از مدت زمان معین، نمایش اسلاید به اسلاید بعدی منتقل شود. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | زمان، بر حسب میلی‌ثانیه، که پس از آن انتقال باید شروع شود را مشخص می‌کند. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | زمان، بر حسب میلی‌ثانیه، که پس از آن انتقال باید شروع شود را مشخص می‌کند. |
| [getSpeed()](#getSpeed--) | سرعت انتقال که هنگام رفتن از اسلاید کنونی به اسلاید بعدی استفاده می‌شود را مشخص می‌کند. |
| [setSpeed(int value)](#setSpeed-int-) | سرعت انتقال که هنگام رفتن از اسلاید کنونی به اسلاید بعدی استفاده می‌شود را مشخص می‌کند. |
| [getValue()](#getValue--) | مقدار انتقال نمایش اسلاید. |
| [getType()](#getType--) | نوع انتقال. |
| [setType(int value)](#setType-int-) | نوع انتقال. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | مشخص می‌کند آیا این صدا یک صدا داخلی است یا خیر. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | مشخص می‌کند آیا این صدا یک صدا داخلی است یا خیر. |
| [getSoundName()](#getSoundName--) | نام قابل خواندن انسانی برای صدای انتقال را مشخص می‌کند. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | نام قابل خواندن انسانی برای صدای انتقال را مشخص می‌کند. |
| [getDuration()](#getDuration--) | مدت زمان اثر انتقال اسلاید را بر حسب میلی‌ثانیه دریافت یا تنظیم می‌کند. |
| [setDuration(int value)](#setDuration-int-) | مدت زمان اثر انتقال اسلاید را بر حسب میلی‌ثانیه دریافت یا تنظیم می‌کند. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

داده‌های صوتی توکار را باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی [IAudio](../../com.aspose.slides/iaudio).

**بازگشت:**  
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

داده‌های صوتی توکار را باز می‌گرداند یا تنظیم می‌کند. خواندنی-نوشتنی [IAudio](../../com.aspose.slides/iaudio).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

حالت صدا را برای انتقال اسلاید تنظیم یا بازمی‌گرداند. خواندنی-نوشتنی [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**بازگشت:**  
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

حالت صدا را برای انتقال اسلاید تنظیم یا بازمی‌گرداند. خواندنی-نوشتنی [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

این ویژگی مشخص می‌کند که صدا تا وقوع رویداد صوتی بعدی در نمایش اسلاید چرخه بزند. خواندنی-نوشتنی boolean.

**بازگشت:**  
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

این ویژگی مشخص می‌کند که صدا تا وقوع رویداد صوتی بعدی در نمایش اسلاید چرخه بزند. خواندنی-نوشتنی boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

مشخص می‌کند آیا کلیک ماوس اسلاید را پیش می‌برد یا خیر. اگر این ویژگی مشخص نشده باشد، مقدار true در نظر گرفته می‌شود. خواندنی-نوشتنی boolean.

**بازگشت:**  
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

مشخص می‌کند آیا کلیک ماوس اسلاید را پیش می‌برد یا خیر. اگر این ویژگی مشخص نشده باشد، مقدار true در نظر گرفته می‌شود. خواندنی-نوشتنی boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

این ویژگی مشخص می‌کند که پس از مدت زمان معین، نمایش اسلاید به اسلاید بعدی منتقل شود. خواندنی/نوشتنی boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین انتقال اسلاید
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // بررسی فعال بودن پرچم پیشروی اسلاید پس از
>      if (slideTransition.getAdvanceAfter())
>      {
>          // دریافت مقدار زمان پیشروی اسلاید پس از
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**بازگشت:**  
boolean
### setAdvanceAfter(boolean value) {#setAdvanceAfter-boolean-}
```
public abstract void setAdvanceAfter(boolean value)
```

این ویژگی مشخص می‌کند که پس از مدت زمان معین، نمایش اسلاید به اسلاید بعدی منتقل شود. خواندنی/نوشتنی boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین انتقال اسلاید
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // بررسی اینکه پرچم پیشروی اسلاید پس از فعال است یا نه
>      if (slideTransition.getAdvanceAfter())
>      {
>          // دریافت مقدار زمان پیشروی اسلاید پس از
>          long advanceAfterTime = slideTransition.getAdvanceAfterTime();
>      }
>  } finally {
>      if (pres != null) pres.dispose();
>  }
> ```


**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfterTime() {#getAdvanceAfterTime--}
```
public abstract long getAdvanceAfterTime()
```

زمان، بر حسب میلی‌ثانیه، که پس از آن انتقال باید شروع شود را مشخص می‌کند. این تنظیم می‌تواند همراه با ویژگی advClick استفاده شود. اگر این ویژگی مشخص نشده باشد، فرض می‌شود که خودکار پیشروی رخ ندهد. خواندنی-نوشتنی long.

**بازگشت:**  
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

زمان، بر حسب میلی‌ثانیه، که پس از آن انتقال باید شروع شود را مشخص می‌کند. این تنظیم می‌تواند همراه با ویژگی advClick استفاده شود. اگر این ویژگی مشخص نشده باشد، فرض می‌شود که خودکار پیشروی رخ ندهد. خواندنی-نوشتنی long.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

سرعت انتقال که هنگام رفتن از اسلاید کنونی به اسلاید بعدی استفاده می‌شود را مشخص می‌کند. خواندنی-نوشتنی [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**بازگشت:**  
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

سرعت انتقال که هنگام رفتن از اسلاید کنونی به اسلاید بعدی استفاده می‌شود را مشخص می‌کند. خواندنی-نوشتنی [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getValue() {#getValue--}
```
public abstract ITransitionValueBase getValue()
```

مقدار انتقال نمایش اسلاید. فقط-خواندنی [ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase).

**بازگشت:**  
[ITransitionValueBase](../../com.aspose.slides/itransitionvaluebase)
### getType() {#getType--}
```
public abstract int getType()
```

نوع انتقال. خواندنی-نوشتنی [TransitionType](../../com.aspose.slides/transitiontype).

**بازگشت:**  
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

نوع انتقال. خواندنی-نوشتنی [TransitionType](../../com.aspose.slides/transitiontype).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

مشخص می‌کند آیا این صدا یک صدا داخلی است یا خیر. اگر این ویژگی به true تنظیم شود، برنامه تولیدکننده برای بررسی نام صدا در فهرست صداهای داخلی هشدار می‌دهد و می‌تواند نام یا رابط کاربری سفارشی را ارائه دهد. خواندنی-نوشتنی boolean.

**بازگشت:**  
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

مشخص می‌کند آیا این صدا یک صدا داخلی است یا خیر. اگر این ویژگی به true تنظیم شود، برنامه تولیدکننده برای بررسی نام صدا در فهرست صداهای داخلی هشدار می‌دهد و می‌تواند نام یا رابط کاربری سفارشی را ارائه دهد. خواندنی-نوشتنی boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

نام قابل خواندن انسانی برای صدای انتقال را مشخص می‌کند. ویژگی (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) باید برای دریافت یا تنظیم نام صدا اختصاص داده شود. خواندنی-نوشتنی String.

**بازگشت:**  
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

نام قابل خواندن انسانی برای صدای انتقال را مشخص می‌کند. ویژگی \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) باید برای دریافت یا تنظیم نام صدا اختصاص داده شود. خواندنی-نوشتنی String.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

مدت زمان اثر انتقال اسلاید را بر حسب میلی‌ثانیه دریافت یا تنظیم می‌کند. خواندنی/نوشتنی int.

--------------------

مطابق با ویژگی p14:dur در عنصر p:transition در طرح‌القاعده PresentationML. اگر تنظیم نشود، مدت زمان به‌صورت خودکار بر پایه ویژگی \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) و نوع انتقال محاسبه می‌شود.

**بازگشت:**  
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

مدت زمان اثر انتقال اسلاید را بر حسب میلی‌ثانیه دریافت یا تنظیم می‌کند. خواندنی/نوشتنی int.

--------------------

مطابق با ویژگی p14:dur در عنصر p:transition در طرح‌القاعده PresentationML. اگر تنظیم نشود، مدت زمان به‌صورت خودکار بر پایه ویژگی \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) و نوع انتقال محاسبه می‌شود.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |