---
title: ISlideShowTransition
second_title: Aspose.Slides for Java API Reference
description: نمایانگر انتقال نمایش اسلاید.
type: docs
url: /fa/com.aspose.slides/islideshowtransition/
---```
public interface ISlideShowTransition
```

نمایانگر انتقال نمایش اسلاید.
## متدها

| متد | توضیح |
| --- | --- |
| [getSound()](#getSound--) | داده‌های صوتی تعبیه‌شده را برمی‌گرداند یا تنظیم می‌کند. |
| [setSound(IAudio value)](#setSound-com.aspose.slides.IAudio-) | داده‌های صوتی تعبیه‌شده را برمی‌گرداند یا تنظیم می‌کند. |
| [getSoundMode()](#getSoundMode--) | حالت صدا برای انتقال اسلاید را تنظیم یا برمی‌گرداند. |
| [setSoundMode(int value)](#setSoundMode-int-) | حالت صدا برای انتقال اسلاید را تنظیم یا برمی‌گرداند. |
| [getSoundLoop()](#getSoundLoop--) | این ویژگی مشخص می‌کند که آیا صدا تا وقوع رویداد صوتی بعدی در نمایش اسلاید حلقه می‌زند یا نه. |
| [setSoundLoop(boolean value)](#setSoundLoop-boolean-) | این ویژگی مشخص می‌کند که آیا صدا تا وقوع رویداد صوتی بعدی در نمایش اسلاید حلقه می‌زند یا نه. |
| [getAdvanceOnClick()](#getAdvanceOnClick--) | مشخص می‌کند که آیا کلیک ماوس اسلاید را پیشروی می‌کند یا خیر. |
| [setAdvanceOnClick(boolean value)](#setAdvanceOnClick-boolean-) | مشخص می‌کند که آیا کلیک ماوس اسلاید را پیشروی می‌کند یا خیر. |
| [getAdvanceAfter()](#getAdvanceAfter--) | این ویژگی تعیین می‌کند که آیا نمایش اسلاید پس از زمان مشخصی به اسلاید بعدی می‌پرد یا خیر. |
| [setAdvanceAfter(boolean value)](#setAdvanceAfter-boolean-) | این ویژگی تعیین می‌کند که آیا نمایش اسلاید پس از زمان مشخصی به اسلاید بعدی می‌پرد یا خیر. |
| [getAdvanceAfterTime()](#getAdvanceAfterTime--) | زمان را بر حسب میلی‌ثانیه مشخص می‌کند که پس از آن انتقال باید شروع شود. |
| [setAdvanceAfterTime(long value)](#setAdvanceAfterTime-long-) | زمان را بر حسب میلی‌ثانیه مشخص می‌کند که پس از آن انتقال باید شروع شود. |
| [getSpeed()](#getSpeed--) | سرعت انتقال را که هنگام انتقال از اسلاید فعلی به اسلاید بعدی استفاده می‌شود، مشخص می‌کند. |
| [setSpeed(int value)](#setSpeed-int-) | سرعت انتقال را که هنگام انتقال از اسلاید فعلی به اسلاید بعدی استفاده می‌شود، مشخص می‌کند. |
| [getValue()](#getValue--) | مقدار انتقال نمایش اسلاید. |
| [getType()](#getType--) | نوع انتقال. |
| [setType(int value)](#setType-int-) | نوع انتقال. |
| [getSoundIsBuiltIn()](#getSoundIsBuiltIn--) | مشخص می‌کند که آیا این صدا یک صدای پیش‌ساخته است یا خیر. |
| [setSoundIsBuiltIn(boolean value)](#setSoundIsBuiltIn-boolean-) | مشخص می‌کند که آیا این صدا یک صدای پیش‌ساخته است یا خیر. |
| [getSoundName()](#getSoundName--) | نامی قابل خواندن برای صداهای انتقال مشخص می‌کند. |
| [setSoundName(String value)](#setSoundName-java.lang.String-) | نامی قابل خواندن برای صداهای انتقال مشخص می‌کند. |
| [getDuration()](#getDuration--) | مدت زمان اثر انتقال اسلاید را بر حسب میلی‌ثانیه به‌دست می‌آورد یا تنظیم می‌کند. |
| [setDuration(int value)](#setDuration-int-) | مدت زمان اثر انتقال اسلاید را بر حسب میلی‌ثانیه به‌دست می‌آورد یا تنظیم می‌کند. |
### getSound() {#getSound--}
```
public abstract IAudio getSound()
```

داده‌های صوتی تعبیه‌شده را برمی‌گرداند یا تنظیم می‌کند. خواندن-نوشتن [IAudio](../../com.aspose.slides/iaudio).

**بازگشت:**
[IAudio](../../com.aspose.slides/iaudio)
### setSound(IAudio value) {#setSound-com.aspose.slides.IAudio-}
```
public abstract void setSound(IAudio value)
```

داده‌های صوتی تعبیه‌شده را برمی‌گرداند یا تنظیم می‌کند. خواندن-نوشتن [IAudio](../../com.aspose.slides/iaudio).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IAudio](../../com.aspose.slides/iaudio) |  |
### getSoundMode() {#getSoundMode--}
```
public abstract int getSoundMode()
```

حالت صدا برای انتقال اسلاید را تنظیم یا برمی‌گرداند. خواندن-نوشتن [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**بازگشت:**
int
### setSoundMode(int value) {#setSoundMode-int-}
```
public abstract void setSoundMode(int value)
```

حالت صدا برای انتقال اسلاید را تنظیم یا برمی‌گرداند. خواندن-نوشتن [TransitionSoundMode](../../com.aspose.slides/transitionsoundmode).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getSoundLoop() {#getSoundLoop--}
```
public abstract boolean getSoundLoop()
```

این ویژگی مشخص می‌کند که آیا صدا تا وقوع رویداد صوتی بعدی در نمایش اسلاید حلقه می‌زند یا نه. خواندن-نوشتن boolean.

**بازگشت:**
boolean
### setSoundLoop(boolean value) {#setSoundLoop-boolean-}
```
public abstract void setSoundLoop(boolean value)
```

این ویژگی مشخص می‌کند که آیا صدا تا وقوع رویداد صوتی بعدی در نمایش اسلاید حلقه می‌زند یا نه. خواندن-نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceOnClick() {#getAdvanceOnClick--}
```
public abstract boolean getAdvanceOnClick()
```

مشخص می‌کند که آیا کلیک ماوس اسلاید را پیشروی می‌کند یا نه. اگر این ویژگی مشخص نشود مقدار true در نظر گرفته می‌شود. خواندن-نوشتن boolean.

**بازگشت:**
boolean
### setAdvanceOnClick(boolean value) {#setAdvanceOnClick-boolean-}
```
public abstract void setAdvanceOnClick(boolean value)
```

مشخص می‌کند که آیا کلیک ماوس اسلاید را پیشروی می‌کند یا نه. اگر این ویژگی مشخص نشود مقدار true در نظر گرفته می‌شود. خواندن-نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getAdvanceAfter() {#getAdvanceAfter--}
```
public abstract boolean getAdvanceAfter()
```

این ویژگی تعیین می‌کند که آیا نمایش اسلاید پس از زمان مشخصی به اسلاید بعدی می‌پرد یا خیر. خواندن-نوشتن boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین انتقال اسلاید
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // بررسی اینکه آیا پرچم پیش‌رفت اسلاید بعدی فعال است یا نه
>      if (slideTransition.getAdvanceAfter())
>      {
>          // دریافت مقدار زمان پیش‌رفت اسلاید بعدی
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

این ویژگی تعیین می‌کند که آیا نمایش اسلاید پس از زمان مشخصی به اسلاید بعدی می‌پرد یا خیر. خواندن-نوشتن boolean.

--------------------

> ```
> Presentation pres = new Presentation("demo.pptx");
>  try {
>      // دریافت اولین انتقال اسلاید
>      ISlideShowTransition slideTransition = pres.getSlides().get_Item(0).getSlideShowTransition();
> 
>      // بررسی اینکه آیا پرچم پیش‌رفت اسلاید بعدی فعال است یا نه
>      if (slideTransition.getAdvanceAfter())
>      {
>          // دریافت مقدار زمان پیش‌رفت اسلاید بعدی
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

زمان را بر حسب میلی‌ثانیه مشخص می‌کند که پس از آن انتقال باید شروع شود. این تنظیم می‌تواند همراه با ویژگی advClick استفاده شود. اگر این ویژگی مشخص نشود فرض می‌شود که هیچ پیشرفت خودکار رخ ندهد. خواندن-نوشتن long.

**بازگشت:**
long
### setAdvanceAfterTime(long value) {#setAdvanceAfterTime-long-}
```
public abstract void setAdvanceAfterTime(long value)
```

زمان را بر حسب میلی‌ثانیه مشخص می‌کند که پس از آن انتقال باید شروع شود. این تنظیم می‌تواند همراه با ویژگی advClick استفاده شود. اگر این ویژگی مشخص نشود فرض می‌شود که هیچ پیشرفت خودکار رخ ندهد. خواندن-نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |
### getSpeed() {#getSpeed--}
```
public abstract int getSpeed()
```

سرعت انتقال را که هنگام انتقال از اسلاید فعلی به اسلاید بعدی استفاده می‌شود، مشخص می‌کند. خواندن-نوشتن [TransitionSpeed](../../com.aspose.slides/transitionspeed).

**بازگشت:**
int
### setSpeed(int value) {#setSpeed-int-}
```
public abstract void setSpeed(int value)
```

سرعت انتقال را که هنگام انتقال از اسلاید فعلی به اسلاید بعدی استفاده می‌شود، مشخص می‌کند. خواندن-نوشتن [TransitionSpeed](../../com.aspose.slides/transitionspeed).

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

نوع انتقال. خواندن-نوشتن [TransitionType](../../com.aspose.slides/transitiontype).

**بازگشت:**
int
### setType(int value) {#setType-int-}
```
public abstract void setType(int value)
```

نوع انتقال. خواندن-نوشتن [TransitionType](../../com.aspose.slides/transitiontype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getSoundIsBuiltIn() {#getSoundIsBuiltIn--}
```
public abstract boolean getSoundIsBuiltIn()
```

مشخص می‌کند که آیا این صدا یک صدای پیش‌ساخته است یا خیر. اگر این ویژگی به true تنظیم شود، برنامه تولیدکننده هشدار داده می‌شود تا ویژگی name را که برای این صدا در فهرست صداهای پیش‌ساخته آن مشخص شده است، بررسی کند و می‌تواند نام یا رابط کاربری سفارشی را در صورت نیاز نمایش دهد. خواندن-نوشتن boolean.

**بازگشت:**
boolean
### setSoundIsBuiltIn(boolean value) {#setSoundIsBuiltIn-boolean-}
```
public abstract void setSoundIsBuiltIn(boolean value)
```

مشخص می‌کند که آیا این صدا یک صدای پیش‌ساخته است یا خیر. اگر این ویژگی به true تنظیم شود، برنامه تولیدکننده هشدار داده می‌شود تا ویژگی name را که برای این صدا در فهرست صداهای پیش‌ساخته آن مشخص شده است، بررسی کند و می‌تواند نام یا رابط کاربری سفارشی را در صورت نیاز نمایش دهد. خواندن-نوشتن boolean.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |
### getSoundName() {#getSoundName--}
```
public abstract String getSoundName()
```

نامی قابل خواندن برای صداهای انتقال مشخص می‌کند. ویژگی (\#getSound.getSound/\#setSound(IAudio).setSound(IAudio)) باید برای دریافت یا تنظیم نام صدا اختصاص داده شود. خواندن-نوشتن String.

**بازگشت:**
java.lang.String
### setSoundName(String value) {#setSoundName-java.lang.String-}
```
public abstract void setSoundName(String value)
```

نامی قابل خواندن برای صداهای انتقال مشخص می‌کند. ویژگی \#getSound.getSound/\#setSound(IAudio).setSound(IAudio) باید برای دریافت یا تنظیم نام صدا اختصاص داده شود. خواندن-نوشتن String.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | java.lang.String |  |
### getDuration() {#getDuration--}
```
public abstract int getDuration()
```

مدت زمان اثر انتقال اسلاید را بر حسب میلی‌ثانیه به‌دست می‌آورد یا تنظیم می‌کند. خواندن-نوشتن int.

--------------------

به ویژگی p14:dur عنصر p:transition در طرح‌نامه PresentationML مطابقت دارد. اگر تنظیم نشود، مدت زمان به‌صورت خودکار بر پایه ویژگی \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) و نوع انتقال تعیین می‌شود.

**بازگشت:**
int
### setDuration(int value) {#setDuration-int-}
```
public abstract void setDuration(int value)
```

مدت زمان اثر انتقال اسلاید را بر حسب میلی‌ثانیه به‌دست می‌آورد یا تنظیم می‌کند. خواندن-نوشتن int.

--------------------

به ویژگی p14:dur عنصر p:transition در طرح‌نامه PresentationML مطابقت دارد. اگر تنظیم نشود، مدت زمان به‌صورت خودکار بر پایه ویژگی \#getSpeed.getSpeed/\#setSpeed(int).setSpeed(int) و نوع انتقال تعیین می‌شود.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |