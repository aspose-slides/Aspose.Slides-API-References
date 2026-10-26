---
title: ITextAnimation
second_title: Aspose.Slides برای Java مرجع API
description: نمایش انیمیشن متن.
type: docs
url: /fa/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

نمایش انیمیشن متن.
## متدها

| Method | Description |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | افکت جدیدی را به انتهای دنباله فعلی تا انتهای انیمیشن‌های متنی گروه اضافه می‌کند. |
| [getBuildType()](#getBuildType--) | فهرست نوع ساخت (به عنوان مثال |
| [setBuildType(int value)](#setBuildType-int-) | فهرست نوع ساخت (به عنوان مثال |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | اثر شکل مرتبط با گروه یا نه (null) خواندنی/نوشتنی [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | اثر شکل مرتبط با گروه یا نه (null) خواندنی/نوشتنی [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```


افکت جدیدی را به انتهای دنباله فعلی تا انتهای انیمیشن‌های متنی گروه اضافه می‌کند. فقط در صورتی معتبر است که تعداد پاراگراف‌های متنی برابر یا بیشتر از تعداد افکت‌های این گروه باشد!

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| effectType | int | نوع یک افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع تحریک افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**بازگشت:**
[IEffect](../../com.aspose.slides/ieffect) - شیء افکت جدید [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```


فهرست نوع ساخت (به عنوان مثال پاراگراف 1،2،3، همه یک‌باره) انیمیشن متن. خواندنی/نوشتنی \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**بازگشت:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```


فهرست نوع ساخت (به عنوان مثال پاراگراف 1،2،3، همه یک‌باره) انیمیشن متن. خواندنی/نوشتنی \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```


اثر شکل مرتبط با گروه یا نه (null) خواندنی/نوشتنی [IEffect](../../com.aspose.slides/ieffect).

**بازگشت:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```


اثر شکل مرتبط با گروه یا نه (null) خواندنی/نوشتنی [IEffect](../../com.aspose.slides/ieffect).

**پارامترها:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |