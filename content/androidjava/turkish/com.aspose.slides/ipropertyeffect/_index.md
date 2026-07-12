---
title: IPropertyEffect
second_title: Aspose.Slides Android için Java API Referansı
description: Özellik etkisi davranışını temsil eder.
type: docs
url: /tr/com.aspose.slides/ipropertyeffect/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface IPropertyEffect extends IBehavior
```

Represent property effect behavior.
## Metotlar

| Metot | Açıklama |
| --- | --- |
| [getFrom()](#getFrom--) | Animasyonun başlangıç değerini belirtir. |
| [setFrom(String value)](#setFrom-java.lang.String-) | Animasyonun başlangıç değerini belirtir. |
| [getTo()](#getTo--) | Animasyonun bitiş değerini belirtir. |
| [setTo(String value)](#setTo-java.lang.String-) | Animasyonun bitiş değerini belirtir. |
| [getBy()](#getBy--) | Animasyonun başlangıçtan önceki konumuna göre göreli bir ofset değerini belirtir. |
| [setBy(String value)](#setBy-java.lang.String-) | Animasyonun başlangıçtan önceki konumuna göre göreli bir ofset değerini belirtir. |
| [getValueType()](#getValueType--) | Bir özelliğin değerinin türünü belirtir. |
| [setValueType(int value)](#setValueType-int-) | Bir özelliğin değerinin türünü belirtir. |
| [getCalcMode()](#getCalcMode--) | Animasyon için ara değerleme modunu belirtir Okunur/Yazılabilir [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [setCalcMode(int value)](#setCalcMode-int-) | Animasyon için ara değerleme modunu belirtir Okunur/Yazılabilir [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype). |
| [getPoints()](#getPoints--) | Animasyonun noktalarını belirtir. |
| [setPoints(IPointCollection value)](#setPoints-com.aspose.slides.IPointCollection-) | Animasyonun noktalarını belirtir. |
### getFrom() {#getFrom--}
```
public abstract String getFrom()
```

Animasyonun başlangıç değerini belirtir. Okunur/Yazılabilir String.

**Döndürür:**
java.lang.String
### setFrom(String value) {#setFrom-java.lang.String-}
```
public abstract void setFrom(String value)
```

Animasyonun başlangıç değerini belirtir. Okunur/Yazılabilir String.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getTo() {#getTo--}
```
public abstract String getTo()
```

Animasyonun bitiş değerini belirtir. Okunur/Yazılabilir String.

**Döndürür:**
java.lang.String
### setTo(String value) {#setTo-java.lang.String-}
```
public abstract void setTo(String value)
```

Animasyonun bitiş değerini belirtir. Okunur/Yazılabilir String.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getBy() {#getBy--}
```
public abstract String getBy()
```

Animasyonun başlangıçtan önceki konumuna göre göreli bir ofset değerini belirtir. Okunur/Yazılabilir String.

**Döndürür:**
java.lang.String
### setBy(String value) {#setBy-java.lang.String-}
```
public abstract void setBy(String value)
```

Animasyonun başlangıçtan önceki konumuna göre göreli bir ofset değerini belirtir. Okunur/Yazılabilir String.

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getValueType() {#getValueType--}
```
public abstract int getValueType()
```

Bir özelliğin değerinin türünü belirtir Okunur/Yazılabilir [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**Döndürür:**
int
### setValueType(int value) {#setValueType-int-}
```
public abstract void setValueType(int value)
```

Bir özelliğin değerinin türünü belirtir Okunur/Yazılabilir [PropertyValueType](../../com.aspose.slides/propertyvaluetype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getCalcMode() {#getCalcMode--}
```
public abstract int getCalcMode()
```

Animasyon için ara değerleme modunu belirtir Okunur/Yazılabilir [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**Döndürür:**
int
### setCalcMode(int value) {#setCalcMode-int-}
```
public abstract void setCalcMode(int value)
```

Animasyon için ara değerleme modunu belirtir Okunur/Yazılabilir [PropertyCalcModeType](../../com.aspose.slides/propertycalcmodetype).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getPoints() {#getPoints--}
```
public abstract IPointCollection getPoints()
```

Animasyonun noktalarını belirtir Okunur/Yazılabilir [IPointCollection](../../com.aspose.slides/ipointcollection).

**Döndürür:**
[IPointCollection](../../com.aspose.slides/ipointcollection)
### setPoints(IPointCollection value) {#setPoints-com.aspose.slides.IPointCollection-}
```
public abstract void setPoints(IPointCollection value)
```

Animasyonun noktalarını belirtir Okunur/Yazılabilir [IPointCollection](../../com.aspose.slides/ipointcollection).

**Parametreler:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [IPointCollection](../../com.aspose.slides/ipointcollection) |  |