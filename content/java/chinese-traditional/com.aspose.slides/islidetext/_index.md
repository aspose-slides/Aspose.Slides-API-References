---
title: ISlideText
second_title: Aspose.Slides for Java API Reference
description: Represents the text extracted from the slide
type: docs
url: /zh-hant/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

表示從投影片中提取的文字
## Methods

| Method | Description |
| --- | --- |
| [getText()](#getText--) | 投影片形狀上的文字 |
| [getMasterText()](#getMasterText--) | 此投影片的母版頁面形狀上的文字 |
| [getLayoutText()](#getLayoutText--) | 此投影片的版面配置頁面形狀上的文字 |
| [getNotesText()](#getNotesText--) | 此投影片的備註頁面形狀上的文字 |
| [getCommentsText()](#getCommentsText--) | 投影片註解的文字 |
### getText() {#getText--}
```
public abstract String getText()
```

投影片形狀上的文字

**返回：**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```

此投影片的母版頁面形狀上的文字

**返回：**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```

此投影片的版面配置頁面形狀上的文字

**返回：**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```

此投影片的備註頁面形狀上的文字

**返回：**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```

投影片註解的文字

--------------------

當文字以 Arranged 模式提取時，此欄位為空。

**返回：**
java.lang.String