---
title: Behavior
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: رفتار کلاس پایه اثر را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/behavior/
---
**ارث‌برداری:**  
java.lang.Object

**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject  
```
public abstract class Behavior implements IBehavior, IDOMObject
```

رفتار کلاس پایه اثر را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | نشان می‌دهد آیا رفتارهای انیمیشن جمع می‌شوند یا خیر. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | نشان می‌دهد آیا رفتارهای انیمیشن جمع می‌شوند یا خیر. |
| [getAdditive()](#getAdditive--) | نشان می‌دهد آیا رفتار انیمیشن فعلی با سایر انیمیشن‌های در حال اجرا ترکیب می‌شود یا خیر. |
| [setAdditive(int value)](#setAdditive-int-) | نشان می‌دهد آیا رفتار انیمیشن فعلی با سایر انیمیشن‌های در حال اجرا ترکیب می‌شود یا خیر. |
| [getProperties()](#getProperties--) | خواص رفتار را نشان می‌دهد. |
| [getTiming()](#getTiming--) | خواص زمان‌بندی برای رفتار اثر را نشان می‌دهد. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | خواص زمان‌بندی برای رفتار اثر را نشان می‌دهد. |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شی Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**بازگشت:**  
com.aspose.slides.IDOMObject
### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

نشان می‌دهد آیا رفتارهای انیمیشن جمع می‌شوند یا خیر. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**بازگشت:**  
byte
### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

نشان می‌دهد آیا رفتارهای انیمیشن جمع می‌شوند یا خیر. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | byte |  |
### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

نشان می‌دهد آیا رفتار انیمیشن فعلی با سایر انیمیشن‌های در حال اجرا ترکیب می‌شود یا خیر. خواندنی/نوشتنی [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**بازگشت:**  
int
### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

نشان می‌دهد آیا رفتار انیمیشن فعلی با سایر انیمیشن‌های در حال اجرا ترکیب می‌شود یا خیر. خواندنی/نوشتنی [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

خواص رفتار را نشان می‌دهد. فقط-خواندنی [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**بازگشت:**  
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)
### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

خواص زمان‌بندی برای رفتار اثر را نشان می‌دهد. خواندنی/نوشتنی [ITiming](../../com.aspose.slides/itiming).

**بازگشت:**  
[ITiming](../../com.aspose.slides/itiming)
### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

خواص زمان‌بندی برای رفتار اثر را نشان می‌دهد. خواندنی/نوشتنی [ITiming](../../com.aspose.slides/itiming).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |