---
title: set_embedded_data method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/oleobjectframe/set_embedded_data/
weight: 60
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
設定 OLE 嵌入資料的資訊。

此方法會變更物件的屬性以反映新資料，並將 IsObjectLink 標誌設為 false，表示 OLE 物件已嵌入。

```python
def set_embedded_data(self, embedded_data):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo) | 嵌入資料 [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo) |

### 例外

| 例外 | 描述 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 embeddedData 參數為 None 時。 |

### 另請參閱
* 類別 [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo)
* 類別 [`OleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/oleobjectframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)