---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API 参考
description: 用于接收警告的类的接口
type: docs
url: /zh/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

用于接收警告的类的接口
## 方法

| 方法 | 描述 |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | 回调方法，用于接收警告并决定是否中止操作。 |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

回调方法，用于接收警告并决定是否中止操作。

**参数:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | 要处理的警告。 |

**返回值:**
int - 中止决定 [ReturnAction](../../com.aspose.slides/returnaction).