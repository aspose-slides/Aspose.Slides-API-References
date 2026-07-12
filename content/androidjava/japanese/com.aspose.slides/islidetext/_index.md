---
title: ISlideText
second_title: Aspose.Slides for Android via Java API Reference
description: スライドから抽出されたテキストを表します
type: docs
url: /ja/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

スライドから抽出されたテキストを表します
## メソッド

| Method | 説明 |
| --- | --- |
| [getText()](#getText--) | スライドのシェイプ上のテキスト |
| [getMasterText()](#getMasterText--) | このスライドのマスターページ上のシェイプのテキスト |
| [getLayoutText()](#getLayoutText--) | このスライドのレイアウトページ上のシェイプのテキスト |
| [getNotesText()](#getNotesText--) | このスライドのノートページ上のシェイプのテキスト |
| [getCommentsText()](#getCommentsText--) | スライドコメントのテキスト |
### getText() {#getText--}
```
public abstract String getText()
```


スライドのシェイプ上のテキスト

**戻り値:**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


このスライドのマスターページ上のシェイプのテキスト

**戻り値:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


このスライドのレイアウトページ上のシェイプのテキスト

**戻り値:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


このスライドのノートページ上のシェイプのテキスト

**戻り値:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


スライドコメントのテキスト

--------------------

このフィールドは、Arranged モードを使用してテキストを抽出した場合は空になります。

**戻り値:**
java.lang.String