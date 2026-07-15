---
title: IAIConversation
second_title: Aspose.Slides 適用於 Android 的 Java API 參考
description: 表示一個會話實例。
type: docs
url: /zh-hant/com.aspose.slides/iaiconversation/
---```
public interface IAIConversation
```

表示一個會話實例。與一般的 AI 呼叫不同，會話會保留完整的上下文。
## 方法

| 方法 | 描述 |
| --- | --- |
| [getResponse(String instruction)](#getResponse-java.lang.String-) | 發送會話請求訊息，包括全部上下文，並回傳回應。 |
### getResponse(String instruction) {#getResponse-java.lang.String-}
```
public abstract String getResponse(String instruction)
```

發送會話請求訊息，包括全部上下文，並回傳回應。

**參數：**
| 參數 | 類型 | 描述 |
| --- | --- | --- |
| instruction | java.lang.String | 要由 AI 模型處理的指示或訊息。 |

**回傳：**
java.lang.String - 在會話上下文中對給定指示的回應，AI 模型產生的訊息。