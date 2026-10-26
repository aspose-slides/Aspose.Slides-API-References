---
title: TextAnimation
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: نمایانگر انیمیشن متن.
type: docs
url: /fa/com.aspose.slides/textanimation/
---
**ارث‌بری:**
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.ITextAnimation](../../com.aspose.slides/itextanimation)
```
public class TextAnimation implements ITextAnimation
```

نمایش انیمیشن متن.
## سازنده‌ها

| سازنده | توضیح |
| --- | --- |
| [TextAnimation()](#TextAnimation--) |  |
## متدها

| متد | توضیح |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | افکت جدیدی را به انتهای دنبالهٔ فعلی برای انتهای انیمیشن‌های متنی گروه اضافه می‌کند. |
| [getBuildType()](#getBuildType--) | لیست نوع ساخت (برای مثال |
| [setBuildType(int value)](#setBuildType-int-) | لیست نوع ساخت (برای مثال |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | افکت شکل مرتبط با گروه یا نه (null). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | افکت شکل مرتبط با گروه یا نه (null). |
### TextAnimation() {#TextAnimation--}
```
public TextAnimation()
```


### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public final IEffect addEffect(int effectType, int subtype, int triggerType)
```


افکت جدیدی را به انتهای دنبالهٔ فعلی برای انتهای انیمیشن‌های متنی گروه اضافه می‌کند. فقط در صورتی معتبر است که شمارش پاراگراف‌های متن برابر یا بیشتر از شمارش افکت‌های این گروه باشد!

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| effectType | int | نوع اثر انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع‌های اثر انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع فعال‌سازی اثر [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**بازگشت:**
[IEffect](../../com.aspose.slides/ieffect) - شیء افکت جدید [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public final int getBuildType()
```


لیست نوع ساخت (برای مثال پاراگراف 1,2,3, همه به‌صورت همزمان) انیمیشن متن. خواندنی/قابل نوشتن [BuildType](../../com.aspose.slides/buildtype).

**بازگشت:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public final void setBuildType(int value)
```


لیست نوع ساخت (برای مثال پاراگراف 1,2,3, همه به‌صورت همزمان) انیمیشن متن. خواندنی/قابل نوشتن [BuildType](../../com.aspose.slides/buildtype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public final IEffect getEffectAnimateBackgroundShape()
```


افکت شکل مرتبط با گروه یا نه (null). خواندنی/قابل نوشتن [IEffect](../../com.aspose.slides/ieffect).

**بازگشت:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public final void setEffectAnimateBackgroundShape(IEffect value)
```


افکت شکل مرتبط با گروه یا نه (null). خواندنی/قابل نوشتن [IEffect](../../com.aspose.slides/ieffect).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |