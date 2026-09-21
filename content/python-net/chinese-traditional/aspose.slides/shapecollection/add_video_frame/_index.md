---
title: add_video_frame method
second_title: Aspose.Slides for Python via .NET API 參考
description: 
type: docs
url: /zh-hant/aspose.slides/shapecollection/add_video_frame/
weight: 160
---
## add_video_frame(self, x, y, width, height, fname) {#float-float-float-float-str}
建立一個新的影片框並將其加入形狀集合的末端。

### Returns

新建立的 [`IVideoFrame`](/slides/python-net/zh-hant/aspose.slides/ivideoframe)。

```python
def add_video_frame(self, x, y, width, height, fname):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | 新影片框的 x 座標，單位為點。 |
| y | **float** | 新影片框的 y 座標，單位為點。 |
| width | **float** | 新影片框的寬度，單位為點。 |
| height | **float** | 新影片框的高度，單位為點。 |
| fname | **str** | 要嵌入的影片檔案的路徑或名稱。 |

## add_video_frame(self, x, y, width, height, video) {#float-float-float-float-ivideo}
建立一個新的影片框並將其加入形狀集合的末端。

### Returns

新建立的 [`IVideoFrame`](/slides/python-net/zh-hant/aspose.slides/ivideoframe)。

```python
def add_video_frame(self, x, y, width, height, video):
    ...
```

| Parameter | Type | Description |
| :- | :- | :- |
| x | **float** | 新影片框的 x 座標，單位為點。 |
| y | **float** | 新影片框的 y 座標，單位為點。 |
| width | **float** | 新影片框的寬度，單位為點。 |
| height | **float** | 新影片框的高度，單位為點。 |
| video | [`IVideo`](/slides/python-net/zh-hant/aspose.slides/ivideo) | 要嵌入於影片框的 [`IVideo`](/slides/python-net/zh-hant/aspose.slides/ivideo)。 |

### See Also
* 類別 [`IVideo`](/slides/python-net/zh-hant/aspose.slides/ivideo)
* 類別 [`IVideoFrame`](/slides/python-net/zh-hant/aspose.slides/ivideoframe)
* 類別 [`ShapeCollection`](/slides/python-net/zh-hant/aspose.slides/shapecollection)
* 模組 [`aspose.slides`](/slides/python-net/zh-hant/aspose.slides)
* 函式庫 [`Aspose.Slides`](/slides/python-net)