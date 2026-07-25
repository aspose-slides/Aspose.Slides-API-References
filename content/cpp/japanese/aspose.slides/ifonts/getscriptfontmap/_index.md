---
title: GetScriptFontMap()
second_title: C++ 用 Aspose.Slides API リファレンス
description: プレゼンテーション内のすべてのスクリプト フォント定義の辞書を返します。
type: docs
weight: 79
url: /ja/aspose.slides/ifonts/getscriptfontmap/
---
## IFonts::GetScriptFontMap() メソッド

プレゼンテーション内のすべてのスクリプト フォント定義の辞書を返します。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> Aspose::Slides::IFonts::GetScriptFontMap()=0
```

### 戻り値

スクリプト コードをフォント名にマッピングする辞書。

## 備考

```cpp
System::SharedPtr<System::Collections::Generic::IDictionary<System::String, System::String>> map = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFontMap();
for (auto&& kvp : map)
{
    System::Console::WriteLine(kvp.get_Key() + u" ? " + kvp.get_Value());
}
```

## 関連項目

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IDictionary](../../../system.collections.generic/idictionary/)
* クラス [String](../../../system/string/)
* クラス [IFonts](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)