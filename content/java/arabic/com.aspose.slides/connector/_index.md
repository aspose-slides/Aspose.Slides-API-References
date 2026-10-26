---
title: Connector
second_title: مرجع Aspose.Slides لواجهة برمجة تطبيقات Java
description: يمثل موصلاً.
type: docs
url: /ar/com.aspose.slides/connector/
---
**الوراثة:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**جميع الواجهات المنفذة:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

يمثل موصلاً.
## الطرق

| الطريقة | الوصف |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | يعيد أقفال الشكل. |
| [getConnectorLock()](#getConnectorLock--) | يعيد أقفال الموصل. |
| [getShapeType()](#getShapeType--) | يعيد أو يضبط نوع AutoShape. |
| [setShapeType(int value)](#setShapeType-int-) | يعيد أو يضبط نوع AutoShape. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | يعيد أو يضبط الشكل الذي يربط به بداية الموصل. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | يعيد أو يضبط الشكل الذي يربط به بداية الموصل. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | يعيد أو يضبط الشكل الذي يربط به نهاية الموصل. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | يعيد أو يضبط الشكل الذي يربط به نهاية الموصل. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | يعيد أو يضبط فهرس موقع الاتصال للشكل الابتدائي. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | يعيد أو يضبط فهرس موقع الاتصال للشكل الابتدائي. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | يعيد أو يضبط فهرس موقع الاتصال للشكل النهائي. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | يعيد أو يضبط فهرس موقع الاتصال للشكل النهائي. |
| [reroute()](#reroute--) | يعيد توجيه الموصل بحيث يأخذ أقصر مسار ممكن بين الأشكال التي يربطها. |
### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

يعيد أقفال الشكل. للقراءة فقط [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**الإرجاع:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

يعيد أقفال الموصل. للقراءة فقط [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**الإرجاع:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

يعيد أو يضبط نوع AutoShape. قراءة/كتابة [ShapeType](../../com.aspose.slides/shapetype).

**الإرجاع:**
int
### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

يعيد أو يضبط نوع AutoShape. قراءة/كتابة [ShapeType](../../com.aspose.slides/shapetype).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | int |  |
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

يعيد أو يضبط الشكل الذي يربط به بداية الموصل. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

يعيد أو يضبط الشكل الذي يربط به بداية الموصل. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

يعيد أو يضبط الشكل الذي يربط به نهاية الموصل. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**الإرجاع:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

يعيد أو يضبط الشكل الذي يربط به نهاية الموصل. قراءة/كتابة [IShape](../../com.aspose.slides/ishape).

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

يعيد أو يضبط فهرس موقع الاتصال للشكل الابتدائي. قراءة/كتابة long.

**الإرجاع:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

يعيد أو يضبط فهرس موقع الاتصال للشكل الابتدائي. قراءة/كتابة long.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

يعيد أو يضبط فهرس موقع الاتصال للشكل النهائي. قراءة/كتابة long.

**الإرجاع:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

يعيد أو يضبط فهرس موقع الاتصال للشكل النهائي. قراءة/كتابة long.

**المعلمات:**
| المعلمة | النوع | الوصف |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public final void reroute()
```

يعيد توجيه الموصل بحيث يأخذ أقصر مسار ممكن بين الأشكال التي يربطها.