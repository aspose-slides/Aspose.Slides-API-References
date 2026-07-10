---
title: TextSearchOptions
second_title: Aspose.Slides for Android via Java API 参考文档
description: 表示可用于在演示文稿、幻灯片或文本框中搜索文本的选项。
type: docs
url: /zh/com.aspose.slides/textsearchoptions/
---
**继承:**  
java.lang.Object

**所有已实现的接口:**  
[com.aspose.slides.ITextSearchOptions](../../com.aspose.slides/itextsearchoptions)  
```
public class TextSearchOptions implements ITextSearchOptions
```

表示可用于在 Presentation、Slide 或 TextFrame 中搜索文本的选项。

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TextSearchOptions()](#TextSearchOptions--) | 创建新的默认文本搜索选项。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCaseSensitive()](#getCaseSensitive--) | 设置为 true 以使用区分大小写的搜索，false 则相反。 |
| [setCaseSensitive(boolean value)](#setCaseSensitive-boolean-) | 设置为 true 以使用区分大小写的搜索，false 则相反。 |
| [getWholeWordsOnly()](#getWholeWordsOnly--) | 设置为 true 仅匹配完整单词，false 则相反。 |
| [setWholeWordsOnly(boolean value)](#setWholeWordsOnly-boolean-) | 设置为 true 仅匹配完整单词，false 则相反。 |
| [getIncludeNotes()](#getIncludeNotes--) | 在执行文本搜索、替换或高亮操作时，设置为 true 以包含幻灯片备注中包含的文本（[NotesSlide](../../com.aspose.slides/notesslide)）。 |
| [setIncludeNotes(boolean value)](#setIncludeNotes-boolean-) | 在执行文本搜索、替换或高亮操作时，设置为 true 以包含幻灯片备注中包含的文本（[NotesSlide](../../com.aspose.slides/notesslide)）。 |

### TextSearchOptions() {#TextSearchOptions--}
```
public TextSearchOptions()
```

创建新的默认文本搜索选项。

### getCaseSensitive() {#getCaseSensitive--}
```
public final boolean getCaseSensitive()
```

设置为 true 以使用区分大小写的搜索，false 则相反。读/写  boolean .

**返回:**  
boolean

### setCaseSensitive(boolean value) {#setCaseSensitive-boolean-}
```
public final void setCaseSensitive(boolean value)
```

设置为 true 以使用区分大小写的搜索，false 则相反。读/写  boolean .

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getWholeWordsOnly() {#getWholeWordsOnly--}
```
public final boolean getWholeWordsOnly()
```

设置为 true 仅匹配完整单词，false 则相反。读/写  boolean .

**返回:**  
boolean

### setWholeWordsOnly(boolean value) {#setWholeWordsOnly-boolean-}
```
public final void setWholeWordsOnly(boolean value)
```

设置为 true 仅匹配完整单词，false 则相反。读/写  boolean .

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getIncludeNotes() {#getIncludeNotes--}
```
public final boolean getIncludeNotes()
```

在执行文本搜索、替换或高亮操作时，设置为 true 以包含幻灯片备注中包含的文本（[NotesSlide](../../com.aspose.slides/notesslide)）。默认值为 false。

**返回:**  
boolean

### setIncludeNotes(boolean value) {#setIncludeNotes-boolean-}
```
public final void setIncludeNotes(boolean value)
```

在执行文本搜索、替换或高亮操作时，设置为 true 以包含幻灯片备注中包含的文本（[NotesSlide](../../com.aspose.slides/notesslide)）。默认值为 false。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |