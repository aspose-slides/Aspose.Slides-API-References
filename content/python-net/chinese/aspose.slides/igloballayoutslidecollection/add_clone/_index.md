---
title: add_clone method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/igloballayoutslidecollection/add_clone/
weight: 20
---
## add_clone(self, source_layout) {#ilayoutslide}
向演示文稿添加指定布局幻灯片的副本。

### 返回
已添加的幻灯片。

```python
def add_clone(self, source_layout):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide) | 要克隆的幻灯片。 |

### 备注
在不同演示文稿之间克隆布局时，布局的母版也可能被克隆，以保留源格式。
内部注册表用于跟踪自动克隆的母版，防止创建同一母版幻灯片的多个克隆。
手动克隆母版幻灯片既不会被阻止，也不会被注册。

## add_clone(self, source_layout, dest_master) {#ilayoutslide-imasterslide}
向演示文稿添加指定布局幻灯片的副本。

### 返回
已添加的幻灯片。

```python
def add_clone(self, source_layout, dest_master):
    ...
```

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| source_layout | [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide) | 要克隆的幻灯片。 |
| dest_master | [`IMasterSlide`](/slides/python-net/zh/aspose.slides/imasterslide) | 新布局的母版幻灯片。 |

### 备注
新布局将与目标演示文稿中定义的母版关联。
因此，这相当于在 PowerPoint 中使用“使用目标主题”选项进行复制/粘贴。

### 另见
* 类 [`IGlobalLayoutSlideCollection`](/slides/python-net/zh/aspose.slides/igloballayoutslidecollection)
* 类 [`ILayoutSlide`](/slides/python-net/zh/aspose.slides/ilayoutslide)
* 类 [`IMasterSlide`](/slides/python-net/zh/aspose.slides/imasterslide)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)