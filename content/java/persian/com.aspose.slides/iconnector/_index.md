---
title: IConnector
second_title: Aspose.Slides برای مرجع API جاوا
description: نمایانگر یک connector است.
type: docs
url: /fa/com.aspose.slides/iconnector/
---
**تمام رابط‌های پیاده‌سازی‌شده:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

نمایش‌دهنده یک اتصال‌دهنده است.
## متدها

| متد | توضیح |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | قفل‌های شکل را برمی‌گرداند. |
| [getConnectorLock()](#getConnectorLock--) | قفل‌های Connector را برمی‌گرداند. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | شکل متصل به ابتدای اتصال‌دهنده را برمی‌گرداند یا تنظیم می‌کند. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | شکل متصل به ابتدای اتصال‌دهنده را برمی‌گرداند یا تنظیم می‌کند. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | شکل متصل به انتهای اتصال‌دهنده را برمی‌گرداند یا تنظیم می‌کند. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | شکل متصل به انتهای اتصال‌دهنده را برمی‌گرداند یا تنظیم می‌کند. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | نمایه‌ی مکان اتصال برای شکل شروع را برمی‌گرداند یا تنظیم می‌کند. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | نمایه‌ی مکان اتصال برای شکل شروع را برمی‌گرداند یا تنظیم می‌کند. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | نمایه‌ی مکان اتصال برای شکل پایان را برمی‌گرداند یا تنظیم می‌کند. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | نمایه‌ی مکان اتصال برای شکل پایان را برمی‌گرداند یا تنظیم می‌کند. |
| [reroute()](#reroute--) | اتصال‌دهنده را به گونه‌ای مسیر می‌دهد که کوتاه‌ترین مسیر ممکن بین شکل‌هایی که وصل می‌کند را بگیرد. |
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

شکل متصل به ابتدای اتصال‌دهنده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [IShape](../../com.aspose.slides/ishape).

**بازگشت:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

شکل متصل به ابتدای اتصال‌دهنده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [IShape](../../com.aspose.slides/ishape).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

شکل متصل به انتهای اتصال‌دهنده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [IShape](../../com.aspose.slides/ishape).

**بازگشت:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

شکل متصل به انتهای اتصال‌دهنده را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن [IShape](../../com.aspose.slides/ishape).

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

نمایه‌ی مکان اتصال برای شکل شروع را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن long.

**بازگشت:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

نمایه‌ی مکان اتصال برای شکل شروع را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

نمایه‌ی مکان اتصال برای شکل پایان را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن long.

**بازگشت:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

نمایه‌ی مکان اتصال برای شکل پایان را برمی‌گرداند یا تنظیم می‌کند. خواندنی/قابل نوشتن long.

**پارامترها:**
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```

اتصال‌دهنده را به گونه‌ای مسیر می‌دهد که کوتاه‌ترین مسیر ممکن بین شکل‌هایی که وصل می‌کند را بگیرد.