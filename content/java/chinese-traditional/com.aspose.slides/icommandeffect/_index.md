---
title: ICommandEffect
second_title: Aspose.Slides for Java API 參考
description: 表示動畫行為的命令效果。
type: docs
url: /zh-hant/com.aspose.slides/icommandeffect/
---
**所有已實作的介面：**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

表示動畫行為的命令效果。  
## 方法

| 方法 | 描述 |
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

定義行為的命令效果類型。可讀寫 [CommandEffectType](../../com.aspose.slides/commandeffecttype)。

**傳回值：**  
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

定義行為的命令效果類型。可讀寫 [CommandEffectType](../../com.aspose.slides/commandeffecttype)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |

### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

定義命令字串。可讀寫 String。

**傳回值：**  
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

定義命令字串。可讀寫 String。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

定義命令效果的形狀目標。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**傳回值：**  
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

定義命令效果的形狀目標。可讀寫 [IShape](../../com.aspose.slides/ishape)。

**參數：**  
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |