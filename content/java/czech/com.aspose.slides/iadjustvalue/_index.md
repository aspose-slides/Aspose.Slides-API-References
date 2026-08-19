---
title: IAdjustValue
second_title: Aspose.Slides for Java API Reference
description: Representuje hodnotu úpravy geometrického tvaru.
type: docs
url: /cs/com.aspose.slides/iadjustvalue/
---```
public interface IAdjustValue
```

Representuje hodnotu úpravy geometrického tvaru. Tyto hodnoty ovlivňují tvar.

## Metody

| Method | Description |
| --- | --- |
| [getRawValue()](#getRawValue--) | Vrací nebo nastavuje hodnotu úpravy "tak, jak je". |
| [setRawValue(long value)](#setRawValue-long-) | Vrací nebo nastavuje hodnotu úpravy "tak, jak je". |
| [getAngleValue()](#getAngleValue--) | Vrací nebo nastavuje hodnotu, která je interpretována jako úhel ve stupních. |
| [setAngleValue(float value)](#setAngleValue-float-) | Vrací nebo nastavuje hodnotu, která je interpretována jako úhel ve stupních. |
| [getName()](#getName--) | Vrací název této hodnoty úpravy. |
| [getType()](#getType--) | Vrací typ úpravy tvaru. |
### getRawValue() {#getRawValue--}
```
public abstract long getRawValue()
```


Vrací nebo nastavuje hodnotu úpravy "tak, jak je". Čtení/zápis long.

**Vrací:**
long
### setRawValue(long value) {#setRawValue-long-}
```
public abstract void setRawValue(long value)
```


Vrací nebo nastavuje hodnotu úpravy "tak, jak je". Čtení/zápis long.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | long |  |

### getAngleValue() {#getAngleValue--}
```
public abstract float getAngleValue()
```


Vrací nebo nastavuje hodnotu, která je interpretována jako úhel ve stupních. Čtení/zápis float.

**Vrací:**
float
### setAngleValue(float value) {#setAngleValue-float-}
```
public abstract void setAngleValue(float value)
```


Vrací nebo nastavuje hodnotu, která je interpretována jako úhel ve stupních. Čtení/zápis float.

**Parametry:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float |  |

### getName() {#getName--}
```
public abstract String getName()
```


Vrací název této hodnoty úpravy. Pouze pro čtení String.

**Vrací:**
java.lang.String
### getType() {#getType--}
```
public abstract int getType()
```


Vrací typ úpravy tvaru. Pouze pro čtení [ShapeAdjustmentType](../../com.aspose.slides/shapeadjustmenttype).

**Vrací:**
int