---
title: Behavior
second_title: مرجع API Aspose.Slides برای Java
description: نمایش رفتار کلاس پایهٔ اثر.
type: docs
url: /fa/com.aspose.slides/behavior/
---
**Inheritance:**  
وراثت:

java.lang.Object

**All Implemented Interfaces:**  
تمام رابط‌های پیاده‌سازی‌شده:

[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior), com.aspose.slides.IDOMObject  
```
public abstract class Behavior implements IBehavior, IDOMObject
```

رفتار کلاس پایه اثر را نشان می‌دهد.

## متدها

| Method | Description |
| --- | --- |
| [getParent_Immediate()](#getParent-Immediate--) |  |
| [getAccumulate()](#getAccumulate--) | نشان می‌دهد آیا رفتارهای انیمیشن انباشت می‌شوند. |
| [setAccumulate(byte value)](#setAccumulate-byte-) | نشان می‌دهد آیا رفتارهای انیمیشن انباشت می‌شوند. |
| [getAdditive()](#getAdditive--) | نشان می‌دهد آیا رفتار فعلی انیمیشن با انیمیشن‌های دیگر در حال اجرا ترکیب می‌شود. |
| [setAdditive(int value)](#setAdditive-int-) | نشان می‌دهد آیا رفتار فعلی انیمیشن با انیمیشن‌های دیگر در حال اجرا ترکیب می‌شود. |
| [getProperties()](#getProperties--) | نشان می‌دهد ویژگی‌های رفتار. |
| [getTiming()](#getTiming--) | نشان می‌دهد ویژگی‌های زمان‌بندی برای رفتار اثر. |
| [setTiming(ITiming value)](#setTiming-com.aspose.slides.ITiming-) | نشان می‌دهد ویژگی‌های زمان‌بندی برای رفتار اثر. |

### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```

شی Parent_Immediate را برمی‌گرداند. فقط-خواندنی IDOMObject.

**Returns:**  
com.aspose.slides.IDOMObject

### getAccumulate() {#getAccumulate--}
```
public final byte getAccumulate()
```

نشان می‌دهد آیا رفتارهای انیمیشن انباشت می‌شوند. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**Returns:**  
byte

### setAccumulate(byte value) {#setAccumulate-byte-}
```
public final void setAccumulate(byte value)
```

نشان می‌دهد آیا رفتارهای انیمیشن انباشت می‌شوند. خواندنی/نوشتنی [NullableBool](../../com.aspose.slides/nullablebool).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getAdditive() {#getAdditive--}
```
public final int getAdditive()
```

نشان می‌دهد آیا رفتار فعلی انیمیشن با انیمیشن‌های دیگر در حال اجرا ترکیب می‌شود. خواندنی/نوشتنی [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Returns:**  
int

### setAdditive(int value) {#setAdditive-int-}
```
public final void setAdditive(int value)
```

نشان می‌دهد آیا رفتار فعلی انیمیشن با انیمیشن‌های دیگر در حال اجرا ترکیب می‌شود. خواندنی/نوشتنی [BehaviorAdditiveType](../../com.aspose.slides/behavioradditivetype).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getProperties() {#getProperties--}
```
public final IBehaviorPropertyCollection getProperties()
```

نشان می‌دهد ویژگی‌های رفتار. فقط-خواندنی [IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection).

**Returns:**  
[IBehaviorPropertyCollection](../../com.aspose.slides/ibehaviorpropertycollection)

### getTiming() {#getTiming--}
```
public final ITiming getTiming()
```

نشان می‌دهد ویژگی‌های زمان‌بندی برای رفتار اثر. خواندنی/نوشتنی [ITiming](../../com.aspose.slides/itiming).

**Returns:**  
[ITiming](../../com.aspose.slides/itiming)

### setTiming(ITiming value) {#setTiming-com.aspose.slides.ITiming-}
```
public final void setTiming(ITiming value)
```

نشان می‌دهد ویژگی‌های زمان‌بندی برای رفتار اثر. خواندنی/نوشتنی [ITiming](../../com.aspose.slides/itiming).

**Parameters:**  
| Parameter | Type | Description |
| --- | --- | --- |
| value | [ITiming](../../com.aspose.slides/itiming) |  |