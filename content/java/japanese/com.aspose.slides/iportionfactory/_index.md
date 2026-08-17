---
title: IPortionFactory
second_title: Aspose.Slides for Java API Reference
description: テスト Portion を作成できます
type: docs
url: /ja/com.aspose.slides/iportionfactory/
---```
public interface IPortionFactory
```

テスト Portion を作成できます

--------------------

COM互換性のため
## メソッド

| メソッド | 説明 |
| --- | --- |
| [createPortion()](#createPortion--) | 空のテキスト Portion を作成します。 |
| [createPortion(String str)](#createPortion-java.lang.String-) | 指定された文字列からテキスト Portion を作成します。 |
| [createPortion(IPortion portion)](#createPortion-com.aspose.slides.IPortion-) | 指定された Portion データを使用して Portion を作成します。 |
### createPortion() {#createPortion--}
```
public abstract IPortion createPortion()
```


空のテキスト Portion を作成します。

**戻り値:**
[IPortion](../../com.aspose.slides/iportion) - Portion.
### createPortion(String str) {#createPortion-java.lang.String-}
```
public abstract IPortion createPortion(String str)
```


指定された文字列からテキスト Portion を作成します。

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


指定された Portion データを使用して Portion を作成します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| portion | [IPortion](../../com.aspose.slides/iportion) | 使用する Portion。 |

**戻り値:**
[IPortion](../../com.aspose.slides/iportion) - Portion.