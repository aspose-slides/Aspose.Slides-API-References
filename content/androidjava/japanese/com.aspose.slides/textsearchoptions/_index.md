---
title: TextSearchOptions
second_title: Java API リファレンスによる Android 用 Aspose.Slides
description: プレゼンテーションのスライドまたは TextFrame 内のテキストを検索するために使用できるオプションを表します。
type: docs
url: /ja/com.aspose.slides/textsearchoptions/
---
**継承:**
java.lang.Object

**実装されているすべてのインターフェイス:**
[com.aspose.slides.ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)
```
public class TextSearchOptions implements ITextSearchOptions
```

プレゼンテーション、スライド、または TextFrame 内のテキストを検索するために使用できるオプションを表します。

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [TextSearchOptions()](#TextSearchOptions--) | 新しいデフォルトのテキスト検索オプションを作成します。 |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getCaseSensitive()](#getCaseSensitive--) | 大文字小文字を区別した検索を使用する場合は true、そうでない場合は false を設定します。 |
| [setCaseSensitive(boolean value)](#setCaseSensitive-boolean-) | 大文字小文字を区別した検索を使用する場合は true、そうでない場合は false を設定します。 |
| [getWholeWordsOnly()](#getWholeWordsOnly--) | 完全一致のみを対象とする場合は true、そうでない場合は false を設定します。 |
| [setWholeWordsOnly(boolean value)](#setWholeWordsOnly-boolean-) | 完全一致のみを対象とする場合は true、そうでない場合は false を設定します。 |
| [getIncludeNotes()](#getIncludeNotes--) | スライドノート ([NotesSlide](../../com.aspose.slides/notesslide)) に含まれるテキストを、テキスト検索、置換、またはハイライト操作で使用する場合は true を設定します。 |
| [setIncludeNotes(boolean value)](#setIncludeNotes-boolean-) | スライドノート ([NotesSlide](../../com.aspose.slides/notesslide)) に含まれるテキストを、テキスト検索、置換、またはハイライト操作で使用する場合は true を設定します。 |

### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```

新しいデフォルトのテキスト検索オプションを作成します。

### getCaseSensitive() {#getCaseSensitive--}
```
public final boolean getCaseSensitive()
```

大文字小文字を区別した検索を使用する場合は true、そうでない場合は false を設定します。 読み取り/書き込み  boolean .

**戻り値:**
boolean

### setCaseSensitive(boolean value) {#setCaseSensitive-boolean-}
```
public final void setCaseSensitive(boolean value)
```

大文字小文字を区別した検索を使用する場合は true、そうでない場合は false を設定します。 読み取り/書き込み  boolean .

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getWholeWordsOnly() {#getWholeWordsOnly--}
```
public final boolean getWholeWordsOnly()
```

完全一致のみを対象とする場合は true、そうでない場合は false を設定します。 読み取り/書き込み  boolean .

**戻り値:**
boolean

### setWholeWordsOnly(boolean value) {#setWholeWordsOnly-boolean-}
```
public final void setWholeWordsOnly(boolean value)
```

完全一致のみを対象とする場合は true、そうでない場合は false を設定します。 読み取り/書き込み  boolean .

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |

### getIncludeNotes() {#getIncludeNotes--}
```
public final boolean getIncludeNotes()
```

スライドノート ([NotesSlide](../../com.aspose.slides/notesslide)) に含まれるテキストを、テキスト検索、置換、またはハイライト操作で使用する場合は true を設定します。 デフォルト値は false です。

**戻り値:**
boolean

### setIncludeNotes(boolean value) {#setIncludeNotes-boolean-}
```
public final void setIncludeNotes(boolean value)
```

スライドノート ([NotesSlide](../../com.aspose.slides/notesslide)) に含まれるテキストを、テキスト検索、置換、またはハイライト操作で使用する場合は true を設定します。 デフォルト値は false です。

**パラメータ:**
| パラメータ | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |