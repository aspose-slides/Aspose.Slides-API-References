---
title: IHtmlGenerator
second_title: Aspose.Slides for Android via Java API Reference
description: Html generator.
type: docs
url: /ja/com.aspose.slides/ihtmlgenerator/
---```
public interface IHtmlGenerator
```

HTML ジェネレータ。

## メソッド

| メソッド | 説明 |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | フォーマットされた HTML テキストを追加します。 |
| [addHtml(char[] html)](#addHtml-char---) | フォーマットされた HTML テキストを追加します。 |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | フォーマットされた HTML テキストを追加します。 |
| [addText(String text)](#addText-java.lang.String-) | 特殊文字を HTML エンティティに置き換えてプレーンテキストを HTML ファイルに追加します。 |
| [addText(char[] text)](#addText-char---) | 特殊文字を HTML エンティティに置き換えてプレーンテキストを HTML ファイルに追加します。 |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | 特殊文字を HTML エンティティに置き換えてプレーンテキストを HTML ファイルに追加します。 |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | 属性値をクォートして HTML ファイルに追加します。 |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | 属性値をクォートして HTML ファイルに追加します。 |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | 属性値をクォートして HTML ファイルに追加します。 |
| [getSlideImageSize()](#getSlideImageSize--) | スライド画像サイズを返します。 |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | スライド画像サイズが指定される単位を返します。 |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | スライド画像サイズが指定される単位の CSS コードを返します。 |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | 前回レンダリングされたスライドのインデックスを返します。最初のスライドがレンダリング中の場合は -1 を返します。 |
| [getSlideIndex()](#getSlideIndex--) | 現在レンダリング中のスライドのインデックスを返します。 |
| [getNextSlideIndex()](#getNextSlideIndex--) | 現在のスライドの次にレンダリングされるスライドのインデックスを返します。最後のスライドが現在レンダリング中の場合は -1 を返します。 |

### addHtml(String html) {#addHtml-java.lang.String-}
```
public abstract void addHtml(String html)
```

フォーマットされた HTML テキストを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| html | java.lang.String | 追加するテキスト。 |

### addHtml(char[] html) {#addHtml-char---}
```
public abstract void addHtml(char[] html)
```

フォーマットされた HTML テキストを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| html | char[] | 追加するテキスト。 |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public abstract void addHtml(char[] html, int startIndex, int length)
```

フォーマットされた HTML テキストを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| html | char[] | 追加するテキスト。 |
| startIndex | int | 追加する部分の開始インデックス。 |
| length | int | 追加する部分の長さ。 |

### addText(String text) {#addText-java.lang.String-}
```
public abstract void addText(String text)
```

特殊文字を HTML エンティティに置き換えてプレーンテキストを HTML ファイルに追加します。改行や空白は置き換えられません。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 追加するテキスト。 |

### addText(char[] text) {#addText-char---}
```
public abstract void addText(char[] text)
```

特殊文字を HTML エンティティに置き換えてプレーンテキストを HTML ファイルに追加します。改行や空白は置き換えられません。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | char[] | 追加するテキスト。 |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public abstract void addText(char[] text, int startIndex, int length)
```

特殊文字を HTML エンティティに置き換えてプレーンテキストを HTML ファイルに追加します。改行や空白は置き換えられません。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | char[] | 追加するテキスト。 |
| startIndex | int | 追加する部分の開始インデックス。 |
| length | int | 追加する部分の長さ。 |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public abstract void addAttributeValue(String value)
```

属性値をクォートして HTML ファイルに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | 属性値文字列。 |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public abstract void addAttributeValue(char[] value)
```

属性値をクォートして HTML ファイルに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char[] | 属性値文字列。 |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public abstract void addAttributeValue(char[] value, int startIndex, int length)
```

属性値をクォートして HTML ファイルに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char[] | 属性値文字列。 |
| startIndex | int | 追加する部分の開始インデックス。 |
| length | int | 追加する部分の長さ。 |

### getSlideImageSize() {#getSlideImageSize--}
```
public abstract SizeF getSlideImageSize()
```

スライド画像サイズを返します。読み取り専用 [SizeF](../../com.aspose.slides.android/sizef)。

**戻り値:**
[SizeF](../../com.aspose.slides.android/sizef)

### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public abstract int getSlideImageSizeUnit()
```

スライド画像サイズが指定される単位を返します。読み取り専用 [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit)。

**戻り値:**
int

### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public abstract String getSlideImageSizeUnitCode()
```

スライド画像サイズが指定される単位の CSS コードを返します。読み取り専用 String。

**戻り値:**
java.lang.String

### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public abstract int getPreviousSlideIndex()
```

前回レンダリングされたスライドのインデックスを返します。最初のスライドがレンダリング中の場合は -1 を返します。読み取り専用 int。

**戻り値:**
int

### getSlideIndex() {#getSlideIndex--}
```
public abstract int getSlideIndex()
```

現在レンダリング中のスライドのインデックスを返します。読み取り専用 int。

**戻り値:**
int

### getNextSlideIndex() {#getNextSlideIndex--}
```
public abstract int getNextSlideIndex()
```

現在のスライドの次にレンダリングされるスライドのインデックスを返します。最後のスライドが現在レンダリング中の場合は -1 を返します。読み取り専用 int。

**戻り値:**
int