---
title: set_metered_key method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/metered/set_metered_key/
weight: 60
---
## set_metered_key(self, public_key, private_key) {#str-str}
設定計量公鑰與私鑰。
如果您購買了計量授權，應用程式啟動時應呼叫此 API，通常這已足夠。
然而，如果持續無法上傳消耗資料且超過 24 小時，授權會被設定為評估狀態，
為避免此情況，您應定期檢查授權狀態，若為評估狀態，請再次呼叫此 API。

```python
def set_metered_key(self, public_key, private_key):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| public_key | **str** | 公鑰 |
| private_key | **str** | 私鑰 |

### 參見
* 類別 [`Metered`](/slides/python-net/zh-hant/aspose.slides/metered)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)