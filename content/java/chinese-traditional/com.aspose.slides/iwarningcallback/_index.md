---
title: IWarningCallback
second_title: Aspose.Slides for Java API 參考
description: 接收警告的類別介面
type: docs
url: /zh-hant/com.aspose.slides/iwarningcallback/
---```
public interface IWarningCallback
```

接收警告的類別介面
## 方法

| 方法 | 說明 |
| --- | --- |
| [warning(IWarningInfo warning)](#warning-com.aspose.slides.IWarningInfo-) | 接收警告並決定是否應中止操作的回呼方法。 |
### warning(IWarningInfo warning) {#warning-com.aspose.slides.IWarningInfo-}
```
public abstract int warning(IWarningInfo warning)
```


接收警告並決定是否應中止操作的回呼方法。

**參數:**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| warning | [IWarningInfo](../../com.aspose.slides/iwarninginfo) | 要處理的警告。 |

**返回值:**
int - 中止決策 [ReturnAction](../../com.aspose.slides/returnaction).