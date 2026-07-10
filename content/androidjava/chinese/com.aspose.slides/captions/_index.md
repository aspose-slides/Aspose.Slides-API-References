---
title: Captions
second_title: Aspose.Slides for Android 通过 Java API 参考
description: 表示 WebVTT 闭字幕。
type: docs
url: /zh/com.aspose.slides/captions/
---
**继承:**  
java.lang.Object

**所有实现的接口:**  
[com.aspose.slides.ICaptions](../../com.aspose.slides/icaptions)  
```
public class Captions implements ICaptions
```

表示 WebVTT 闭字幕。

## 方法

| 方法 | 描述 |
| --- | --- |
| [getCaptionId()](#getCaptionId--) | 返回闭字幕的全局唯一标识符 (GUID)。 |
| [getLabel()](#getLabel--) | 返回或设置闭字幕的标签。 |
| [setLabel(String value)](#setLabel-java.lang.String-) | 返回或设置闭字幕的标签。 |
| [getBinaryData()](#getBinaryData--) | 返回闭字幕的二进制数据。 |
| [getDataAsString()](#getDataAsString--) | 返回闭字幕数据为 UTF-8 编码的字符串，只读 String。 |

### getCaptionId() {#getCaptionId--}
```
public final UUID getCaptionId()
```

返回闭字幕的全局唯一标识符 (GUID)。只读 java.util.UUID。

**返回:**  
java.util.UUID

### getLabel() {#getLabel--}
```
public final String getLabel()
```

返回或设置闭字幕的标签。可读写 String。

**返回:**  
java.lang.String

### setLabel(String value) {#setLabel-java.lang.String-}
```
public final void setLabel(String value)
```

返回或设置闭字幕的标签。可读写 String。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

### getBinaryData() {#getBinaryData--}
```
public final byte[] getBinaryData()
```

返回闭字幕的二进制数据。只读 byte[] 。

**返回:**  
byte[]

### getDataAsString() {#getDataAsString--}
```
public final String getDataAsString()
```

返回闭字幕数据为 UTF-8 编码的字符串，只读 String。

**返回:**  
java.lang.String