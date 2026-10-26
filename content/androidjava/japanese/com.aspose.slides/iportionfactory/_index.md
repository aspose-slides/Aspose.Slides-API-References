---
title: IPortionFactory
second_title: Aspose.Slides for Android via Java API Reference
description: Allows to create test portions
type: docs
url: /ja/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

テスト部分を作成できます

--------------------

COM 互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createPortion()](#createPortion--) | 空のテキスト部分を作成します。 |
| [createPortion(String str)](#createPortion-java.lang.String-) | 指定された文字列からテキスト部分を作成します。 |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | 指定された部分データを使用して部分を作成します。 |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


空のテキスト部分を作成します。

**戻り値:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
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
public abstract IPortion createPortion(IPortion portion)
```


指定された部分データを使用して部分を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | 使用する部分。 |

**戻り値:**  
[IPortion](../../com.aspose.slides/iportion) - Portion.