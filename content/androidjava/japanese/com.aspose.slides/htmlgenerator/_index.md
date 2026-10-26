---
title: HtmlGenerator
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: HTML ジェネレーター。
type: docs
url: /ja/com.aspose.slides/htmlgenerator/
---
**継承:**
java.lang.Object

**実装されたすべてのインターフェイス:**
[com.aspose.slides.IHtmlGenerator](../../com.aspose.slides/ihtmlgenerator)
```
public final class HtmlGenerator implements IHtmlGenerator
```

HTML ジェネレーター。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [addHtml(String html)](#addHtml-java.lang.String-) | フォーマットされたHTMLテキストを追加します。 |
| [addHtml(char[] html)](#addHtml-char---) | フォーマットされたHTMLテキストを追加します。 |
| [addHtml(char[] html, int startIndex, int length)](#addHtml-char---int-int-) | フォーマットされたHTMLテキストを追加します。 |
| [addText(String text)](#addText-java.lang.String-) | HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。 |
| [addText(char[] text)](#addText-char---) | HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。 |
| [addText(char[] text, int startIndex, int length)](#addText-char---int-int-) | HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。 |
| [addAttributeValue(String value)](#addAttributeValue-java.lang.String-) | 属性値を引用し、HTML ファイルに追加します。 |
| [addAttributeValue(char[] value)](#addAttributeValue-char---) | 属性値を引用し、HTML ファイルに追加します。 |
| [addAttributeValue(char[] value, int startIndex, int length)](#addAttributeValue-char---int-int-) | 属性値を引用し、HTML ファイルに追加します。 |
| [getSlideImageSize()](#getSlideImageSize--) | スライド画像サイズを返します。 |
| [getSlideImageSizeUnit()](#getSlideImageSizeUnit--) | スライド画像サイズが指定されている単位を返します。 |
| [getSlideImageSizeUnitCode()](#getSlideImageSizeUnitCode--) | スライド画像サイズが指定されている単位の CSS コードを返します。 |
| [getPreviousSlideIndex()](#getPreviousSlideIndex--) | 前にレンダリングされたスライドのインデックスを返します。最初のスライドがレンダリング中の場合は -1 を返します。 |
| [getSlideIndex()](#getSlideIndex--) | 現在レンダリング中のスライドのインデックスを返します。 |
| [getNextSlideIndex()](#getNextSlideIndex--) | 現在のスライドの次にレンダリングされるスライドのインデックスを返します。現在最後のスライドをレンダリング中の場合は -1 を返します。 |
### addHtml(String html) {#addHtml-java.lang.String-}
```
public final void addHtml(String html)
```

フォーマットされたHTMLテキストを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| html | java.lang.String | 追加するテキスト。 |

### addHtml(char[] html) {#addHtml-char---}
```
public final void addHtml(char[] html)
```

フォーマットされたHTMLテキストを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| html | char[] | 追加するテキスト。 |

### addHtml(char[] html, int startIndex, int length) {#addHtml-char---int-int-}
```
public final void addHtml(char[] html, int startIndex, int length)
```

フォーマットされたHTMLテキストを追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| html | char[] | 追加するテキスト。 |
| startIndex | int | 追加する部分の開始インデックス。 |
| length | int | 追加する部分の長さ。 |

### addText(String text) {#addText-java.lang.String-}
```
public final void addText(String text)
```

HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。改行と空白は置き換えられません。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | java.lang.String | 追加するテキスト。 |

### addText(char[] text) {#addText-char---}
```
public final void addText(char[] text)
```

HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。改行と空白は置き換えられません。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | char[] | 追加するテキスト。 |

### addText(char[] text, int startIndex, int length) {#addText-char---int-int-}
```
public final void addText(char[] text, int startIndex, int length)
```

HTML ファイルにプレーンテキストを追加し、特殊文字を HTML エンティティに置き換えます。改行と空白は置き換えられません。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| text | char[] | 追加するテキスト。 |
| startIndex | int | 追加する部分の開始インデックス。 |
| length | int | 追加する部分の長さ。 |

### addAttributeValue(String value) {#addAttributeValue-java.lang.String-}
```
public final void addAttributeValue(String value)
```

属性値を引用し、HTML ファイルに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | java.lang.String | 属性値文字列。 |

### addAttributeValue(char[] value) {#addAttributeValue-char---}
```
public final void addAttributeValue(char[] value)
```

属性値を引用し、HTML ファイルに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char[] | 属性値文字列。 |

### addAttributeValue(char[] value, int startIndex, int length) {#addAttributeValue-char---int-int-}
```
public final void addAttributeValue(char[] value, int startIndex, int length)
```

属性値を引用し、HTML ファイルに追加します。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | char[] | 属性値文字列。 |
| startIndex | int | 追加する部分の開始インデックス。 |
| length | int | 追加する部分の長さ。 |

### getSlideImageSize() {#getSlideImageSize--}
```
public final SizeF getSlideImageSize()
```

スライド画像サイズを返します。読み取り専用 [SizeF](../../com.aspose.slides.android/sizef)。

**戻り値:**
[SizeF](../../com.aspose.slides.android/sizef)
### getSlideImageSizeUnit() {#getSlideImageSizeUnit--}
```
public final int getSlideImageSizeUnit()
```

スライド画像サイズが指定されている単位を返します。読み取り専用 [SvgCoordinateUnit](../../com.aspose.slides/svgcoordinateunit)。

**戻り値:**
int
### getSlideImageSizeUnitCode() {#getSlideImageSizeUnitCode--}
```
public final String getSlideImageSizeUnitCode()
```

スライド画像サイズが指定されている単位の CSS コードを返します。読み取り専用 String。

**戻り値:**
java.lang.String
### getPreviousSlideIndex() {#getPreviousSlideIndex--}
```
public final int getPreviousSlideIndex()
```

前にレンダリングされたスライドのインデックスを返します。最初のスライドがレンダリング中の場合は -1 を返します。読み取り専用 int。

**戻り値:**
int
### getSlideIndex() {#getSlideIndex--}
```
public final int getSlideIndex()
```

現在レンダリング中のスライドのインデックスを返します。読み取り専用 int。

**戻り値:**
int
### getNextSlideIndex() {#getNextSlideIndex--}
```
public final int getNextSlideIndex()
```

現在のスライドの次にレンダリングされるスライドのインデックスを返します。現在最後のスライドをレンダリング中の場合は -1 を返します。読み取り専用 int。

**戻り値:**
int