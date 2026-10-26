---
title: GetScriptFontMap()
second_title: Aspose.Slides for C++ API 參考
description: 傳回簡報中所有腳本字型定義的字典。
type: docs
weight: 79
url: /zh-hant/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() 方法


返回簡報中所有腳本字型定義的字典。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```


### 傳回值

一個將腳本代碼映射到字型名稱的字典。
## 備註




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## 另請參閱

* 類型別名 [SharedPtr](../../../system/sharedptr/)
* 類別 [IDictionary](../../../system.collections.generic/idictionary/)
* 類別 [String](../../../system/string/)
* 類別 [IFonts](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)