---
title: ICommandEffect
second_title: Aspose.Slides for Android a Java API referencián keresztül
description: Parancs hatást reprezentál egy animációs viselkedéshez.
type: docs
url: /hu/com.aspose.slides/icommandeffect/
---
**Minden megvalósított interfész:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

Parancs hatást reprezentál egy animációs viselkedéshez.
## Módszerek

| Módszer | Leírás |
| --- | --- |
| [getType()](#getType--) | Meghatározza a parancs hatás típusát a viselkedéshez. |
| [setType(byte value)](#setType-byte-) | Meghatározza a parancs hatás típusát a viselkedéshez. |
| [getCommandString()](#getCommandString--) | Meghatározza a parancs karakterláncot. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | Meghatározza a parancs karakterláncot. |
| [getShapeTarget()](#getShapeTarget--) | Meghatározza a parancs hatás alakzat célját. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | Meghatározza a parancs hatás alakzat célját. |
### getType() {#getType--}
```
public abstract byte getType()
```

Meghatározza a parancs hatás típusát a viselkedéshez. Olvasás/írás [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Visszatér:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Meghatározza a parancs hatás típusát a viselkedéshez. Olvasás/írás [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | byte |  |

### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

Meghatározza a parancs karakterláncot. Olvasás/írás String.

**Visszatér:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

Meghatározza a parancs karakterláncot. Olvasás/írás String.

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | java.lang.String |  |

### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

Meghatározza a parancs hatás alakzat célját. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Visszatér:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

Meghatározza a parancs hatás alakzat célját. Olvasás/írás [IShape](../../com.aspose.slides/ishape).

**Paraméterek:**
| Paraméter | Típus | Leírás |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |