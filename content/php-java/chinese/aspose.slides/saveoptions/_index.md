---
title: SaveOptions
second_title: Aspose.Sildes for PHP via Java API 参考
description: 
type: docs

url: /zh/aspose.slides/saveoptions/
---
## SaveOptions 类

抽象类，提供控制演示文稿保存方式的选项。

### SaveOptions {#SaveOptions}

| 名称 | 描述 |
| --- | --- |
| SaveOptions() |  |

**返回:**  
SaveOptions

---

### getDefaultRegularFont {#getDefaultRegularFont}

| 名称 | 描述 |
| --- | --- |
| getDefaultRegularFont () | 返回或设置在未找到源字体时使用的字体。读写 String。 |

**返回:**  
String

---

### getGradientStyle {#getGradientStyle}

| 名称 | 描述 |
| --- | --- |
| getGradientStyle () | 返回或设置渐变的可视样式。读写 GradientStyle。 |

**返回:**  
int

---

### getProgressCallback {#getProgressCallback}

| 名称 | 描述 |
| --- | --- |
| getProgressCallback () | 表示用于保存进度更新（百分比）的回调对象。参见 IProgressCallback。 |

**返回:**  
IProgressCallback

---

### getSkipJavaScriptLinks {#getSkipJavaScriptLinks}

| 名称 | 描述 |
| --- | --- |
| getSkipJavaScriptLinks () | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。读写 boolean。默认值为 false。当此属性设置为 true 时，保存时将忽略带有 JavaScript 调用的超链接。当此属性设置为 false 时，所有超链接都将被保存。 |

**返回:**  
boolean

---

### getWarningCallback {#getWarningCallback}

| 名称 | 描述 |
| --- | --- |
| getWarningCallback () | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。读写 IWarningCallback。 |

**返回:**  
IWarningCallback

---

### setDefaultRegularFont {#setDefaultRegularFont}

| 名称 | 描述 |
| --- | --- |
| setDefaultRegularFont (String) | 返回或设置在未找到源字体时使用的字体。读写 String。 |

**返回:**  
void

---

### setGradientStyle {#setGradientStyle}

| 名称 | 描述 |
| --- | --- |
| setGradientStyle (int) | 返回或设置渐变的可视样式。读写 GradientStyle。 |

**返回:**  
void

---

### setProgressCallback {#setProgressCallback}

| 名称 | 描述 |
| --- | --- |
| setProgressCallback ([IProgressCallback](../iprogresscallback)) | 表示用于保存进度更新（百分比）的回调对象。参见 IProgressCallback。 |

**返回:**  
void

---

### setSkipJavaScriptLinks {#setSkipJavaScriptLinks}

| 名称 | 描述 |
| --- | --- |
| setSkipJavaScriptLinks (boolean) | 指定在保存演示文稿时是否跳过带有 JavaScript 调用的超链接。读写 boolean。默认值为 false。当此属性设置为 true 时，保存时将忽略带有 JavaScript 调用的超链接。当此属性设置为 false 时，所有超链接都将被保存。 |

**返回:**  
void

---

### setWarningCallback {#setWarningCallback}

| 名称 | 描述 |
| --- | --- |
| setWarningCallback ([IWarningCallback](../iwarningcallback)) | 返回或设置一个接收警告并决定加载过程是继续还是中止的对象。读写 IWarningCallback。 |

**返回:**  
void

---