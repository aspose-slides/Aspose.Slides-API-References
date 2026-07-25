---
title: SetScriptFont()
second_title: Aspose.Slides for C++ API リファレンス
description: 特定のスクリプトタグにフォント名を割り当てます。このタグは、そのスクリプトのテキストがプレゼンテーションでどのように描画されるかを定義します。
type: docs
weight: 105
url: /ja/aspose.slides/fonts/setscriptfont/
---
## Fonts::SetScriptFont(System::String, System::String) メソッド

特定のスクリプトタグにフォント名を割り当てます。このタグは、そのスクリプトのテキストがプレゼンテーションでどのように描画されるかを定義します。

```cpp
void Aspose::Slides::Fonts::SetScriptFont(System::String script, System::String fontName) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | BCP-47 スクリプトコード（例: "Arab", "Hebr", "Hans"）で、書記体系を識別します。 |
| fontName | [System::String](../../../system/string/) | 指定されたスクリプトに割り当てるフォントの名前。 |
## 備考

この例は、アラビア文字スクリプトのフォントを "Segoe UI" に設定する方法を示しています:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->SetScriptFont(u"Arab", u"Segoe UI");
```

## 参照

* クラス [String](../../../system/string/)
* クラス [Fonts](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)