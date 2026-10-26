---
title: IConnector
second_title: Aspose.Slides for Java API Referansı
description: Bir bağlayıcıyı temsil eder.
type: docs
url: /tr/com.aspose.slides/iconnector/
---
**Tüm Gerçekleştirilen Arayüzler:**
[com.aspose.slides.IGeometryShape](../../com.aspose.slides/igeometryshape)
```
public interface IConnector extends IGeometryShape
```

Bir bağlayıcıyı temsil eder.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getShapeLock()](#getShapeLock--) | Şeklin kilitlerini döndürür. |
| [getConnectorLock()](#getConnectorLock--) | Bağlayıcının kilitlerini döndürür. |
| [getStartShapeConnectedTo()](#getStartShapeConnectedTo--) | Bağlayıcının başlangıcını bağlamak için şekli döndürür veya ayarlar. |
| [setStartShapeConnectedTo(IShape value)](#setStartShapeConnectedTo-com.aspose.slides.IShape-) | Bağlayıcının başlangıcını bağlamak için şekli döndürür veya ayarlar. |
| [getEndShapeConnectedTo()](#getEndShapeConnectedTo--) | Bağlayıcının sonunu bağlamak için şekli döndürür veya ayarlar. |
| [setEndShapeConnectedTo(IShape value)](#setEndShapeConnectedTo-com.aspose.slides.IShape-) | Bağlayıcının sonunu bağlamak için şekli döndürür veya ayarlar. |
| [getStartShapeConnectionSiteIndex()](#getStartShapeConnectionSiteIndex--) | Başlangıç şekli için bağlantı noktasının indeksini döndürür veya ayarlar. |
| [setStartShapeConnectionSiteIndex(long value)](#setStartShapeConnectionSiteIndex-long-) | Başlangıç şekli için bağlantı noktasının indeksini döndürür veya ayarlar. |
| [getEndShapeConnectionSiteIndex()](#getEndShapeConnectionSiteIndex--) | Bitiş şekli için bağlantı noktasının indeksini döndürür veya ayarlar. |
| [setEndShapeConnectionSiteIndex(long value)](#setEndShapeConnectionSiteIndex-long-) | Bitiş şekli için bağlantı noktasının indeksini döndürür veya ayarlar. |
| [reroute()](#reroute--) | Bağlayıcıyı, bağladığı şekiller arasında mümkün olan en kısa yolu alacak şekilde yeniden yönlendirir. |
### getShapeLock() {#getShapeLock--}
```
public abstract IConnectorLock getShapeLock()
```


Şeklin kilitlerini döndürür. Salt-okunur [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Döndürür:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getConnectorLock() {#getConnectorLock--}
```
public abstract IConnectorLock getConnectorLock()
```


Bağlayıcının kilitlerini döndürür. Salt-okunur [IConnectorLock](../../com.aspose.slides/iconnectorlock).

**Döndürür:**
[IConnectorLock](../../com.aspose.slides/iconnectorlock)
### getStartShapeConnectedTo() {#getStartShapeConnectedTo--}
```
public abstract IShape getStartShapeConnectedTo()
```


Bağlayıcının başlangıcını bağlamak için şekli döndürür veya ayarlar. Okunabilir/Yazılabilir [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)
### setStartShapeConnectedTo(IShape value) {#setStartShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setStartShapeConnectedTo(IShape value)
```


Bağlayıcının başlangıcını bağlamak için şekli döndürür veya ayarlar. Okunabilir/Yazılabilir [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getEndShapeConnectedTo() {#getEndShapeConnectedTo--}
```
public abstract IShape getEndShapeConnectedTo()
```


Bağlayıcının sonunu bağlamak için şekli döndürür veya ayarlar. Okunabilir/Yazılabilir [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)
### setEndShapeConnectedTo(IShape value) {#setEndShapeConnectedTo-com.aspose.slides.IShape-}
```
public abstract void setEndShapeConnectedTo(IShape value)
```


Bağlayıcının sonunu bağlamak için şekli döndürür veya ayarlar. Okunabilir/Yazılabilir [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |
### getStartShapeConnectionSiteIndex() {#getStartShapeConnectionSiteIndex--}
```
public abstract long getStartShapeConnectionSiteIndex()
```


Başlangıç şekli için bağlantı noktasının indeksini döndürür veya ayarlar. Okunabilir/Yazılabilir long.

**Döndürür:**
long
### setStartShapeConnectionSiteIndex(long value) {#setStartShapeConnectionSiteIndex-long-}
```
public abstract void setStartShapeConnectionSiteIndex(long value)
```


Başlangıç şekli için bağlantı noktasının indeksini döndürür veya ayarlar. Okunabilir/Yazılabilir long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |
### getEndShapeConnectionSiteIndex() {#getEndShapeConnectionSiteIndex--}
```
public abstract long getEndShapeConnectionSiteIndex()
```


Bitiş şekli için bağlantı noktasının indeksini döndürür veya ayarlar. Okunabilir/Yazılabilir long.

**Döndürür:**
long
### setEndShapeConnectionSiteIndex(long value) {#setEndShapeConnectionSiteIndex-long-}
```
public abstract void setEndShapeConnectionSiteIndex(long value)
```


Bitiş şekli için bağlantı noktasının indeksini döndürür veya ayarlar. Okunabilir/Yazılabilir long.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | long |  |
### reroute() {#reroute--}
```
public abstract void reroute()
```


Bağlayıcıyı, bağladığı şekiller arasında mümkün olan en kısa yolu alacak şekilde yeniden yönlendirir.