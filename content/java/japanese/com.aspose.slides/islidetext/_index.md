---
title: ISlideText
second_title: Aspose.Slides for Java API Reference
description: Represents the text extracted from the slide
type: docs
url: /ja/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

スライドから抽出されたテキストを表します
## メソッド

| メソッド | 説明 |
| --- | --- |
| [getText()](#getText--) | スライドのシェイプ上のテキスト |
| [getMasterText()](#getMasterText--) | このスライドのマスターページのシェイプ上のテキスト |
| [getLayoutText()](#getLayoutText--) | このスライドのレイアウトページのシェイプ上のテキスト |
| [getNotesText()](#getNotesText--) | このスライドのノートページのシェイプ上のテキスト |
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

このスライドのマスターページのシェイプ上のテキスト

**戻り値:**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```

このスライドのレイアウトページのシェイプ上のテキスト

**戻り値:**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```

このスライドのノートページのシェイプ上のテキスト

**戻り値:**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```

スライドコメントのテキスト

--------------------

テキストが Arranged モードで抽出される場合、このフィールドは空になります。

**戻り値:**
java.lang.String