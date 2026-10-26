---
title: add_video_frame method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/ishapecollection/add_video_frame/
weight: 160
---
## add_video_frame(self, x, y, width, height, fname) {#float-float-float-float-str}
建立新的影片框架，並將其加入形狀集合的末端。

### 回傳

新建立的 [`IVideoFrame`](/slides/python-net/zh-hant/aspose.slides/ivideoframe)。

```python
def add_video_frame(self, x, y, width, height, fname):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| x | **float** | 新影片框架的 x 座標，以點為單位。 |
| y | **float** | 新影片框架的 y 座標，以點為單位。 |
| width | **float** | 新影片框架的寬度，以點為單位。 |
| height | **float** | 新影片框架的高度，以點為單位。 |
| fname | **str** | 要嵌入的影片檔案路徑或名稱。 |

## add_video_frame(self, x, y, width, height, video) {#float-float-float-float-ivideo}
建立新的影片框架，並將其加入形狀集合的末端。

### 回傳

新建立的 [`IVideoFrame`](/slides/python-net/zh-hant/aspose.slides/ivideoframe)。

```python
def add_video_frame(self, x, y, width, height, video):
    ...
```

| 參數 | 類型 | 描述 |
| :- | :- | :- |
| x | **float** | 新影片框架的 x 座標，以點為單位。 |
| y | **float** | 新影片框架的 y 座標，以點為單位。 |
| width | **float** | 新影片框架的寬度，以點為單位。 |
| height | **float** | 新影片框架的高度，以點為單位。 |
| video | [`IVideo`](/slides/python-net/zh-hant/aspose.slides/ivideo) | 要嵌入影片框架的 [`IVideo`](/slides/python-net/zh-hant/aspose.slides/ivideo)。 |

### 另請參閱
* 類別 [`IShapeCollection`](/slides/python-net/zh-hant/aspose.slides/ishapecollection)
* 類別 [`IVideo`](/slides/python-net/zh-hant/aspose.slides/ivideo)
* 類別 [`IVideoFrame`](/slides/python-net/zh-hant/aspose.slides/ivideoframe)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)