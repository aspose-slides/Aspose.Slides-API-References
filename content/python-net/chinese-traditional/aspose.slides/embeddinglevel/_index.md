---
title: EmbeddingLevel enumeration
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/embeddinglevel/
---
## EmbeddingLevel 列舉

表示字型嵌入的授權權利。

EmbeddingLevel 類型公開以下成員：

## 欄位

| 欄位 | 描述 |
| :- | :- |
| INSTALLABLE | 具有此設定的字型表示它們可以由應用程式嵌入並永久安裝在遠端系統上。<br/>遠端系統的使用者將取得與原始購買者相同的權利、義務與授權，<br/>並受到與原始購買者相同的最終使用者授權協議、版權、設計專利及/或商標的限制。 |
| RESTRICTED | 只有設定此位元的字型不得以任何方式修改、嵌入或交換，除非先取得合法所有者的許可。 |
| PREVIEW_PRINT | 設定此位元時，字型可以嵌入，並暫時載入遠端系統。包含 Preview &<br/>Print 字型的文件必須以「唯讀」方式開啟；不得對文件進行編輯。 |
| EDITABLE | 設定此位元時，字型可以嵌入，但只能暫時安裝在其他系統上。與 Preview &<br/>Print 字型相比，包含 Editable 字型的文件可供閱讀，允許編輯，且變更可以儲存。 |
| NO_SUBSETTING | 設定此位元時，字型在嵌入前不得進行子集化。位元 0-3 與 9 所指定的其他嵌入限制亦同樣適用。 |
| BITMAP_ONLY | 設定此位元時，僅允許嵌入字型中包含的點陣圖。輪廓資料不得嵌入。若字型中沒有可用的點陣圖，<br/>則視為不可嵌入，嵌入服務將失敗。 |

### 相關參考
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)