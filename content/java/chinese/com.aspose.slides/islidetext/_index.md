---
title: ISlideText
second_title: Aspose.Slides for Java API Reference
description: 表示从幻灯片中提取的文本
type: docs
url: /zh/com.aspose.slides/islidetext/
---```
public interface ISlideText
```

表示从幻灯片中提取的文本
## 方法

| 方法 | 描述 |
| --- | --- |
| [getText()](#getText--) | 幻灯片形状上的文本 |
| [getMasterText()](#getMasterText--) | 此幻灯片的母版页形状上的文本 |
| [getLayoutText()](#getLayoutText--) | 此幻灯片的布局页形状上的文本 |
| [getNotesText()](#getNotesText--) | 此幻灯片的备注页形状上的文本 |
| [getCommentsText()](#getCommentsText--) | 幻灯片批注的文本 |
### getText() {#getText--}
```
public abstract String getText()
```


幻灯片形状上的文本

**返回：**
java.lang.String
### getMasterText() {#getMasterText--}
```
public abstract String getMasterText()
```


此幻灯片的母版页形状上的文本

**返回：**
java.lang.String
### getLayoutText() {#getLayoutText--}
```
public abstract String getLayoutText()
```


此幻灯片的布局页形状上的文本

**返回：**
java.lang.String
### getNotesText() {#getNotesText--}
```
public abstract String getNotesText()
```


此幻灯片的备注页形状上的文本

**返回：**
java.lang.String
### getCommentsText() {#getCommentsText--}
```
public abstract String getCommentsText()
```


幻灯片批注的文本

--------------------

使用 Arranged 模式提取文本时此字段为空。

**返回：**
java.lang.String