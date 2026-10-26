---
title: set_embedded_data method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ioleobjectframe/set_embedded_data/
weight: 50
---
## set_embedded_data(self, embedded_data) {#ioleembeddeddatainfo}
設定有關 OLE 嵌入資料的資訊。


```python
def set_embedded_data(self, embedded_data):
    ...
```


| 參數 | 類型 | 說明 |
| :- | :- | :- |
| embedded_data | [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo) | 嵌入資料 [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo) |

### 備註

此方法會變更物件的屬性以反映新資料，並將 IsObjectLink 旗標設定為 false，表示 OLE 物件已嵌入。

### 例外狀況

| 例外 | 說明 |
| :- | :- |
| **RuntimeError(Proxy error(ArgumentNullException))** | 當 embeddedData 參數為 None 時。 |



### 參見
* 類別 [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo)
* 類別 [`IOleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/ioleobjectframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 程式庫 [`Aspose.Slides`](/slides/python-net)