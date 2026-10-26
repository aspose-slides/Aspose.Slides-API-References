---
title: IAIConversation
second_title: Aspose.Slides for Java API Reference
description: 代表一個對話實例。
type: docs
url: /zh-hant/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

代表一個對話實例。與一般的 AI 調用不同，對話會保留完整的上下文。

## 方法

| 方法 | 說明 |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | 傳送包含完整上下文的對話請求訊息並返回回應。 |

### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

傳送包含完整上下文的對話請求訊息並返回回應。

**參數：**
| 參數 | 類型 | 說明 |
| --- | --- | --- |
| instruction | java.lang.String | 要由 AI 模型處理的指示或訊息。 |

**回傳值：**
java.lang.String - AI 模型根據對話上下文中給定的指示所產生的訊息。