---
title: ICommandEffect
second_title: Aspose.Slides pro Android prostřednictvím Java API Reference
description: Reprezentuje efekt příkazu pro chování animace.
type: docs
url: /cs/com.aspose.slides/icommandeffect/
---
**Všechny implementované rozhraní:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

Reprezentuje efekt příkazu pro chování animace.
## Metody

| Metoda | Popis |
| --- | --- |
| [getType()](#getType--) | Definuje typ efektu příkazu chování. |
| [setType(byte value)](#setType-byte-) | Definuje typ efektu příkazu chování. |
| [getCommandString()](#getCommandString--) | Definuje řetězec příkazu. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | Definuje řetězec příkazu. |
| [getShapeTarget()](#getShapeTarget--) | Definuje cíl tvaru efektu příkazu. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | Definuje cíl tvaru efektu příkazu. |
### getType() {#getType--}
```
public abstract byte getType()
```


Definuje typ efektu příkazu chování. Čtení/zápis [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Vrací:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```


Definuje typ efektu příkazu chování. Čtení/zápis [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | byte |  |

### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```


Definuje řetězec příkazu. Čtení/zápis String.

**Vrací:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```


Definuje řetězec příkazu. Čtení/zápis String.

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | java.lang.String |  |

### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```


Definuje cíl tvaru efektu příkazu. Čtení/zápis [IShape](../../com.aspose.slides/ishape).

**Vrací:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```


Definuje cíl tvaru efektu příkazu. Čtení/zápis [IShape](../../com.aspose.slides/ishape).

**Parametry:**
| Parametr | Typ | Popis |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |