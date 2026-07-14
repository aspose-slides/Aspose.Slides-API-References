---
title: IConnectorLock
second_title: Aspose.Slides برای اندروید از طریق مرجع API جاوا
description: مشخص می‌کند کدام عملیات‌ها بر روی Connector والد غیرفعال هستند.
type: docs
url: /fa/com.aspose.slides/iconnectorlock/
---
**تمام رابط‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IConnectorLock extends IBaseShapeLock
```

مشخص می‌کند که کدام عملیات‌ها بر روی Connector والد غیرفعال هستند.  
## متدها

| متد | توضیح |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | مشخص می‌کند آیا افزودن این شکل به یک گروه ممنوع است یا نه. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | مشخص می‌کند آیا افزودن این شکل به یک گروه ممنوع است یا نه. |
| [getSelectLocked()](#getSelectLocked--) | مشخص می‌کند آیا انتخاب این شکل ممنوع است یا نه. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | مشخص می‌کند آیا انتخاب این شکل ممنوع است یا نه. |
| [getRotateLocked()](#getRotateLocked--) | مشخص می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است یا نه. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | مشخص می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است یا نه. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | مشخص می‌کند آیا شکل باید نسبت عرض به ارتفاع را هنگام تغییر اندازه حفظ کند یا نه. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | مشخص می‌کند آیا شکل باید نسبت عرض به ارتفاع را هنگام تغییر اندازه حفظ کند یا نه. |
| [getPositionMove()](#getPositionMove--) | مشخص می‌کند آیا جابه‌جایی این شکل ممنوع است یا نه. |
| [setPositionMove(boolean value)](#setPositionMove-boolean-) | مشخص می‌کند آیا جابه‌جایی این شکل ممنوع است یا نه. |
| [getSizeLocked()](#getSizeLocked--) | مشخص می‌کند آیا تغییر اندازه این شکل ممنوع است یا نه. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | مشخص می‌کند آیا تغییر اندازه این شکل ممنوع است یا نه. |
| [getEditPointsLocked()](#getEditPointsLocked--) | مشخص می‌کند آیا تغییر مستقیم خطوط بیرونی این شکل ممنوع است یا نه. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | مشخص می‌کند آیا تغییر مستقیم خطوط بیرونی این شکل ممنوع است یا نه. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | مشخص می‌کند آیا تغییر مقادیر تنظیمات ممنوع است یا نه. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | مشخص می‌کند آیا تغییر مقادیر تنظیمات ممنوع است یا نه. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | مشخص می‌کند آیا تغییر سرهای پیکان ممنوع است یا نه. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | مشخص می‌کند آیا تغییر سرهای پیکان ممنوع است یا نه. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | مشخص می‌کند آیا تغییر نوع شکل ممنوع است یا نه. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | مشخص می‌کند آیا تغییر نوع شکل ممنوع است یا نه. |

### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

مشخص می‌کند آیا افزودن این شکل به یک گروه ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean  
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

مشخص می‌کند آیا افزودن این شکل به یک گروه ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

مشخص می‌کند آیا انتخاب این شکل ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean  
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

مشخص می‌کند آیا انتخاب این شکل ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

مشخص می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean  
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

مشخص می‌کند آیا تغییر زاویه چرخش این شکل ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

مشخص می‌کند آیا شکل باید نسبت عرض به ارتفاع را هنگام تغییر اندازه حفظ کند یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean  
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

مشخص می‌کند آیا شکل باید نسبت عرض به ارتفاع را هنگام تغییر اندازه حفظ کند یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getPositionMove() {#getPositionMove--}
```
public abstract boolean getPositionMove()
```

مشخص می‌کند آیا جابه‌جایی این شکل ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean  
### setPositionMove(boolean value) {#setPositionMove-boolean-}
```
public abstract void setPositionMove(boolean value)
```

مشخص می‌کند آیا جابه‌جایی این شکل ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

مشخص می‌کند آیا تغییر اندازه این شکل ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean  
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

مشخص می‌کند آیا تغییر اندازه این شکل ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

مشخص می‌کند آیا تغییر مستقیم خطوط بیرونی این شکل ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean  
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

مشخص می‌کند آیا تغییر مستقیم خطوط بیرونی این شکل ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

مشخص می‌کند آیا تغییر مقادیر تنظیمات ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean  
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

مشخص می‌کند آیا تغییر مقادیر تنظیمات ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

مشخص می‌کند آیا تغییر سرهای پیکان ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean  
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

مشخص می‌کند آیا تغییر سرهای پیکان ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

مشخص می‌کند آیا تغییر نوع شکل ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**بازگشت:**  
boolean  
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

مشخص می‌کند آیا تغییر نوع شکل ممنوع است یا نه. قابل خواندن/نوشتن boolean.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | boolean |  |