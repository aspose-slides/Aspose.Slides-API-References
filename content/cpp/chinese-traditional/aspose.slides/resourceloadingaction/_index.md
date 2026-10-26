---
title: ResourceLoadingAction
second_title: Aspose.Slides 用於 C++ 的 API 參考
description: 指定外部資源載入的模式。
type: docs
weight: 6761
url: /zh-hant/aspose.slides/resourceloadingaction/
---
## ResourceLoadingAction 列舉


指定外部資源載入的模式。

```cpp
enum class ResourceLoadingAction
```

### 值

| 名稱 | 值 | 說明 |
| --- | --- | --- |
| Default | 0 | [Aspose.Slides](../) 將照常載入外部資源。 |
| Skip | 1 | [Aspose.Slides](../) 將跳過外部資源的載入。僅會為圖像儲存沒有資料的連結。 |
| UserProvided | 2 | [Aspose.Slides](../) 將使用使用者在 [IResourceLoadingArgs::SetData](../iresourceloadingargs/setdata/) 中提供的位元組陣列作為圖像資料。 |

## 參見

* 命名空間 [Aspose::Slides](../)
* 函式庫 [Aspose.Slides](../../)