---
title: insert_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/insert_ole_object_frame/
weight: 280
---
## insert_ole_object_frame(self, index, x, y, width, height, data_info) {#int-float-float-float-float-ioleembeddeddatainfo}
建立一個新的 OLE 物件框架，並將其插入至形狀集合中指定的索引位置。

### 回傳
新建立的 [`IOleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/ioleobjectframe)。

```python
def insert_ole_object_frame(self, index, x, y, width, height, data_info):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入 OLE 物件框架的零基索引。 |
| x | **float** | 新 OLE 框架的 x 座標，單位為點。 |
| y | **float** | 新 OLE 框架的 y 座標，單位為點。 |
| width | **float** | 新 OLE 框架的寬度，單位為點。 |
| height | **float** | 新 OLE 框架的高度，單位為點。 |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo) | 嵌入的 OLE 資料資訊（[`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo)）。 |

## insert_ole_object_frame(self, index, x, y, width, height, class_name, path) {#int-float-float-float-float-str-str}
建立一個新的 OLE 物件框架，並將其插入至形狀集合中指定的索引位置。

### 回傳
新建立的 [`IOleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/ioleobjectframe)。

```python
def insert_ole_object_frame(self, index, x, y, width, height, class_name, path):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| index | **int** | 要插入 OLE 物件框架的零基索引。 |
| x | **float** | 新 OLE 框架的 x 座標，單位為點。 |
| y | **float** | 新 OLE 框架的 y 座標，單位為點。 |
| width | **float** | 新 OLE 框架的寬度，單位為點。 |
| height | **float** | 新 OLE 框架的高度，單位為點。 |
| class_name | **str** | OLE 物件的類別名稱。 |
| path | **str** | 連結檔案的路徑。 <br/><br/>此路徑會以原樣儲存在簡報中。<br/><br/>            如果指定相對路徑，當從不同目錄開啟簡報時，檔案將無法存取。 |

### 另請參閱
* 類別 [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo)
* 類別 [`IOleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/ioleobjectframe)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)