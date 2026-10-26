---
title: IMasterTheme
second_title: Java API を介した Android 用 Aspose.Slides
description: マスターテーマを表します。
type: docs
url: /ja/com.aspose.slides/imastertheme/
---
**実装されているすべてのインターフェイス:**
[com.aspose.slides.ITheme](../../com.aspose.slides/itheme)
```
public interface IMasterTheme extends ITheme
```

マスターテーマを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getExtraColorSchemes()](#getExtraColorSchemes--) | 追加のカラースキームのコレクションを返します。 |
| [getName()](#getName--) | テーマの名前を返します。 |
| [setName(String value)](#setName-java.lang.String-) | テーマの名前を返します。 |
### getExtraColorSchemes() {#getExtraColorSchemes--}
```
public abstract IExtraColorSchemeCollection getExtraColorSchemes()
```

追加のカラースキームのコレクションを返します。これらのスキームはプレゼンテーションの外観に影響せず、スライドのメインカラースキームとして選択できます。読み取り専用 [IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)。

**戻り値:**
[IExtraColorSchemeCollection](../../com.aspose.slides/iextracolorschemecollection)
### getName() {#getName--}
```
public abstract String getName()
```

テーマの名前を返します。 読み書き可能な String。

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

テーマの名前を返します。 読み書き可能な String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |