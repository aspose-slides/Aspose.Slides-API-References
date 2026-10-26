---
title: IFontScheme
second_title: Aspose.Slides for Android via Java API Reference
description: テーマで定義されたフォントを格納します。
type: docs
url: /ja/com.aspose.slides/ifontscheme/
---```
public interface IFontScheme
```

テーマで定義されたフォントを格納します。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMinor()](#getMinor--) | スライドの "body" 部分のフォント コレクションを返します。 |
| [getMajor()](#getMajor--) | スライドの "heading" 部分のフォント コレクションを返します。 |
| [getName()](#getName--) | フォント スキームの名前を返します。 |
| [setName(String value)](#setName-java.lang.String-) | フォント スキームの名前を返します。 |

### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```

スライドの "body" 部分のフォント コレクションを返します。読み取り専用 [IFonts](../../com.aspose.slides/ifonts).

**戻り値:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```

スライドの "heading" 部分のフォント コレクションを返します。読み取り専用 [IFonts](../../com.aspose.slides/ifonts).

**戻り値:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```

フォント スキームの名前を返します。読み書き可能 String.

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```

フォント スキームの名前を返します。読み書き可能 String.

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |