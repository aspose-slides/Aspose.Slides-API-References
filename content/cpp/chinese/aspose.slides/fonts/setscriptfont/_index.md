---
title: SetScriptFont()
second_title: Aspose.Slides C++ API 参考
description: 为特定脚本标签分配字体名称，以定义该脚本的文本在演示文稿中的呈现方式。
type: docs
weight: 105
url: /zh/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) 方法

为特定的脚本标签分配字体名称，定义该脚本的文本在演示文稿中的呈现方式。

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47 脚本代码（例如 "Arab", "Hebr", "Hans"），用于标识书写系统。 |
| fontName | [System::String](../../../system/string/) | 要分配给指定脚本的字体名称。 |
## 备注

此示例展示如何将阿拉伯脚本的字体设置为 "Segoe UI"：
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## 另请参见

* 类 [String](../../../system/string/)
* 类 [Fonts](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)