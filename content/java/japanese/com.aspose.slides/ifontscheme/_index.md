---
title: IFontScheme
second_title: Aspose.Slides for Java API Reference
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
| [getMinor()](#getMinor--) | スライドの「本文」部分のフォントコレクションを返します。 |
| [getMajor()](#getMajor--) | スライドの「見出し」部分のフォントコレクションを返します。 |
| [getName()](#getName--) | フォントスキーム名を返します。 |
| [setName(String value)](#setName-java.lang.String-) | フォントスキーム名を返します。 |
### getMinor() {#getMinor--}
```
public abstract IFonts getMinor()
```


スライドの「本文」部分のフォントコレクションを返します。 読み取り専用 [IFonts](../../com.aspose.slides/ifonts)。

**戻り値:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public abstract IFonts getMajor()
```


スライドの「見出し」部分のフォントコレクションを返します。 読み取り専用 [IFonts](../../com.aspose.slides/ifonts)。

**戻り値:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public abstract String getName()
```


フォントスキーム名を返します。 読み取り/書き込み String。

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public abstract void setName(String value)
```


フォントスキーム名を設定します。 読み取り/書き込み String。

**パラメーター:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |