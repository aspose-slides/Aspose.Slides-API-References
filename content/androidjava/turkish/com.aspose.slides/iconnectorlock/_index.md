---
title: IConnectorLock
second_title: Aspose.Slides for Android via Java API Referansı
description: Üst Connector'da hangi işlemlerin devre dışı bırakıldığını belirler.
type: docs
url: /tr/com.aspose.slides/iconnectorlock/
---
**Uygulanan Tüm Arayüzler:**
[com.aspose.slides.IBaseShapeLock](../../com.aspose.slides/ibaseshapelock)
```
public interface IConnectorLock extends IBaseShapeLock
```

Üst Bağlayıcıda hangi işlemlerin devre dışı bırakıldığını belirler.
## Metotlar

| Method | Description |
| --- | --- |
| [getGroupingLocked()](#getGroupingLocked--) | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. |
| [setGroupingLocked(boolean value)](#setGroupingLocked-boolean-) | Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. |
| [getSelectLocked()](#getSelectLocked--) | Bu şeklin seçilmesinin yasak olup olmadığını belirler. |
| [setSelectLocked(boolean value)](#setSelectLocked-boolean-) | Bu şeklin seçilmesinin yasak olup olmadığını belirler. |
| [getRotateLocked()](#getRotateLocked--) | Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. |
| [setRotateLocked(boolean value)](#setRotateLocked-boolean-) | Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. |
| [getAspectRatioLocked()](#getAspectRatioLocked--) | Bu şeklin yeniden boyutlandırılırken en-boy oranını koruması gerekip gerekmediğini belirler. |
| [setAspectRatioLocked(boolean value)](#setAspectRatioLocked-boolean-) | Bu şeklin yeniden boyutlandırılırken en-boy oranını koruması gerekip gerekmediğini belirler. |
| [getPositionMove()](#getPositionMove--) | Bu şeklin taşınmasının yasak olup olmadığını belirler. |
| [setPositionMove(boolean value)](#setPositionMove-boolean-) | Bu şeklin taşınmasının yasak olup olmadığını belirler. |
| [getSizeLocked()](#getSizeLocked--) | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. |
| [setSizeLocked(boolean value)](#setSizeLocked-boolean-) | Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. |
| [getEditPointsLocked()](#getEditPointsLocked--) | Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. |
| [setEditPointsLocked(boolean value)](#setEditPointsLocked-boolean-) | Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. |
| [getAdjustHandlesLocked()](#getAdjustHandlesLocked--) | Ayar değerlerinin değiştirilmesinin yasak olup olmadığını belirler. |
| [setAdjustHandlesLocked(boolean value)](#setAdjustHandlesLocked-boolean-) | Ayar değerlerinin değiştirilmesinin yasak olup olmadığını belirler. |
| [getArrowheadsLocked()](#getArrowheadsLocked--) | Ok başlıklarının değiştirilmesinin yasak olup olmadığını belirler. |
| [setArrowheadsLocked(boolean value)](#setArrowheadsLocked-boolean-) | Ok başlıklarının değiştirilmesinin yasak olup olmadığını belirler. |
| [getShapeTypeLocked()](#getShapeTypeLocked--) | Şekil tipinin değiştirilmesinin yasak olup olmadığını belirler. |
| [setShapeTypeLocked(boolean value)](#setShapeTypeLocked-boolean-) | Şekil tipinin değiştirilmesinin yasak olup olmadığını belirler. |

### getGroupingLocked() {#getGroupingLocked--}
```
public abstract boolean getGroupingLocked()
```

Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setGroupingLocked(boolean value) {#setGroupingLocked-boolean-}
```
public abstract void setGroupingLocked(boolean value)
```

Bu şeklin bir gruba eklenmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSelectLocked() {#getSelectLocked--}
```
public abstract boolean getSelectLocked()
```

Bu şeklin seçilmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setSelectLocked(boolean value) {#setSelectLocked-boolean-}
```
public abstract void setSelectLocked(boolean value)
```

Bu şeklin seçilmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getRotateLocked() {#getRotateLocked--}
```
public abstract boolean getRotateLocked()
```

Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setRotateLocked(boolean value) {#setRotateLocked-boolean-}
```
public abstract void setRotateLocked(boolean value)
```

Bu şeklin döndürme açısının değiştirilmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAspectRatioLocked() {#getAspectRatioLocked--}
```
public abstract boolean getAspectRatioLocked()
```

Bu şeklin yeniden boyutlandırılırken en-boy oranını koruması gerekip gerekmediğini belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setAspectRatioLocked(boolean value) {#setAspectRatioLocked-boolean-}
```
public abstract void setAspectRatioLocked(boolean value)
```

Bu şeklin yeniden boyutlandırılırken en-boy oranını koruması gerekip gerekmediğini belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getPositionMove() {#getPositionMove--}
```
public abstract boolean getPositionMove()
```

Bu şeklin taşınmasının yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setPositionMove(boolean value) {#setPositionMove-boolean-}
```
public abstract void setPositionMove(boolean value)
```

Bu şeklin taşınmasının yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getSizeLocked() {#getSizeLocked--}
```
public abstract boolean getSizeLocked()
```

Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setSizeLocked(boolean value) {#setSizeLocked-boolean-}
```
public abstract void setSizeLocked(boolean value)
```

Bu şeklin yeniden boyutlandırılmasının yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getEditPointsLocked() {#getEditPointsLocked--}
```
public abstract boolean getEditPointsLocked()
```

Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setEditPointsLocked(boolean value) {#setEditPointsLocked-boolean-}
```
public abstract void setEditPointsLocked(boolean value)
```

Bu şeklin konturunun doğrudan değiştirilmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getAdjustHandlesLocked() {#getAdjustHandlesLocked--}
```
public abstract boolean getAdjustHandlesLocked()
```

Ayar değerlerinin değiştirilmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setAdjustHandlesLocked(boolean value) {#setAdjustHandlesLocked-boolean-}
```
public abstract void setAdjustHandlesLocked(boolean value)
```

Ayar değerlerinin değiştirilmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getArrowheadsLocked() {#getArrowheadsLocked--}
```
public abstract boolean getArrowheadsLocked()
```

Ok başlıklarının değiştirilmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setArrowheadsLocked(boolean value) {#setArrowheadsLocked-boolean-}
```
public abstract void setArrowheadsLocked(boolean value)
```

Ok başlıklarının değiştirilmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |

### getShapeTypeLocked() {#getShapeTypeLocked--}
```
public abstract boolean getShapeTypeLocked()
```

Şekil tipinin değiştirilmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Döndürür:**
boolean
### setShapeTypeLocked(boolean value) {#setShapeTypeLocked-boolean-}
```
public abstract void setShapeTypeLocked(boolean value)
```

Şekil tipinin değiştirilmesinin yasak olup olmadığını belirler. Okunur/yazılabilir boolean.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | boolean |  |