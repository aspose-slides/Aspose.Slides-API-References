---
title: ICommandEffect
second_title: Riferimento API di Aspose.Slides per Java
description: Rappresenta un effetto di comando per un comportamento di animazione.
type: docs
url: /it/com.aspose.slides/icommandeffect/
---
**Tutte le interfacce implementate:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

Rappresenta un effetto di comando per un comportamento di animazione.
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Definisce il tipo di effetto del comando del comportamento. |
| [setType(byte value)](#setType-byte-) | Definisce il tipo di effetto del comando del comportamento. |
| [getCommandString()](#getCommandString--) | Definisce la stringa del comando. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | Definisce la stringa del comando. |
| [getShapeTarget()](#getShapeTarget--) | Definisce l'obiettivo della forma dell'effetto del comando. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | Definisce l'obiettivo della forma dell'effetto del comando. |
### getType() {#getType--}
```
public abstract byte getType()
```

Definisce il tipo di effetto del comando del comportamento. Lettura/scrittura [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Restituisce:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Definisce il tipo di effetto del comando del comportamento. Lettura/scrittura [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | byte |  |
### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

Definisce la stringa del comando. Lettura/scrittura String.

**Restituisce:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

Definisce la stringa del comando. Lettura/scrittura String.

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | java.lang.String |  |
### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

Definisce l'obiettivo della forma dell'effetto del comando. Lettura/scrittura [IShape](../../com.aspose.slides/ishape).

**Restituisce:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

Definisce l'obiettivo della forma dell'effetto del comando. Lettura/scrittura [IShape](../../com.aspose.slides/ishape).

**Parametri:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |