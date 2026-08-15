---
title: LinkEmbedDecision
second_title: Aspose.Slides for C++ API 參考
description: 決定物件在儲存過程中如何被處理。
type: docs
weight: 911
url: /zh-hant/aspose.slides.export/linkembeddecision/
---
## LinkEmbedDecision 列舉

決定物件在儲存過程中的處理方式。

```cpp
enum class LinkEmbedDecision
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Link | 0 | 物件將被外部儲存，透過 URL 參考 |
| Embed | 1 | 如果可能，應將物件嵌入生成的檔案中。如果嵌入不可能，將呼叫 GetUrl，並根據結果，物件將透過 URL 參考或被忽略 |
| Ignore | 2 | 物件將被忽略 |

## 參見

* 命名空間 [Aspose::Slides::Export](../)
* 函式庫 [Aspose.Slides](../../)