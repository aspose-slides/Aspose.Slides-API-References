---
title: Remove()
second_title: Aspose.Slides for C++ API リファレンス
description: リストから特定のFallBackフォントの最初の出現を削除します。
type: docs
weight: 118
url: /ja/aspose.slides/fontfallbackrule/remove/
---
## FontFallBackRule::Remove(System::String) メソッド


リストから特定のFallBackフォントの最初の出現を削除します。

```cpp
void Aspose::Slides::FontFallBackRule::Remove(System::String fontName) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | リストから削除するフォントの名前。 |
## 備考


```cpp
// フォントのリストを含むルールを作成します。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// リストからTahomaを削除します。
newRule->Remove(u"Tahoma");
```


## 関連項目

* クラス [String](../../../system/string/)
* クラス [FontFallBackRule](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)