---
title: GetScriptFont()
second_title: Aspose.Slides C++ API 参考
description: 获取演示文稿主题中与特定脚本标签关联的字体名称。
type: docs
weight: 92
url: /zh/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) 方法


获取演示文稿主题中与特定脚本标签关联的字体名称。

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```


### 参数

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 用于标识书写系统的 BCP-47 脚本代码（例如 "Latn", "Cyrl", "Jpan"）。 |

### 返回值

指定脚本使用的字体名称；如果未定义该脚本，则为 **null**。
## 备注



此示例演示如何检索演示文稿主题中分配给西里尔文脚本的字体。
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## 另见

* 类 [String](../../../system/string/)
* 类 [IFonts](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)