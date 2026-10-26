---
title: IConnector
second_title: Aspose.Slides لـ Android عبر مرجع API Java
description: يمثل موصلاً.
type: docs
url: /ar/com.aspose.slides/iconnector/
---
**جميع الواجهات المنفذة:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

يمثل موصلاً.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | يعيد أقفال shape. |
| [getConnectorLock()](#getConnectorLock--) | يعيد أقفال Connector. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | يعيد أو يضبط الشكل لتوصيل بداية الموصل إليه. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | يعيد أو يضبط الشكل لتوصيل بداية الموصل إليه. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | يعيد أو يضبط الشكل لتوصيل نهاية الموصل إليه. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | يعيد أو يضبط الشكل لتوصيل نهاية الموصل إليه. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | يعيد أو يضبط فهرس موقع الاتصال للshape البداية. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | يعيد أو يضبط فهرس موقع الاتصال للshape البداية. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | يعيد أو يضبط فهرس موقع الاتصال للshape النهاية. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | يعيد أو يضبط فهرس موقع الاتصال للshape النهاية. |
| [reroute()](#reroute--) | يعيد توجيه الموصل بحيث يأخذ أقصر مسار ممكن بين الأشكال التي يربطها. |

### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```

يعيد أقفال shape. للقراءة فقط [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**الإرجاع:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```

يعيد أقفال Connector. للقراءة فقط [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**الإرجاع:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```

يعيد أو يضبط الشكل لتوصيل بداية الموصل إليه. قابل للقراءة والكتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```

يعيد أو يضبط الشكل لتوصيل بداية الموصل إليه. قابل للقراءة والكتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```

يعيد أو يضبط الشكل لتوصيل نهاية الموصل إليه. قابل للقراءة والكتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```

يعيد أو يضبط الشكل لتوصيل نهاية الموصل إليه. قابل للقراءة والكتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```

يعيد أو يضبط فهرس موقع الاتصال للshape البداية. قابل للقراءة والكتابة long.

**الإرجاع:**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```

يعيد أو يضبط فهرس موقع الاتصال للshape البداية. قابل للقراءة والكتابة long.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```

يعيد أو يضبط فهرس موقع الاتصال للshape النهاية. قابل للقراءة والكتابة long.

**الإرجاع:**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```

يعيد أو يضبط فهرس موقع الاتصال للshape النهاية. قابل للقراءة والكتابة long.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public abstract void reroute()
```

يعيد توجيه الموصل بحيث يأخذ أقصر مسار ممكن بين الأشكال التي يربطها.