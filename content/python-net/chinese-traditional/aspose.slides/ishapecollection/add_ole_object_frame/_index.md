---
title: add_ole_object_frame method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/add_ole_object_frame/
weight: 100
---
## add_ole_object_frame(self, x, y, width, height, data_info) {#float-float-float-float-ioleembeddeddatainfo}
建立新的 OLE 物件框架，並將它加入形狀集合的末端。

### 返回值

新建立的 [`IOleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/ioleobjectframe)。

```python
def add_ole_object_frame(self, x, y, width, height, data_info):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 新 OLE 框架的 x 座標，以點為單位。 |
| y | **float** | 新 OLE 框架的 y 座標，以點為單位。 |
| width | **float** | 新 OLE 框架的寬度，以點為單位。 |
| height | **float** | 新 OLE 框架的高度，以點為單位。 |
| data_info | [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo) | 嵌入的 OLE 資料資訊（[`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo)）。 |

## add_ole_object_frame(self, x, y, width, height, class_name, path) {#float-float-float-float-str-str}
建立新的 OLE 物件框架，並將它加入形狀集合的末端。

### 返回值

新建立的 [`IOleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/ioleobjectframe)。

```python
def add_ole_object_frame(self, x, y, width, height, class_name, path):
    ...
```

| 參數 | 類型 | 說明 |
| :- | :- | :- |
| x | **float** | 新 OLE 框架的 x 座標，以點為單位。 |
| y | **float** | 新 OLE 框架的 y 座標，以點為單位。 |
| width | **float** | 新 OLE 框架的寬度，以點為單位。 |
| height | **float** | 新 OLE 框架的高度，以點為單位。 |
| class_name | **str** | OLE 物件的類別名稱。 |
| path | **str** | 連結檔案的路徑。 <br/><br/>此路徑以原樣方式儲存在簡報中。<br/><br/>如果指定相對路徑，於從不同目錄開啟簡報時，檔案將無法存取。 |

### 另請參閱
* 類別 [`IOleEmbeddedDataInfo`](/slides/python-net/zh-hant/aspose.slides/ioleembeddeddatainfo)
* 類別 [`IOleObjectFrame`](/slides/python-net/zh-hant/aspose.slides/ioleobjectframe)
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)