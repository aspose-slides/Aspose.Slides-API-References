---
title: GetScriptFontMap()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーション内のすべてのスクリプトフォント定義の辞書を返します。
type: docs
weight: 79
url: /ja/aspose.slides/fonts/getscriptfontmap/
---
## Fonts::GetScriptFontMap() メソッド


プレゼンテーション内のすべてのスクリプトフォント定義の辞書を返します。

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::Fonts::GetScriptFontMap() override
```


### 戻り値

スクリプトコードをフォント名にマッピングする辞書。

## 備考




```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## 関連項目

* typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IDictionary](../../../system.collections.generic/idictionary/)
* クラス [String](../../../system/string/)
* クラス [Fonts](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)