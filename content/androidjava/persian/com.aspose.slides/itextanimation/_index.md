---
title: ITextAnimation
second_title: Aspose.Slides برای Android از طریق API مرجع Java
description: نمایش انیمیشن متن.
type: docs
url: /fa/com.aspose.slides/itextanimation/
---```
public interface ITextAnimation
```

نمایش انیمیشن متن.
## متدها

| متد | توضیح |
| --- | --- |
| [addEffect(int effectType, int subtype, int triggerType)](#addEffect-int-int-int-) | افکت جدیدی را به انتهای توالی جاری به انتهای انیمیشن متنی گروه اضافه می‌کند. |
| [getBuildType()](#getBuildType--) | فهرست نوع ساخت (برای مثال |
| [setBuildType(int value)](#setBuildType-int-) | فهرست نوع ساخت (برای مثال |
| [getEffectAnimateBackgroundShape()](#getEffectAnimateBackgroundShape--) | افکت شکل مرتبط با گروه یا نه (null) خواندنی/نوشتنی [IEffect](../../com.aspose.slides/ieffect). |
| [setEffectAnimateBackgroundShape(IEffect value)](#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-) | افکت شکل مرتبط با گروه یا نه (null) خواندنی/نوشتنی [IEffect](../../com.aspose.slides/ieffect). |
### addEffect(int effectType, int subtype, int triggerType) {#addEffect-int-int-int-}
```
public abstract IEffect addEffect(int effectType, int subtype, int triggerType)
```

افکت جدیدی را به انتهای توالی جاری به انتهای انیمیشن متنی گروه اضافه می‌کند. فقط زمانی معتبر است که تعداد پاراگراف‌های متن برابر یا بیشتر از تعداد افکت‌های این گروه باشد!

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| effectType | int | نوع افکت انیمیشن [EffectType](../../com.aspose.slides/effecttype) |
| subtype | int | زیرنوع‌های افکت انیمیشن [EffectSubtype](../../com.aspose.slides/effectsubtype) |
| triggerType | int | نوع رخداد افکت [EffectTriggerType](../../com.aspose.slides/effecttriggertype) |

**بازگشت:**
[IEffect](../../com.aspose.slides/ieffect) - شیء افکت جدید [IEffect](../../com.aspose.slides/ieffect)
### getBuildType() {#getBuildType--}
```
public abstract int getBuildType()
```

فهرست نوع ساخت (برای مثال پاراگراف 1،2،3، همه یکجا) انیمیشن متنی. خواندنی/نوشتنی \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**بازگشت:**
int
### setBuildType(int value) {#setBuildType-int-}
```
public abstract void setBuildType(int value)
```

فهرست نوع ساخت (برای مثال پاراگراف 1،2،3، همه یکجا) انیمیشن متنی. خواندنی/نوشتنی \#getBuildType.getBuildType/\#setBuildType(int).setBuildType(int).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getEffectAnimateBackgroundShape() {#getEffectAnimateBackgroundShape--}
```
public abstract IEffect getEffectAnimateBackgroundShape()
```

افکت شکل مرتبط با گروه یا نه (null) خواندنی/نوشتنی [IEffect](../../com.aspose.slides/ieffect).

**بازگشت:**
[IEffect](../../com.aspose.slides/ieffect)
### setEffectAnimateBackgroundShape(IEffect value) {#setEffectAnimateBackgroundShape-com.aspose.slides.IEffect-}
```
public abstract void setEffectAnimateBackgroundShape(IEffect value)
```

افکت شکل مرتبط با گروه یا نه (null) خواندنی/نوشتنی [IEffect](../../com.aspose.slides/ieffect).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IEffect](../../com.aspose.slides/ieffect) |  |