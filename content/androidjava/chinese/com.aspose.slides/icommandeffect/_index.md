---
title: ICommandEffect
second_title: Aspose.Slides for Android via Java API 参考
description: 表示动画行为的命令效果。
type: docs
url: /zh/com.aspose.slides/icommandeffect/
---
**所有实现的接口:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

表示动画行为的命令效果。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getType()](#getType--) | 定义行为的命令效果类型。 |
| [setType(byte value)](#setType-byte-) | 定义行为的命令效果类型。 |
| [getCommandString()](#getCommandString--) | 定义命令字符串。 |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | 定义命令字符串。 |
| [getShapeTarget()](#getShapeTarget--) | 定义命令效果的形状目标。 |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | 定义命令效果的形状目标。 |

### getType() {#getType--}
```
public abstract byte getType()
```

定义行为的命令效果类型。读/写 [CommandEffectType](../../com.aspose.slides/commandeffecttype)。

**返回:**
byte

### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

定义行为的命令效果类型。读/写 [CommandEffectType](../../com.aspose.slides/commandeffecttype)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

定义命令字符串。读/写 String。

**返回:**
java.lang.String

### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

定义命令字符串。读/写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

定义命令效果的形状目标。读/写 [IShape](../../com.aspose.slides/ishape)。

**返回:**
[IShape](../../com.aspose.slides/ishape)

### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

定义命令效果的形状目标。读/写 [IShape](../../com.aspose.slides/ishape)。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |