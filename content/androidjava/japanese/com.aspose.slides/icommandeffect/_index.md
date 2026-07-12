---
title: ICommandEffect
second_title: Aspose.Slides for Android の Java API リファレンス
description: アニメーション動作のコマンド効果を表します。
type: docs
url: /ja/com.aspose.slides/icommandeffect/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.IBehavior](../../com.aspose.slides/ibehavior)
```
public interface ICommandEffect extends IBehavior
```

アニメーションの動作に対するコマンド効果を表します。
## メソッド

| Method | Description |
| --- | --- |
| [getType()](#getType--) | 動作のコマンド効果タイプを定義します。 |
| [setType(byte value)](#setType-byte-) | 動作のコマンド効果タイプを定義します。 |
| [getCommandString()](#getCommandString--) | コマンド文字列を定義します。 |
| [setCommandString(String value)](#setCommandString-java.lang.String-) | コマンド文字列を定義します。 |
| [getShapeTarget()](#getShapeTarget--) | コマンド効果のシェイプターゲットを定義します。 |
| [setShapeTarget(IShape value)](#setShapeTarget-com.aspose.slides.IShape-) | コマンド効果のシェイプターゲットを定義します。 |
### getType() {#getType--}
```
public abstract byte getType()
```

動作のコマンド効果タイプを定義します。読み取り/書き込み [CommandEffectType](../../com.aspose.slides/commandeffecttype)。

**戻り値:**
byte
### setType(byte value) {#setType-byte-}
```
public abstract void setType(byte value)
```

動作のコマンド効果タイプを定義します。読み取り/書き込み [CommandEffectType](../../com.aspose.slides/commandeffecttype)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | byte |  |

### getCommandString() {#getCommandString--}
```
public abstract String getCommandString()
```

コマンド文字列を定義します。読み取り/書き込み String。

**戻り値:**
java.lang.String
### setCommandString(String value) {#setCommandString-java.lang.String-}
```
public abstract void setCommandString(String value)
```

コマンド文字列を定義します。読み取り/書き込み String。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |

### getShapeTarget() {#getShapeTarget--}
```
public abstract IShape getShapeTarget()
```

コマンド効果のシェイプターゲットを定義します。読み取り/書き込み [IShape](../../com.aspose.slides/ishape)。

**戻り値:**
[IShape](../../com.aspose.slides/ishape)
### setShapeTarget(IShape value) {#setShapeTarget-com.aspose.slides.IShape-}
```
public abstract void setShapeTarget(IShape value)
```

コマンド効果のシェイプターゲットを定義します。読み取り/書き込み [IShape](../../com.aspose.slides/ishape)。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | [IShape](../../com.aspose.slides/ishape) |  |