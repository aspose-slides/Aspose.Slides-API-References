---
title: ICommandEffect
second_title: Aspose.Slides für Java API-Referenz
description: Stellt einen Befehls-Effekt für ein Animationsverhalten dar.
type: docs
url: /de/com.aspose.slides/icommandeffect/
---
**Alle implementierten Schnittstellen:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

Stellt einen Befehls-Effekt für ein Animationsverhalten dar.
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getType()](#getType--) | Definiert den Befehlseffekttyp des Verhaltens. |
| [setType(byte value)](#setType-byte-) | Definiert den Befehlseffekttyp des Verhaltens. |
| [getCommandString()](#getCommandString--) | Definiert die Befehlszeichenfolge. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | Definiert die Befehlszeichenfolge. |
| [getShapeTarget()](#getShapeTarget--) | Definiert das Zielobjekt des Befehls-Effekts. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | Definiert das Zielobjekt des Befehls-Effekts. |
### getType() {#getType--}
```
public abstract byte getType()
```

Definiert den Befehlseffekttyp des Verhaltens. Lesen/Schreiben [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Rückgabewert:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Definiert den Befehlseffekttyp des Verhaltens. Lesen/Schreiben [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | byte |  |

### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

Definiert die Befehlszeichenfolge. Lesen/Schreiben String.

**Rückgabewert:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

Definiert die Befehlszeichenfolge. Lesen/Schreiben String.

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | java.lang.String |  |

### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

Definiert das Zielobjekt des Befehls-Effekts. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Rückgabewert:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

Definiert das Zielobjekt des Befehls-Effekts. Lesen/Schreiben [IShape](../../com.aspose.slides/ishape).

**Parameter:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |