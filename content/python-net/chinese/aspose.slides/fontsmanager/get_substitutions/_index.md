---
title: get_substitutions method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/fontsmanager/get_substitutions/
weight: 60
---
## get_substitutions(self) {#}
获取将在演示文稿渲染时被替换的字体信息。

### 返回

所有字体替换的集合 [`FontSubstitutionInfo`](/slides/python-net/zh/aspose.slides/fontsubstitutioninfo)。



```python
def get_substitutions(self):
    ...
```



## get_substitutions(self, slides) {#listint}
获取将在指定幻灯片渲染期间被替换的字体信息。

### 返回

针对指定幻灯片的所有字体替换的集合 ([`FontSubstitutionInfo`](/slides/python-net/zh/aspose.slides/fontsubstitutioninfo))。



```python
def get_substitutions(self, slides):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| slides | **List[int]** | 一个用于检索字体替换信息的幻灯片索引数组，索引从 1 开始。 |



### 另见
* 类 [`FontsManager`](/slides/python-net/zh/aspose.slides/fontsmanager)
* 类 [`FontSubstitutionInfo`](/slides/python-net/zh/aspose.slides/fontsubstitutioninfo)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)