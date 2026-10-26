---
title: get_substitutions method
second_title: Aspose.Slides for Python via .NET API 参考
description: 
type: docs
url: /zh/aspose.slides/ifontsmanager/get_substitutions/
weight: 60
---
## get_substitutions(self) {#}
获取在演示文稿渲染时将被替换的字体信息。

### 返回

所有字体替换的集合 [`FontSubstitutionInfo`](/slides/python-net/zh/aspose.slides/fontsubstitutioninfo).



```python
def get_substitutions(self):
    ...
```



## get_substitutions(self, slides) {#listint}
获取在指定幻灯片渲染期间将被替换的字体信息。

### 返回

为指定幻灯片提供的所有字体替换集合 ([`FontSubstitutionInfo`](/slides/python-net/zh/aspose.slides/fontsubstitutioninfo))。



```python
def get_substitutions(self, slides):
    ...
```


| 参数 | 类型 | 描述 |
| :- | :- | :- |
| slides | **List[int]** | 用于检索字体替换信息的幻灯片索引数组，起始值为 1。 |



### 另请参见
* 类 [`FontSubstitutionInfo`](/slides/python-net/zh/aspose.slides/fontsubstitutioninfo)
* 类 [`IFontsManager`](/slides/python-net/zh/aspose.slides/ifontsmanager)
* 模块 [`aspose.slides`](/slides/python-net/zh/aspose.slides)
* 库 [`Aspose.Slides`](/slides/python-net)