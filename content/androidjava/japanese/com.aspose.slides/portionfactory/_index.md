---
title: PortionFactory
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: テスト部分の作成を可能にします
type: docs
url: /ja/com.aspose.slides/portionfactory/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IPortionFactory](../../com.aspose.slides/iportionfactory)
```
public class PortionFactory implements IPortionFactory
```

テスト部分を作成できます

--------------------

COM 互換性のため
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [PortionFactory()](#PortionFactory--) |  |
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createPortion()](#createPortion--) | 空のテキスト部分を作成します。 |
| [createPortion(String str)](#createPortion-java.lang.String-) | 指定された文字列からテキスト部分を作成します。 |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | 指定された部分データを使用して部分を作成します。 |
### PortionFactory() {#PortionFactory--}
```
public PortionFactory()
```


### createPortion() {#createPortion--}
```
public final IPortion createPortion()
```


空のテキスト部分を作成します。

**戻り値:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public final IPortion createPortion(String str)
```


指定された文字列からテキスト部分を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| str | java.lang.String | 文字列。 |

**戻り値:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(IPortion portion) {#createPortion-com.aspose.slides.IPortion-}
```
public final IPortion createPortion(IPortion portion)
```


指定された部分データを使用して部分を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | 使用する部分。 |

**戻り値:**
[IPortion](../../com.aspose.slides/iportion) - Portion.