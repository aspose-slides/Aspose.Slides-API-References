---
title: IConnector
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir bağlayıcıyı temsil eder.
type: docs
url: /tr/com.aspose.slides/iconnector/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Bir bağlayıcıyı temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Şeklin kilitlerini döndürür. |
| [getConnectorLock()](#getConnectorLock--) | Connector'ın kilitlerini döndürür. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Bağlayıcının başlangıcına iliştirilmek üzere şekli döndürür veya ayarlar. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Bağlayıcının başlangıcına iliştirilmek üzere şekli döndürür veya ayarlar. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Bağlayıcının sonuna iliştirilmek üzere şekli döndürür veya ayarlar. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Bağlayıcının sonuna iliştirilmek üzere şekli döndürür veya ayarlar. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Başlangıç şekli için bağlantı noktasının indeksini döndürür veya ayarlar. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Başlangıç şekli için bağlantı noktasının indeksini döndürür veya ayarlar. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Bitiş şekli için bağlantı noktasının indeksini döndürür veya ayarlar. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Bitiş şekli için bağlantı noktasının indeksini döndürür veya ayarlar. |
| [reroute()](#reroute--) | Bağlayıcıyı, bağladığı şekiller arasındaki olası en kısa yolu alacak şekilde yeniden yönlendirir. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Şeklin kilitlerini döndürür. Sadece okuma [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Döndürür:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Connector'ın kilitlerini döndürür. Sadece okuma [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Döndürür:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Bağlayıcının başlangıcına iliştirilmek üzere şekli döndürür veya ayarlar. Okuma/Yazma [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Bağlayıcının başlangıcına iliştirilmek üzere şekli döndürür veya ayarlar. Okuma/Yazma [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Bağlayıcının sonuna iliştirilmek üzere şekli döndürür veya ayarlar. Okuma/Yazma [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Bağlayıcının sonuna iliştirilmek üzere şekli döndürür veya ayarlar. Okuma/Yazma [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Başlangıç şekli için bağlantı noktasının indeksini döndürür veya ayarlar. Okuma/Yazma long.

**Döndürür:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Başlangıç şekli için bağlantı noktasının indeksini döndürür veya ayarlar. Okuma/Yazma long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Bitiş şekli için bağlantı noktasının indeksini döndürür veya ayarlar. Okuma/Yazma long.

**Döndürür:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Bitiş şekli için bağlantı noktasının indeksini döndürür veya ayarlar. Okuma/Yazma long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```


Bağlayıcıyı, bağladığı şekiller arasındaki mümkün olan en kısa yolu alacak şekilde yeniden yönlendirir.