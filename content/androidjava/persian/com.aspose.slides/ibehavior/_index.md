---
title: IBehavior
second_title: Aspose.Slides for Android via Java API Reference
description: Represent base class behavior of effect.
type: docs
url: /fa/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

رفتار پایهٔ کلاس اثر را نمایندگی می‌کند.
## متدها

| متد | توضیح |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | نمایش می‌دهد که آیا رفتارهای انیمیشن انباشته می‌شوند یا نه. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | نمایش می‌دهد که آیا رفتارهای انیمیشن انباشته می‌شوند یا نه. |
| [getAdditive()](#getAdditive--) | نمایش می‌دهد که آیا رفتار فعلی انیمیشن با سایر انیمیشن‌های در حال اجرا ترکیب می‌شود یا نه. |
| [setAdditive(int value)](#setAdditive-int-) | نمایش می‌دهد که آیا رفتار فعلی انیمیشن با سایر انیمیشن‌های در حال اجرا ترکیب می‌شود یا نه. |
| [getProperties()](#getProperties--) | خواص رفتار را نمایندگی می‌کند. |
| [getTiming()](#getTiming--) | خواص زمان‌بندی برای رفتار اثر را نمایندگی می‌کند. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | خواص زمان‌بندی برای رفتار اثر را نمایندگی می‌کند. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

نمایش می‌دهد که آیا رفتارهای انیمیشن انباشته می‌شوند یا نه. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگرداندن:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

نمایش می‌دهد که آیا رفتارهای انیمیشن انباشته می‌شوند یا نه. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

نمایش می‌دهد که آیا رفتار فعلی انیمیشن با سایر انیمیشن‌های در حال اجرا ترکیب می‌شود یا نه. خواندنی/نوشتنی [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**بازگرداندن:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

نمایش می‌دهد که آیا رفتار فعلی انیمیشن با سایر انیمیشن‌های در حال اجرا ترکیب می‌شود یا نه. خواندنی/نوشتنی [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

خواص رفتار را نمایندگی می‌کند. فقط-خواندنی [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**بازگرداندن:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

خواص زمان‌بندی برای رفتار اثر را نمایندگی می‌کند. خواندنی/نوشتنی [ITiming](../../com.aspose.slides/itiming).

**بازگرداندن:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

خواص زمان‌بندی برای رفتار اثر را نمایندگی می‌کند. خواندنی/نوشتنی [ITiming](../../com.aspose.slides/itiming).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |