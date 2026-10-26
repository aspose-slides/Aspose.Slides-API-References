---
title: ITextSearchOptions
second_title: Aspose.Slides for Java API 参考
description: 表示可用于在演示文稿幻灯片或文本框中搜索文本的选项。
type: docs
url: /zh/com.aspose.slides/itextsearchoptions/
---```
public interface ITextSearchOptions
```

表示可用于在演示文稿、幻灯片或文本框中搜索文本的选项。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCaseSensitive()](#getCaseSensitive--) | 设置为 true 以进行区分大小写的搜索，false 则相反。 |
| [setCaseSensitive(boolean value)](#setCaseSensitive-boolean-) | 设置为 true 以进行区分大小写的搜索，false 则相反。 |
| [getWholeWordsOnly()](#getWholeWordsOnly--) | 设置为 true 仅匹配完整单词，false 则相反。 |
| [setWholeWordsOnly(boolean value)](#setWholeWordsOnly-boolean-) | 设置为 true 仅匹配完整单词，false 则相反。 |
| [getIncludeNotes()](#getIncludeNotes--) | 设置为 true 在执行文本搜索、替换或突出显示操作时包含幻灯片备注中的文本。 |
| [setIncludeNotes(boolean value)](#setIncludeNotes-boolean-) | 设置为 true 在执行文本搜索、替换或突出显示操作时包含幻灯片备注中的文本。 |

### getCaseSensitive() {#getCaseSensitive--}
```
public abstract boolean getCaseSensitive()
```

设置为 true 以进行区分大小写的搜索，false 则相反。读/写 boolean。

**返回值：**
boolean

### setCaseSensitive(boolean value) {#setCaseSensitive-boolean-}
```
public abstract void setCaseSensitive(boolean value)
```

设置为 true 以进行区分大小写的搜索，false 则相反。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getWholeWordsOnly() {#getWholeWordsOnly--}
```
public abstract boolean getWholeWordsOnly()
```

设置为 true 仅匹配完整单词，false 则相反。读/写 boolean。

**返回值：**
boolean

### setWholeWordsOnly(boolean value) {#setWholeWordsOnly-boolean-}
```
public abstract void setWholeWordsOnly(boolean value)
```

设置为 true 仅匹配完整单词，false 则相反。读/写 boolean。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |

### getIncludeNotes() {#getIncludeNotes--}
```
public abstract boolean getIncludeNotes()
```

设置为 true 在执行文本搜索、替换或突出显示操作时包含幻灯片备注中的文本。默认值为 false。

**返回值：**
boolean

### setIncludeNotes(boolean value) {#setIncludeNotes-boolean-}
```
public abstract void setIncludeNotes(boolean value)
```

设置为 true 在执行文本搜索、替换或突出显示操作时包含幻灯片备注中的文本。默认值为 false。

**参数：**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | boolean |  |