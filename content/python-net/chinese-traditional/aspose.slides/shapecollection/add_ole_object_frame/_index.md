---
title: add_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API 參考文件
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
建立新的 OLE 物件框架並將其加入形狀集合的末端。

### 返回

新建立的 [`IOleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/ioleobjectframe)。

```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| x | **float** | 新 OLE 框架的 x 坐標，單位為點。 |
| y | **float** | 新 OLE 框架的 y 坐標，單位為點。 |
| width | **float** | 新 OLE 框架的寬度，單位為點。 |
| height | **float** | 新 OLE 框架的高度，單位為點。 |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo) | 有關嵌入 OLE 資料的資訊 ([`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo))。 |

## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
建立新的 OLE 物件框架並將其加入形狀集合的末端。

### 返回

新建立的 [`IOleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/ioleobjectframe)。

```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| x | **float** | 新 OLE 框架的 x 坐標，單位為點。 |
| y | **float** | 新 OLE 框架的 y 坐標，單位為點。 |
| width | **float** | 新 OLE 框架的寬度，單位為點。 |
| height | **float** | 新 OLE 框架的高度，單位為點。 |
| class_name | **str** | OLE 物件的類別名稱。 |
| path | **str** | 連結檔案的路徑。 <br/><br/>此路徑會以原樣儲存在簡報中。<br/><br/>如果指定相對路徑，當從不同目錄開啟簡報時，檔案將無法存取。 |

### 另見
* 類別 [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo)
* 類別 [`IOleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/ioleobjectframe)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)