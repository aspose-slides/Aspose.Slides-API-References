---
title: Connector
second_title: Java için Aspose.Slides API Referansı
description: Bir bağlayıcıyı temsil eder.
type: docs
url: /tr/com.aspose.slides/connector/
---
**Inheritance:**
java.lang.Object, [com.aspose.slides.Shape](../../com.aspose.slides/shape), [com.aspose.slides.GeometryShape](../../com.aspose.slides/geometryshape)

**All Implemented Interfaces:**
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
| [getShapeType()](#getShapeType--) | AutoShape tipini döndürür veya ayarlar. |
| [setShapeType(int value)](#setShapeType-int-) | AutoShape tipini döndürür veya ayarlar. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Bağlayıcının başlangıcının bağlanacağı şekli döndürür veya ayarlar. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Bağlayıcının başlangıcının bağlanacağı şekli döndürür veya ayarlar. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Bağlayıcının sonunun bağlanacağı şekli döndürür veya ayarlar. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Bağlayıcının sonunun bağlanacağı şekli döndürür veya ayarlar. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Başlangıç şekli için bağlantı noktasının dizinini döndürür veya ayarlar. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Başlangıç şekli için bağlantı noktasının dizinini döndürür veya ayarlar. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Bitiş şekli için bağlantı noktasının dizinini döndürür veya ayarlar. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Bitiş şekli için bağlantı noktasının dizinini döndürür veya ayarlar. |
| [reroute()](#reroute--) | Bağlayıcıyı, bağladığı şekiller arasındaki en kısa yolu alacak şekilde yeniden yönlendirir. |

### getShapeLock() {#getShapeLock--}
```
public final IConnectorLock getShapeLock()
```

Şeklin kilitlerini döndürür. Salt okunur [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Döndürür:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getConnectorLock() {#getConnectorLock--}
```
public final IConnectorLock getConnectorLock()
```

Bağlayıcının kilitlerini döndürür. Salt okunur [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Döndürür:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)

### getShapeType() {#getShapeType--}
```
public int getShapeType()
```

AutoShape tipini döndürür veya ayarlar. Okunabilir/Yazılabilir [ShapeType](../../com.aspose.slides/shapetype).

**Döndürür:**
int

### setShapeType(int value) {#setShapeType-int-}
```
public void setShapeType(int value)
```

AutoShape tipini döndürür veya ayarlar. Okunabilir/Yazılabilir [ShapeType](../../com.aspose.slides/shapetype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | int |  |

### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public final IShape getStartShapeConnectedTo()
```

Bağlayıcının başlangıcının bağlanacağı şekli döndürür veya ayarlar. Okunabilir/Yazılabilir [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)

### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setStartShapeConnectedTo(IShape value)
```

Bağlayıcının başlangıcının bağlanacağı şekli döndürür veya ayarlar. Okunabilir/Yazılabilir [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public final IShape getEndShapeConnectedTo()
```

Bağlayıcının sonunun bağlanacağı şekli döndürür veya ayarlar. Okunabilir/Yazılabilir [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)

### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public final void setEndShapeConnectedTo(IShape value)
```

Bağlayıcının sonunun bağlanacağı şekli döndürür veya ayarlar. Okunabilir/Yazılabilir [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |

### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public final long getStartShapeConnectionSiteIndex()
```

Başlangıç şekli için bağlantı noktasının dizinini döndürür veya ayarlar. Okunabilir/Yazılabilir long.

**Döndürür:**
long

### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public final void setStartShapeConnectionSiteIndex(long value)
```

Başlangıç şekli için bağlantı noktasının dizinini döndürür veya ayarlar. Okunabilir/Yazılabilir long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public final long getEndShapeConnectionSiteIndex()
```

Bitiş şekli için bağlantı noktasının dizinini döndürür veya ayarlar. Okunabilir/Yazılabilir long.

**Döndürür:**
long

### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public final void setEndShapeConnectionSiteIndex(long value)
```

Bitiş şekli için bağlantı noktasının dizinini döndürür veya ayarlar. Okunabilir/Yazılabilir long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |

### reroute() {#reroute--}
```
public final void reroute()
```

Bağlayıcıyı, bağladığı şekiller arasındaki en kısa yolu alacak şekilde yeniden yönlendirir.