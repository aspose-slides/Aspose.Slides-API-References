---
title: IBehavior
second_title: Aspose.Slides for Java API Reference
description: Represent base class behavior of effect.
type: docs
url: /fa/com.aspose.slides/ibehavior/
---```
public interface IBehavior
```

نمایش می‌دهد رفتار کلاس پایهٔ اثر.

## متدها

| متد | توضیح |
| --- | --- |
| [getAccumulate()](#getAccumulate--) | Represents whether animation behaviors are accumulated. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | Represents whether animation behaviors are accumulated. |
| [getAdditive()](#getAdditive--) | Represents whether the current animation behavior is combined with other running animations. |
| [setAdditive(int value)](#setAdditive-int-) | Represents whether the current animation behavior is combined with other running animations. |
| [getProperties()](#getProperties--) | Represents properties of behavior. |
| [getTiming()](#getTiming--) | Represents timing properties for the effect behavior. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | Represents timing properties for the effect behavior. |
### getAccumulate() {#getAccumulate--}
```
public abstract byte getAccumulate()
```

نمایش می‌دهد که آیا رفتارهای انیمیشن انباشته می‌شوند. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**باز می‌گرداند:**
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public abstract void setAccumulate(byte value)
```

نمایش می‌دهد که آیا رفتارهای انیمیشن انباشته می‌شوند. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public abstract int getAdditive()
```

نمایش می‌دهد که آیا رفتار جاری انیمیشن با انیمیشن‌های در حال اجرا ترکیب می‌شود. خواندنی/نوشتنی [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**باز می‌گرداند:**
int
### setAdditive(int value) {#setAdditive-int-}
```
public abstract void setAdditive(int value)
```

نمایش می‌دهد که آیا رفتار جاری انیمیشن با انیمیشن‌های در حال اجرا ترکیب می‌شود. خواندنی/نوشتنی [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public abstract IBehaviorPropertyCollection getProperties()
```

نمایش می‌دهد ویژگی‌های رفتار. فقط-خواندنی [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**باز می‌گرداند:**
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public abstract ITiming getTiming()
```

نمایش می‌دهد ویژگی‌های زمان‌بندی برای رفتار اثر. خواندنی/نوشتنی [ITiming](../../com.aspose.slides/itiming).

**باز می‌گرداند:**
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public abstract void setTiming(ITiming value)
```

نمایش می‌دهد ویژگی‌های زمان‌بندی برای رفتار اثر. خواندنی/نوشتنی [ITiming](../../com.aspose.slides/itiming).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |