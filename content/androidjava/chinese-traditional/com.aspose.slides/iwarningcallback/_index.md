---
title: IWarningCallback
second_title: Aspose.Slides for Android via Java API 參考文件
description: 接收警告的類別介面
type: docs
url: /zh-hant/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

接收警告的類別介面
## Methods

| 方法 | 說明 |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | 回呼方法，用於接收警告並決定是否應該中止操作。 |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```

回呼方法，用於接收警告並決定是否應該中止操作。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | 要處理的警告。 |

**返回值:**
int - 中止決定 [ReturnAction](../../com.aspose.slides/returnaction).