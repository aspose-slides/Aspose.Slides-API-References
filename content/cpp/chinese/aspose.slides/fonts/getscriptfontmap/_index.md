---
title: GetScriptFontMap()
second_title: Aspose.Slides C++ API 参考
description: 返回演示文稿中所有脚本字体定义的字典。
type: docs
weight: 79
url: /zh/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() 方法


返回演示文稿中所有脚本字体定义的字典。

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### 返回值

一个将脚本代码映射到字体名称的字典。
## 备注




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## 另见

* 类型定义 [SharedPtr](../../../system/sharedptr/)
* 类 [IDictionary](../../../system.collections.generic/idictionary/)
* 类 [String](../../../system/string/)
* 类 [Fonts](../)
* 命名空间 [Aspose::Slides](../../)
* 库 [Aspose.Slides](../../../)