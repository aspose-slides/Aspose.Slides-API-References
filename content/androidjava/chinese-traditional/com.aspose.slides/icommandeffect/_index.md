---
title: ICommandEffect
second_title: Aspose.Slides for Android 透過 Java API 參考
description: 表示動畫行為的指令效果。
type: docs
url: /zh-hant/com.aspose.slides/icommandeffect/
---
**所有已實作的介面：**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

表示動畫行為的指令效果。
## 方法

| 方法 | 說明 |
| --- | --- |
| [getType()](#getType--) | 定義行為的指令效果類型。 |
| [setType(byte value)](#setType-byte-) | 定義行為的指令效果類型。 |
| [getCommandString()](#getCommandString--) | 定義指令字串。 |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | 定義指令字串。 |
| [getShapeTarget()](#getShapeTarget--) | 定義指令效果的形狀目標。 |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | 定義指令效果的形狀目標。 |
### getType() {#getType--}
```
public abstract byte getType()
```

定義行為的指令效果類型。讀寫 [CommandEffectType](../../com.aspose.slides/commandeffecttype)。

**返回：**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

定義行為的指令效果類型。讀寫 [CommandEffectType](../../com.aspose.slides/commandeffecttype)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | byte |  |
### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

定義指令字串。讀寫 String。

**返回：**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

定義指令字串。讀寫 String。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

定義指令效果的形狀目標。讀寫 [IShape](../../com.aspose.slides/ishape)。

**返回：**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

定義指令效果的形狀目標。讀寫 [IShape](../../com.aspose.slides/ishape)。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |