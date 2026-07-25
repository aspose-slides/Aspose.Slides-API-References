---
title: AddFallBackFonts()
second_title: Aspose.Slides for C++ API リファレンス
description: FallBack フォントのリストに新しいフォントを追加します。
type: docs
weight: 79
url: /ja/aspose.slides/fontfallbackrule/addfallbackfonts/
---
## FontFallBackRule::AddFallBackFonts(System::String) メソッド

FallBack フォントの一覧に新しいフォントを追加します。

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::String fontName) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | FallBack 用のフォント名またはカンマで区切られた複数のフォント名 |
## 備考



```cpp
// FontFallBackRule の新しいインスタンスを作成
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//ルールに2番目のフォントを追加
newRule->AddFallBackFonts(u"MS Gothic");
//ルールに3番目と4番目のフォントを追加
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```

## FontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) メソッド

FallBack フォントの一覧に新しいフォントを追加します。

```cpp
void Aspose::Slides::FontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | FallBack 用のフォント名またはカンマで区切られた複数のフォント名 |
## 備考



```cpp
//FontFallBackRule の新しいインスタンスを作成
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//ルールに別の3つのフォントを追加
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [FontFallBackRule](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)