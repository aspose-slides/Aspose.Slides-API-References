---
title: EmbeddingLevel
second_title: Aspose.Slides for C++ API 參考文件
description: 表示可嵌入字型的授權權利。
type: docs
weight: 5786
url: /zh-hant/aspose.slides/embeddinglevel/
---
## EmbeddingLevel enum

表示可嵌入字型的授權權利。

```cpp
enum class EmbeddingLevel : uint16_t
```

### Values

| 名稱 | 值 | 描述 |
| --- | --- | --- |
| Installable | 0 | [Fonts](../fonts/) 具有此設定表示它們可以被嵌入並永久安裝在遠端系統上，由應用程式執行。遠端系統的使用者取得與原始購買者相同的權利、義務和字型授權，並受相同的最終使用者授權協議、版權、設計專利和/或商標約束。 |
| Restricted | 2 | [Fonts](../fonts/) 只設定此位元者不得在未先取得合法所有者許可的情況下進行任何修改、嵌入或交換。 |
| PreviewPrint | 4 | 當此位元被設定時，字型可以被嵌入，並暫時載入遠端系統。包含 Preview & Print 字型的文件必須以「唯讀」方式開啟；文件不可進行編輯。 |
| Editable | 8 | 當此位元被設定時，字型可以被嵌入，但只能暫時安裝在其他系統上。與 Preview & Print 字型不同，包含 Editable 字型的文件可開啟閱讀，允許編輯，且變更可被儲存。 |
| NoSubsetting | 256 | 當此位元被設定時，字型在嵌入前不得子集化。位元 0-3 與 9 中指定的其他嵌入限制亦適用。 |
| BitmapOnly | 512 | 當此位元被設定時，僅允許嵌入字型中包含的點陣圖。輪廓資料不得嵌入。若字型中沒有可用的點陣圖，則視為無法嵌入，嵌入服務將失敗。 |

## See Also

* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)