---
title: RemoveScriptFont()
second_title: Aspose.Slides for C++ API リファレンス
description: テーマのフォントコレクションから特定のスクリプトタグに関連付けられたフォント設定を削除します。
type: docs
weight: 118
url: /ja/aspose.slides/fonts/removescriptfont/
---
## Fonts::RemoveScriptFont(System::String) メソッド


テーマのフォントコレクションから、特定のスクリプトタグに関連付けられたフォント設定を削除します。

```cpp
void Aspose::Slides::Fonts::RemoveScriptFont(System::String script) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| script | [System::String](../../../system/string/) | フォント設定を削除すべき BCP-47 スクリプトコード。 |
## 備考



この例は、ヘブライ語スクリプトのフォントマッピングを削除する方法を示しています:
```cpp
presentation->get_MasterTheme()->get_FontScheme()->get_Major()->RemoveScriptFont(u"Hebr");
```

## 参照

* クラス [String](../../../system/string/)
* クラス [Fonts](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)