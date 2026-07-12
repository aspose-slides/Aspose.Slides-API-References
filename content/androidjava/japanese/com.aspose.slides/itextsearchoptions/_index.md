---
title: ITextSearchOptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents options that can be used to search for text in a Presentation Slide or TextFrame.
type: docs
url: /ja/com.aspose.slides/itextsearchoptions/
---```
public interface ITextSearchOptions
```

Presentation、Slide、または TextFrame 内のテキストを検索するために使用できるオプションを表します。
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCaseSensitive()](#getCaseSensitive--) | true を設定すると大文字と小文字を区別した検索を使用し、false の場合は区別しません。 |
| [setCaseSensitive(boolean value)](#setCaseSensitive-boolean-) | true を設定すると大文字と小文字を区別した検索を使用し、false の場合は区別しません。 |
| [getWholeWordsOnly()](#getWholeWordsOnly--) | true を設定すると単語全体にのみ一致させ、false の場合は一致させません。 |
| [setWholeWordsOnly(boolean value)](#setWholeWordsOnly-boolean-) | true を設定すると単語全体にのみ一致させ、false の場合は一致させません。 |
| [getIncludeNotes()](#getIncludeNotes--) | true を設定すると、テキスト検索、置換、またはハイライト操作を実行するときにスライドノートに含まれるテキストを含めます。 |
| [setIncludeNotes(boolean value)](#setIncludeNotes-boolean-) | true を設定すると、テキスト検索、置換、またはハイライト操作を実行するときにスライドノートに含まれるテキストを含めます。 |
### getCaseSensitive() {#getCaseSensitive--}
```
public abstract boolean getCaseSensitive()
```


true を設定すると大文字と小文字を区別した検索を使用し、false の場合は区別しません。 読み取り/書き込み boolean.

**戻り値:**
boolean
### setCaseSensitive(boolean value) {#setCaseSensitive-boolean-}
```
public abstract void setCaseSensitive(boolean value)
```


true を設定すると大文字と小文字を区別した検索を使用し、false の場合は区別しません。 読み取り/書き込み boolean.

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getWholeWordsOnly() {#getWholeWordsOnly--}
```
public abstract boolean getWholeWordsOnly()
```


true を設定すると単語全体にのみ一致させ、false の場合は一致させません。 読み取り/書き込み boolean.

**戻り値:**
boolean
### setWholeWordsOnly(boolean value) {#setWholeWordsOnly-boolean-}
```
public abstract void setWholeWordsOnly(boolean value)
```


true を設定すると単語全体にのみ一致させ、false の場合は一致させません。 読み取り/書き込み boolean.

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getIncludeNotes() {#getIncludeNotes--}
```
public abstract boolean getIncludeNotes()
```


true を設定すると、テキスト検索、置換、またはハイライト操作を実行するときにスライドノートに含まれるテキストを含めます。 デフォルト値は false です。

**戻り値:**
boolean
### setIncludeNotes(boolean value) {#setIncludeNotes-boolean-}
```
public abstract void setIncludeNotes(boolean value)
```


true を設定すると、テキスト検索、置換、またはハイライト操作を実行するときにスライドノートに含まれるテキストを含めます。 デフォルト値は false です。

**パラメーター:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |