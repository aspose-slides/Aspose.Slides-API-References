---
title: GetScriptFontMap()
second_title: Aspose.Slides for C++ API 參考
description: 返回簡報中所有腳本字型定義的字典。
type: docs
weight: 79
url: /zh-hant/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() 方法

返回簡報中所有腳本字型定義的字典。

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```

### 返回值

將腳本代碼映射到字型名稱的字典。

## 備註

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDictionary](../../../system.collections.generic/idictionary/)
* 類別 [String](../../../system/string/)
* 類別 [Fonts](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)