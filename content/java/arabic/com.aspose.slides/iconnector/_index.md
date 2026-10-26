---
title: IConnector
second_title: مرجع API لـ Aspose.Slides للغة Java
description: يمثل موصلاً.
type: docs
url: /ar/com.aspose.slides/iconnector/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

يمثل موصلًا.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | يرجع أقفال الشكل. |
| [getConnectorLock()](#getConnectorLock--) | يرجع أقفال الموصل. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | يرجع أو يعيّن الشكل الذي يتم إرفاق بداية الموصل إليه. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | يرجع أو يعيّن الشكل الذي يتم إرفاق بداية الموصل إليه. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | يرجع أو يعيّن الشكل الذي يتم إرفاق نهاية الموصل إليه. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | يرجع أو يعيّن الشكل الذي يتم إرفاق نهاية الموصل إليه. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | يرجع أو يعيّن فهرس موقع الاتصال للشكل الابتدائي. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | يرجع أو يعيّن فهرس موقع الاتصال للشكل الابتدائي. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | يرجع أو يعيّن فهرس موقع الاتصال للشكل النهائي. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | يرجع أو يعيّن فهرس موقع الاتصال للشكل النهائي. |
| [reroute()](#reroute--) | يعيد توجيه الموصل بحيث يأخذ أقصر مسار ممكن بين الأشكال التي يربطها. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

يرجع أقفال الشكل. قراءة فقط [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**الإرجاع:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

يرجع أقفال الموصل. قراءة فقط [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**الإرجاع:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

يرجع أو يعيّن الشكل الذي يتم إرفاق بداية الموصل إليه. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

يرجع أو يعيّن الشكل الذي يتم إرفاق بداية الموصل إليه. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

يرجع أو يعيّن الشكل الذي يتم إرفاق نهاية الموصل إليه. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

يرجع أو يعيّن الشكل الذي يتم إرفاق نهاية الموصل إليه. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

يرجع أو يعيّن فهرس موقع الاتصال للشكل الابتدائي. قراءة/كتابة long.

**الإرجاع:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

يرجع أو يعيّن فهرس موقع الاتصال للشكل الابتدائي. قراءة/كتابة long.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

يرجع أو يعيّن فهرس موقع الاتصال للشكل النهائي. قراءة/كتابة long.

**الإرجاع:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

يرجع أو يعيّن فهرس موقع الاتصال للشكل النهائي. قراءة/كتابة long.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```

يعيد توجيه الموصل بحيث يأخذ أقصر مسار ممكن بين الأشكال التي يربطها.