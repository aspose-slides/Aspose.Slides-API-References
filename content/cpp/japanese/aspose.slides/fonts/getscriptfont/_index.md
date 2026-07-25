---
title: GetScriptFont()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのテーマから特定のスクリプトタグに関連付けられたフォント名を取得します。
type: docs
weight: 92
url: /ja/aspose.slides/fonts/getscriptfont/
---
## Fonts::GetScriptFont(System::String) メソッド


プレゼンテーションテーマから特定のスクリプトタグに関連付けられたフォント名を取得します。

```cpp
System::String Aspose::Slides::Fonts::GetScriptFont(System::String script) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | 書記体系を識別するために使用される BCP-47 スクリプトコード (例: \"Latn\", \"Cyrl\", \"Jpan\") です。 |

### 戻り値

指定されたスクリプトで使用されるフォント名を返します。スクリプトが定義されていない場合は **null** が返されます。
## 備考



この例は、プレゼンテーションテーマでキリル文字スクリプトに割り当てられたフォントを取得する方法を示しています。
```cpp
System::String font = presentation->get_MasterTheme()->get_FontScheme()->get_Major()->GetScriptFont(u"Cyrl");
System::Console::WriteLine(System::String(u"Font for Cyrillic script: ") + font);
```

## 参照

* クラス [String](../../../system/string/)
* クラス [Fonts](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)