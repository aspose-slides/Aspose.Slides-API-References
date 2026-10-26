---
title: GetScriptFont()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションテーマから特定のスクリプトタグに関連付けられたフォント名を取得します。
type: docs
weight: 92
url: /ja/aspose.slides/ifonts/getscriptfont/
---
## IFonts::GetScriptFont(System::String) メソッド


プレゼンテーションテーマから特定のスクリプトタグに関連付けられたフォント名を取得します。

```cpp
virtual System::String Aspose::Slides::IFonts::GetScriptFont(System::String script)=0
```


### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 書字体系を識別するために使用される BCP-47 スクリプトコード（例: "Latn", "Cyrl", "Jpan"）です。 |

### 戻り値

指定されたスクリプトで使用されるフォント名、またはスクリプトが定義されていない場合は **null** が返されます。

## 備考



この例は、プレゼンテーションテーマでキリル文字スクリプトに割り当てられたフォントを取得する方法を示しています。 
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## 関連項目

* クラス [String](../../../system/string/)
* クラス [IFonts](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)