---
title: ICommandEffect
second_title: Java API Referansı aracılığıyla Android için Aspose.Slides
description: Bir animasyon davranışı için komut etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/icommandeffect/
---
**All Implemented Interfaces:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

Represents a command effect for an animation behavior.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Davranışın komut etkisi türünü tanımlar. |
| [setType(byte value)](#setType-byte-) | Davranışın komut etkisi türünü tanımlar. |
| [getCommandString()](#getCommandString--) | Komut dizesini tanımlar. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | Komut dizesini tanımlar. |
| [getShapeTarget()](#getShapeTarget--) | Komut etkisinin şekil hedefini tanımlar. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | Komut etkisinin şekil hedefini tanımlar. |
### getType() {#getType--}
```
public abstract byte getType()
```

Defines command effect type of behavior. Read/write [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Returns:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Defines command effect type of behavior. Read/write [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

Defines command string. Read/write String.

**Returns:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

Defines command string. Read/write String.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

Defines shape target of command effect. Read/write [IShape](../../com.aspose.slides/ishape).

**Returns:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

Defines shape target of command effect. Read/write [IShape](../../com.aspose.slides/ishape).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |