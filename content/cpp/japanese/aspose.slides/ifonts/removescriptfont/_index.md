---
title: RemoveScriptFont()
second_title: Aspose.Slides for C++ API リファレンス
description: テーマのフォントコレクションから特定のスクリプトタグに関連付けられたフォント設定を削除します。
type: docs
weight: 118
url: /ja/aspose.slides/ifonts/removescriptfont/
---
## IFonts::RemoveScriptFont(System::String) メソッド

特定のスクリプトタグに関連付けられたフォント設定を、テーマのフォントコレクションから削除します。

```cpp
virtual void Aspose::Slides::IFonts::RemoveScriptFont(System::String script)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | フォント設定を削除すべき BCP-47 スクリプトコード。 |
## 備考

この例は、ヘブライ語スクリプトのフォントマッピングを削除する方法を示しています。 
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## 関連項目

* クラス [String](../../../system/string/)
* クラス [IFonts](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)