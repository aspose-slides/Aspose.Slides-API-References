---
title: ICaptions
second_title: Aspose.Slides for Android via Java API Reference
description: Represents the WebVTT closed captions.
type: docs
url: /zh/com.aspose.slides/icaptions/
---```
public interface ICaptions
```

表示 WebVTT 闭合字幕。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | 返回闭合字幕的全局唯一标识符（GUID）。 |
| [getLabel()](#getLabel--) | 返回或设置闭合字幕的标签。 |
| [setLabel(String value)](#setLabel-java.lang.String-) | 返回或设置闭合字幕的标签。 |
| [getBinaryData()](#getBinaryData--) | 返回闭合字幕的二进制数据。 |
| [getDataAsString()](#getDataAsString--) | 返回闭合字幕数据，作为 UTF-8 编码的字符串。只读 String。 |
### getCaptionId() {#getCaptionId--}
```
public abstract UUID getCaptionId()
```


返回闭合字幕的全局唯一标识符（GUID）。只读 java.util.UUID。

**返回:**  
java.util.UUID
### getLabel() {#getLabel--}
```
public abstract String getLabel()
```


返回或设置闭合字幕的标签。读写 String。

**返回:**  
java.lang.String
### setLabel(String value) {#setLabel-java.lang.String-}
```
public abstract void setLabel(String value)
```


返回或设置闭合字幕的标签。读写 String。

**参数:**  
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |
### getBinaryData() {#getBinaryData--}
```
public abstract byte[] getBinaryData()
```


返回闭合字幕的二进制数据。只读 byte[]。

**返回:**  
byte[]
### getDataAsString() {#getDataAsString--}
```
public abstract String getDataAsString()
```


返回闭合字幕数据，作为 UTF-8 编码的字符串。只读 String。

**返回:**  
java.lang.String