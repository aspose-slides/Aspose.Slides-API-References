---
title: ICommandEffect
second_title: Aspose.Slides Java API referencia
description: Egy animációs viselkedés parancs hatását reprezentálja.
type: docs
url: /hu/com.aspose.slides/icommandeffect/
---
**Minden implementált interfész:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

Egy animációs viselkedés parancs hatását reprezentálja.
## Metódusok

| Metódus | Leírás |
| --- | --- |
| [getType()](#getType--) | Meghatározza a viselkedés parancshatás típusát. |
| [setType(byte value)](#setType-byte-) | Meghatározza a viselkedés parancshatás típusát. |
| [getCommandString()](#getCommandString--) | Meghatározza a parancs karakterláncát. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | Meghatározza a parancs karakterláncát. |
| [getShapeTarget()](#getShapeTarget--) | Meghatározza a parancshatás alakzatcélját. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | Meghatározza a parancshatás alakzatcélját. |
### getType() {#getType--}
```
public abstract byte getType()
```

Meghatározza a viselkedés parancshatás típusát. Olvasás/írás [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Visszatér:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Meghatározza a viselkedés parancshatás típusát. Olvasás/írás [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |
### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

Meghatározza a parancs karakterláncát. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

Meghatározza a parancs karakterláncát. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |
### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

Meghatározza a parancshatás alakzatcélját. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Visszatér:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

Meghatározza a parancshatás alakzatcélját. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |