---
title: IndexOf()
second_title: Aspose.Slides for C++ API リファレンス
description: コレクション内の指定されたルールのインデックスを返します。
type: docs
weight: 157
url: /ja/aspose.slides/fontfallbackrule/indexof/
---
## FontFallBackRule::IndexOf(System::String) メソッド


指定されたルールのインデックスをコレクションから返します。

```cpp
int32_t Aspose::Slides::FontFallBackRule::IndexOf(System::String fontName) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | 検索するフォントの名前です。 |

### 戻り値

フォントのインデックス、またはリストにフォントが見つからない場合は -1。

## 備考



```cpp
// フォントのリストを含むルールを作成します。
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho, MS Gothic, Tahoma, Times New Roman");
// Tahoma のインデックスを取得します。
int32_t tahomaIndex = newRule->IndexOf(u"Tahoma");
```


## 参照

* クラス [String](../../../system/string/)
* クラス [FontFallBackRule](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)