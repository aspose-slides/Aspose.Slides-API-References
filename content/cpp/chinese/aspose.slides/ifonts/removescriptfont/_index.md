---
title: RemoveScriptFont()
second_title: Aspose.Slides for C++ API 参考
description: 从主题的字体集合中移除与特定脚本标签关联的字体设置。
type: docs
weight: 118
url: /zh/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) 方法

从主题的字体集合中移除与特定脚本标签关联的字体设置。

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 应移除其字体设置的 BCP-47 脚本代码。 |
## 备注

此示例演示如何移除希伯来语脚本的字体映射：
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## 另见

* 类 [String](../../../system/string/)
* 类 [IFonts](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)