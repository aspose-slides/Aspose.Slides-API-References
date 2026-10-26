---
title: ICommandEffect
second_title: Справочник API Aspose.Slides для Java
description: Представляет эффект команды для поведения анимации.
type: docs
url: /ru/com.aspose.slides/icommandeffect/
---
**Все реализованные интерфейсы:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

Представляет эффект команды для поведения анимации.
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Defines command effect type of behavior. |
| [setType(byte value)](#setType-byte-) | Defines command effect type of behavior. |
| [getCommandString()](#getCommandString--) | Defines command string. |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | Defines command string. |
| [getShapeTarget()](#getShapeTarget--) | Defines shape target of command effect. |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | Defines shape target of command effect. |
### getType() {#getType--}
```
public abstract byte getType()
```

Определяет тип эффекта команды поведения. Чтение/запись [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Возвращаемое значение:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

Определяет тип эффекта команды поведения. Чтение/запись [CommandEffectType](../../com.aspose.slides/commandeffecttype).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte |  |

### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

Определяет строку команды. Чтение/запись String.

**Возвращаемое значение:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

Определяет строку команды. Чтение/запись String.

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

Определяет целевую форму эффекта команды. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Возвращаемое значение:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

Определяет целевую форму эффекта команды. Чтение/запись [IShape](../../com.aspose.slides/ishape).

**Параметры:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |