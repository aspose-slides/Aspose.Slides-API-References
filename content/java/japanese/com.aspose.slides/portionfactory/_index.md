---
title: PortionFactory
second_title: Aspose.Slides for Java API リファレンス
description: テスト用ポーションを作成できます
type: docs
url: /ja/com.aspose.slides/portionfactory/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

テスト用のポーションを作成できます

--------------------

COM 互換性のため
## コンストラクター

| コンストラクター | 説明 |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createPortion()](#createPortion--) | 空のテキストポーションを作成します。 |
| [createPortion(String str)](#createPortion-java.lang.String-) | 指定された文字列からテキストポーションを作成します。 |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | 指定されたポーションデータを使用してポーションを作成します。 |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


空のテキストポーションを作成します。

**戻り値:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


指定された文字列からテキストポーションを作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| str | java.lang.String | 文字列。 |

**戻り値:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
``` 
public final IPortion createPortion(IPortion portion)
```


指定されたポーションデータを使用してポーションを作成します。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | 使用するポーション。 |

**戻り値:**
[IPortion](../../com.aspose.slides/iportion) - Portion.