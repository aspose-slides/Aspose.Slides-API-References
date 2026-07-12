---
title: Connector
second_title: Aspose.Slides for Android için Java API Referansı
description: Bir bağlayıcıyı temsil eder.
type: docs
url: /tr/com.aspose.slides/connector/
---
**Kalıtım:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**Tüm Uygulanan Arayüzler:**
[com.aspose.slides.IConnector](../../com.aspose.slides/iconnector)
```
public class Connector extends GeometryShape implements IConnector
```

Bir bağlayıcıyı temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Şeklin kilitlerini döndürür. |
| [getConnectorLock()](#getConnectorLock--) | Bağlayıcının kilitlerini döndürür. |
| [getShapeType()](#getShapeType--) | AutoShape türünü döndürür veya ayarlar. |
| [setShapeType(int value)](#setShapeType-int-) | AutoShape türünü döndürür veya ayarlar. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Bağlayıcının başlangıcına bağlanacak şekli döndürür veya ayarlar. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Bağlayıcının başlangıcına bağlanacak şekli döndürür veya ayarlar. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Bağlayıcının sonuna bağlanacak şekli döndürür veya ayarlar. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Bağlayıcının sonuna bağlanacak şekli döndürür veya ayarlar. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Başlangıç şekli için bağlantı noktasının dizinini döndürür veya ayarlar. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Başlangıç şekli için bağlantı noktasının dizinini döndürür veya ayarlar. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Bitiş şekli için bağlantı noktasının dizinini döndürür veya ayarlar. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Bitiş şekli için bağlantı noktasının dizinini döndürür veya ayarlar. |
| [reroute()](#reroute--) | Bağlayıcıyı, bağladığı şekiller arasında mümkün olan en kısa yolu alacak şekilde yeniden yönlendirir. |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Şeklin kilitlerini döndürür. Salt-okunur [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Döndürür:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

Bağlayıcının kilitlerini döndürür. Salt-okunur [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Döndürür:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

AutoShape türünü döndürür veya ayarlar. Okunur/yazılır [ShapeType](../../com.aspose.slides/shapetype).

**Döndürür:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

AutoShape türünü döndürür veya ayarlar. Okunur/yazılır [ShapeType](../../com.aspose.slides/shapetype).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Bağlayıcının başlangıcına bağlanacak şekli döndürür veya ayarlar. Okunur/yazılır [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Bağlayıcının başlangıcına bağlanacak şekli döndürür veya ayarlar. Okunur/yazılır [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Bağlayıcının sonuna bağlanacak şekli döndürür veya ayarlar. Okunur/yazılır [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Bağlayıcının sonuna bağlanacak şekli döndürür veya ayarlar. Okunur/yazılır [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Başlangıç şekli için bağlantı noktasının dizinini döndürür veya ayarlar. Okunur/yazılır long.

**Döndürür:**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Başlangıç şekli için bağlantı noktasının dizinini döndürür veya ayarlar. Okunur/yazılır long.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Bitiş şekli için bağlantı noktasının dizinini döndürür veya ayarlar. Okunur/yazılır long.

**Döndürür:**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

Bitiş şekli için bağlantı noktasının dizinini döndürür veya ayarlar. Okunur/yazılır long.

**Parametreler:**
| Parametre | Tip | Açıklama |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

Bağlayıcıyı, bağladığı şekiller arasında mümkün olan en kısa yolu alacak şekilde yeniden yönlendirir.