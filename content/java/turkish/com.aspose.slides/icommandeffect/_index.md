---
title: ICommandEffect
second_title: Aspose.Slides for Java API Referansı
description: Bir animasyon davranışı için komut etkisini temsil eder.
type: docs
url: /tr/com.aspose.slides/icommandeffect/
---
**Uygulanan Tüm Arabirimler:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

Bir animasyon davranışı için komut etkisini temsil eder.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getType()](#getType--) | Davranışın komut etki tipini tanımlar. |
| [setType(byte value)](#setType-byte-) | Davranışın komut etki tipini tanımlar. |
| [getCommandString()](#getCommandString--) | Komut dizesini tanımlar. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | Komut dizesini tanımlar. |
| [getShapeTarget()](#getShapeTarget--) | Komut etkisinin şekil hedefini tanımlar. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | Komut etkisinin şekil hedefini tanımlar. |
### getType() {#getType--}
```
public abstract byte getType()
```

Davranışın komut etki tipini tanımlar. Okunur/yazılır [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Döndürür:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Davranışın komut etki tipini tanımlar. Okunur/yazılır [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | byte |  |
### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

Komut dizesini tanımlar. Okunur/yazılır String.

**Döndürür:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

Komut dizesini tanımlar. Okunur/yazılır String.

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | java.lang.String |  |
### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

Komut etkisinin şekil hedefini tanımlar. Okunur/yazılır [IShape](../../com.aspose.slides/ishape).

**Döndürür:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

Komut etkisinin şekil hedefini tanımlar. Okunur/yazılır [IShape](../../com.aspose.slides/ishape).

**Parametreler:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |