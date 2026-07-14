---
title: IConnector
second_title: Aspose.Slides برای Android از طریق مرجع API جاوا
description: نمایانگر یک کانکتور.
type: docs
url: /fa/com.aspose.slides/iconnector/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

نمایانگر یک کانکتور.
## متدها

| متد | توضیح |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Returns shape's locks. |
| [getConnectorLock()](#getConnectorLock--) | Returns Connector's locks. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Returns or sets the shape to attach the beginning of the connector to. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Returns or sets the shape to attach the beginning of the connector to. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Returns or sets the shape to attach the end of the connector to. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Returns or sets the shape to attach the end of the connector to. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Returns or sets the index of connection site for start shape. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Returns or sets the index of connection site for start shape. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Returns or sets the index of connection site for end shape. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Returns or sets the index of connection site for end shape. |
| [reroute()](#reroute--) | Reroutes connector so that it take the shortest possible path between the shapes it connect. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

قفل‌های شکل را برمی‌گرداند. فقط-خواندنی [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**بازگشت:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

قفل‌های Connector را برمی‌گرداند. فقط-خواندنی [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**بازگشت:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

شکل را برمی‌گرداند یا تنظیم می‌کند تا ابتدای connector به آن متصل شود. خواندنی/نوشتنی [IShape](../../com.aspose.slides/ishape).

**بازگشت:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

شکل را برمی‌گرداند یا تنظیم می‌کند تا ابتدای connector به آن متصل شود. خواندنی/نوشتنی [IShape](../../com.aspose.slides/ishape).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

شکل را برمی‌گرداند یا تنظیم می‌کند تا انتهای connector به آن متصل شود. خواندنی/نوشتنی [IShape](../../com.aspose.slides/ishape).

**بازگشت:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

شکل را برمی‌گرداند یا تنظیم می‌کند تا انتهای connector به آن متصل شود. خواندنی/نوشتنی [IShape](../../com.aspose.slides/ishape).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

شاخص سایت اتصال برای شکل شروع را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی long.

**بازگشت:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

شاخص سایت اتصال برای شکل شروع را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

شاخص سایت اتصال برای شکل انتها را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی long.

**بازگشت:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

شاخص سایت اتصال برای شکل انتها را برمی‌گرداند یا تنظیم می‌کند. خواندنی/نوشتنی long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

اتصال‌دهنده را دوباره مسیر می‌دهد تا کوتاه‌ترین مسیر ممکن بین شکل‌هایی که به هم وصل می‌کند را بگیرد.