---
title: Connector
second_title: Aspose.Slides لنظام Android عبر مرجع API لجافا
description: يمثل موصلًا.
type: docs
url: /ar/com.aspose.slides/connector/
---
**الوراثة:**  
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**جميع الواجهات المُنفذة:**  
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)  
```
public class Connector extends GeometryShape implements IConnector
```

يمثّل موصلًا.

## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | تُعيد أقفال الشكل. |
| [getConnectorLock()](#getConnectorLock--) | تُعيد أقفال الموصل. |
| [getShapeType()](#getShapeType--) | تُعيد أو تُعيّن نوع AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | تُعيد أو تُعيّن نوع AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | تُعيد أو تُعيّن الشكل لإرفاق بداية الموصل به. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | تُعيد أو تُعيّن الشكل لإرفاق بداية الموصل به. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | تُعيد أو تُعيّن الشكل لإرفاق نهاية الموصل به. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | تُعيد أو تُعيّن الشكل لإرفاق نهاية الموصل به. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | تُعيد أو تُعيّن فهرس موقع الاتصال للشكل الابتدائي. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | تُعيد أو تُعيّن فهرس موقع الاتصال للشكل الابتدائي. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | تُعيد أو تُعيّن فهرس موقع الاتصال للشكل النهائي. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | تُعيد أو تُعيّن فهرس موقع الاتصال للشكل النهائي. |
| [reroute()](#reroute--) | يعيد توجيه الموصل بحيث يأخذ أقصر مسار ممكن بين الأشكال التي يربطها. |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

تُعيد أقفال الشكل. للقراءة فقط [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**الإرجاع:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

تُعيد أقفال الموصل. للقراءة فقط [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**الإرجاع:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

تُعيد أو تُعيّن نوع AutoShape. للقراءة والكتابة [ShapeType](../../com.aspose.slides/shapetype).

**الإرجاع:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

تُعيد أو تُعيّن نوع AutoShape. للقراءة والكتابة [ShapeType](../../com.aspose.slides/shapetype).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

تُعيد أو تُعيّن الشكل لإرفاق بداية الموصل به. للقراءة والكتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

تُعيد أو تُعيّن الشكل لإرفاق بداية الموصل به. للقراءة والكتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

تُعيد أو تُعيّن الشكل لإرفاق نهاية الموصل به. للقراءة والكتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

تُعيد أو تُعيّن الشكل لإرفاق نهاية الموصل به. للقراءة والكتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

تُعيد أو تُعيّن فهرس موقع الاتصال للشكل الابتدائي. للقراءة والكتابة long.

**الإرجاع:**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

تُعيد أو تُعيّن فهرس موقع الاتصال للشكل الابتدائي. للقراءة والكتابة long.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

تُعيد أو تُعيّن فهرس موقع الاتصال للشكل النهائي. للقراءة والكتابة long.

**الإرجاع:**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

تُعيد أو تُعيّن فهرس موقع الاتصال للشكل النهائي. للقراءة والكتابة long.

**المعلمات:**
| المعامل | النوع | الوصف |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

يعيد توجيه الموصل بحيث يأخذ أقصر مسار ممكن بين الأشكال التي يربطها.