---
title: FontScheme
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: テーマで定義されたフォントを格納します。
type: docs
url: /ja/com.aspose.slides/fontscheme/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.IFontScheme](../../com.aspose.slides/ifontscheme), com.aspose.slides.IDOMObject
```
public class FontScheme implements IFontScheme, IDOMObject
```

テーマで定義されたフォントを格納します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getMinor()](#getMinor--) | スライドの「body」部分のフォントコレクションを返します。 |
| [getMajor()](#getMajor--) | スライドの「heading」部分のフォントコレクションを返します。 |
| [getName()](#getName--) | フォントスキーム名を返します。 |
| [setName(String value)](#setName-java.lang.String-) | フォントスキーム名を返します。 |
| [getParent_Immediate()](#getParent-Immediate--) |  |
### getMinor() {#getMinor--}
```
public final IFonts getMinor()
```


スライドの「body」部分のフォントコレクションを返します。読み取り専用 [IFonts](../../com.aspose.slides/ifonts)。

**戻り値:**
[IFonts](../../com.aspose.slides/ifonts)
### getMajor() {#getMajor--}
```
public final IFonts getMajor()
```


スライドの「heading」部分のフォントコレクションを返します。読み取り専用 [IFonts](../../com.aspose.slides/ifonts)。

**戻り値:**
[IFonts](../../com.aspose.slides/ifonts)
### getName() {#getName--}
```
public final String getName()
```


フォントスキーム名を返します。読み書き可能 String。

**戻り値:**
java.lang.String
### setName(String value) {#setName-java.lang.String-}
```
public final void setName(String value)
```


フォントスキーム名を返します。読み書き可能 String。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String |  |
### getParent_Immediate() {#getParent-Immediate--}
```
public final IDOMObject getParent_Immediate()
```


Parent_Immediate オブジェクトを返します。読み取り専用 IDOMObject。

**戻り値:**
com.aspose.slides.IDOMObject