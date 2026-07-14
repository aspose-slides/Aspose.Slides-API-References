---
title: Connector
second_title: Aspose.Slides برای Android از طریق مرجع API Java
description: یک اتصال‌گر را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/connector/
---
**وراثت:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**تمام اینترفیس‌های پیاده‌سازی‌شده:**  
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)  
```
public class Connector extends GeometryShape implements IConnector
```

یک اتصال‌گر را نشان می‌دهد.

## متدها

| Method | Description |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | قفل‌های شکل را برمی‌گرداند. |
| [getConnectorLock()](#getConnectorLock--) | قفل‌های رابط را برمی‌گرداند. |
| [getShapeType()](#getShapeType--) | نوع AutoShape را برمی‌گرداند یا تنظیم می‌کند. |
| [setShapeType(int value)](#setShapeType-int-) | نوع AutoShape را برمی‌گرداند یا تنظیم می‌کند. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | شکلی که ابتدای رابط به آن وصل می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | شکلی که ابتدای رابط به آن وصل می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | شکلی که انتهای رابط به آن وصل می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | شکلی که انتهای رابط به آن وصل می‌شود را برمی‌گرداند یا تنظیم می‌کند. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | شاخص محل اتصال برای شکل شروع را برمی‌گرداند یا تنظیم می‌کند. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | شاخص محل اتصال برای شکل شروع را برمی‌گرداند یا تنظیم می‌کند. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | شاخص محل اتصال برای شکل انتها را برمی‌گرداند یا تنظیم می‌کند. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | شاخص محل اتصال برای شکل انتها را برمی‌گرداند یا تنظیم می‌کند. |
| [reroute()](#reroute--) | اتصال‌گر را مسیر می‌دهد به‌طوری که کوتاه‌ترین مسیر ممکن بین اشکالی که به هم متصل می‌کند را دنبال کند. |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**بازگشت:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

قفل‌های رابط را برمی‌گرداند. فقط-خواندنی [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**بازگشت:**  
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

نوع AutoShape را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [ShapeType](../../com.aspose.slides/shapetype).

**بازگشت:**  
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

نوع AutoShape را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [ShapeType](../../com.aspose.slides/shapetype).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

شکلی که ابتدای رابط به آن وصل می‌شود را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [IShape](../../com.aspose.slides/ishape).

**بازگشت:**  
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

شکلی که ابتدای رابط به آن وصل می‌شود را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [IShape](../../com.aspose.slides/ishape).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

شکلی که انتهای رابط به آن وصل می‌شود را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [IShape](../../com.aspose.slides/ishape).

**بازگشت:**  
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

شکلی که انتهای رابط به آن وصل می‌شود را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن [IShape](../../com.aspose.slides/ishape).

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

شاخص محل اتصال برای شکل شروع را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن long.

**بازگشت:**  
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

شاخص محل اتصال برای شکل شروع را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن long.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

شاخص محل اتصال برای شکل انتها را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن long.

**بازگشت:**  
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

شاخص محل اتصال برای شکل انتها را برمی‌گرداند یا تنظیم می‌کند. قابل‌خواندن/قابل‌نوشتن long.

**پارامترها:**  
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

اتصال‌گر را مسیر می‌دهد به‌طوری که کوتاه‌ترین مسیر ممکن بین اشکالی که به هم متصل می‌کند را دنبال کند.