---
title: ITextSearchOptions
second_title: Aspose.Slides for Java API Reference
description: Presentation、Slide、または TextFrame 内のテキストを検索するために使用できるオプションを表します。
type: docs
url: /ja/com.aspose.slides/itextsearchoptions/
---```
public interface ITextSearchOptions
```

Presentation、Slide、または TextFrame 内のテキストを検索するために使用できるオプションを表します。
## Methods

| Method | Description |
| --- | --- |
| [getCaseSensitive()](#getCaseSensitive--) | 大文字と小文字を区別した検索を使用する場合は true、そうでない場合は false を設定します。 |
| [setCaseSensitive(boolean value)](#setCaseSensitive-boolean-) | 大文字と小文字を区別した検索を使用する場合は true、そうでない場合は false を設定します。 |
| [getWholeWordsOnly()](#getWholeWordsOnly--) | 単語全体に一致させる場合は true、そうでない場合は false を設定します。 |
| [setWholeWordsOnly(boolean value)](#setWholeWordsOnly-boolean-) | 単語全体に一致させる場合は true、そうでない場合は false を設定します。 |
| [getIncludeNotes()](#getIncludeNotes--) | テキスト検索、置換、またはハイライト操作を行う際にスライドノートに含まれるテキストを含める場合は true を設定します。 |
| [setIncludeNotes(boolean value)](#setIncludeNotes-boolean-) | テキスト検索、置換、またはハイライト操作を行う際にスライドノートに含まれるテキストを含める場合は true を設定します。 |
### getCaseSensitive() {#getCaseSensitive--}
```
public abstract boolean getCaseSensitive()
```

大文字と小文字を区別した検索を使用する場合は true、そうでない場合は false を設定します。読み書き可能な boolean 型。

**戻り値:**  
boolean
### setCaseSensitive(boolean value) {#setCaseSensitive-boolean-}
```
public abstract void setCaseSensitive(boolean value)
```

大文字と小文字を区別した検索を使用する場合は true、そうでない場合は false を設定します。読み書き可能な boolean 型。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getWholeWordsOnly() {#getWholeWordsOnly--}
```
public abstract boolean getWholeWordsOnly()
```

単語全体に一致させる場合は true、そうでない場合は false を設定します。読み書き可能な boolean 型。

**戻り値:**  
boolean
### setWholeWordsOnly(boolean value) {#setWholeWordsOnly-boolean-}
```
public abstract void setWholeWordsOnly(boolean value)
```

単語全体に一致させる場合は true、そうでない場合は false を設定します。読み書き可能な boolean 型。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |
### getIncludeNotes() {#getIncludeNotes--}
```
public abstract boolean getIncludeNotes()
```

テキスト検索、置換、またはハイライト操作を行う際にスライドノートに含まれるテキストを含める場合は true を設定します。デフォルト値は false です。

**戻り値:**  
boolean
### setIncludeNotes(boolean value) {#setIncludeNotes-boolean-}
```
public abstract void setIncludeNotes(boolean value)
```

テキスト検索、置換、またはハイライト操作を行う際にスライドノートに含まれるテキストを含める場合は true を設定します。デフォルト値は false です。

**パラメーター:**
| パラメーター | 型 | 説明 |
| --- | --- | --- |
| value | boolean |  |