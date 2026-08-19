---
title: Connector
second_title: مرجع API Aspose.Slides برای Java
description: یک اتصال‌گر را نشان می‌دهد.
type: docs
url: /fa/com.aspose.slides/connector/
---
**ارث‌بری:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**همهٔ رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

یک اتصال‌گر را نشان می‌دهد.
## متدها

| متد | توضیح |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | قفل‌های شکل را بر می‌گرداند. |
| [getConnectorLock()](#getConnectorLock--) | قفل‌های اتصال‌گر را بر می‌گرداند. |
| [getShapeType()](#getShapeType--) | نوع AutoShape را بر می‌گرداند یا تنظیم می‌کند. |
| [setShapeType(int value)](#setShapeType-int-) | نوع AutoShape را بر می‌گرداند یا تنظیم می‌کند. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | شکلی را که ابتدای اتصال‌گر به آن متصل می‌شود بر می‌گرداند یا تنظیم می‌کند. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | شکلی را که ابتدای اتصال‌گر به آن متصل می‌شود بر می‌گرداند یا تنظیم می‌کند. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | شکلی را که انتهای اتصال‌گر به آن متصل می‌شود بر می‌گرداند یا تنظیم می‌کند. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | شکلی را که انتهای اتصال‌گر به آن متصل می‌شود بر می‌گرداند یا تنظیم می‌کند. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | اندیس محل اتصال برای شکل شروع را بر می‌گرداند یا تنظیم می‌کند. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | اندیس محل اتصال برای شکل شروع را بر می‌گرداند یا تنظیم می‌کند. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | اندیس محل اتصال برای شکل پایان را بر می‌گرداند یا تنظیم می‌کند. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | اندیس محل اتصال برای شکل پایان را بر می‌گرداند یا تنظیم می‌کند. |
| [reroute()](#reroute--) | اتصال‌گر را به گونه‌ای بازمسیر می‌دهد که کوتاه‌ترین مسیر ممکن بین اشکالی که به هم وصل می‌کند را بگیرد. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

قفل‌های شکل را بر می‌گرداند. فقط-خواندنی [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**بازگشت:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

قفل‌های اتصال‌گر را بر می‌گرداند. فقط-خواندنی [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**بازگشت:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

نوع AutoShape را بر می‌گرداند یا تنظیم می‌کند. قابل‌نوشت [ShapeType](../../com.aspose.slides/shapetype).

**بازگشت:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

نوع AutoShape را بر می‌گرداند یا تنظیم می‌کند. قابل‌نوشت [ShapeType](../../com.aspose.slides/shapetype).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

شکلی را که ابتدای اتصال‌گر به آن متصل می‌شود بر می‌گرداند یا تنظیم می‌کند. قابل‌نوشت [IShape](../../com.aspose.slides/ishape).

**بازگشت:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

شکلی را که ابتدای اتصال‌گر به آن متصل می‌شود بر می‌گرداند یا تنظیم می‌کند. قابل‌نوشت [IShape](../../com.aspose.slides/ishape).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

شکلی را که انتهای اتصال‌گر به آن متصل می‌شود بر می‌گرداند یا تنظیم می‌کند. قابل‌نوشت [IShape](../../com.aspose.slides/ishape).

**بازگشت:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

شکلی را که انتهای اتصال‌گر به آن متصل می‌شود بر می‌گرداند یا تنظیم می‌کند. قابل‌نوشت [IShape](../../com.aspose.slides/ishape).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

اندیس محل اتصال برای شکل شروع را بر می‌گرداند یا تنظیم می‌کند. قابل‌نوشت long.

**بازگشت:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

اندیس محل اتصال برای شکل شروع را بر می‌گرداند یا تنظیم می‌کند. قابل‌نوشت long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

اندیس محل اتصال برای شکل پایان را بر می‌گرداند یا تنظیم می‌کند. قابل‌نوشت long.

**بازگشت:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionIndex(long value)
```

اندیس محل اتصال برای شکل پایان را بر می‌گرداند یا تنظیم می‌کند. قابل‌نوشت long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```

اتصال‌گر را به گونه‌ای بازمسیر می‌دهد که کوتاه‌ترین مسیر ممکن بین اشکالی که به هم وصل می‌کند را بگیرد.