---
title: AddFallBackFonts()
second_title: Aspose.Slides C++ 用 API リファレンス
description: フォールバック フォントのリストに新しいフォント（複数可）を追加します。
type: docs
weight: 40
url: /ja/aspose.slides/ifontfallbackrule/addfallbackfonts/
---
## IFontFallBackRule::AddFallBackFonts(System::String) メソッド


フォールバック フォントのリストに新しいフォント（複数可）を追加します。

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::String fontName)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontName | [System::String](../../../system/string/) | フォールバック用のフォント名または名前（カンマで区切り） |
## 備考



```cpp
//FantFallBackRule の新しいインスタンスを作成
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//ルールに2番目のフォントを追加
newRule->AddFallBackFonts(u"MS Gothic");
//ルールに3番目と4番目のフォントを追加
newRule->AddFallBackFonts(u"Tahoma, Times New Roman");
```


## IFontFallBackRule::AddFallBackFonts(System::ArrayPtr\<System::String\>) メソッド


フォールバック フォントのリストに新しいフォントを追加します。

```cpp
virtual void Aspose::Slides::IFontFallBackRule::AddFallBackFonts(System::ArrayPtr<System::String> fontNames)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fontNames | [System::ArrayPtr](../../../system/arrayptr/)\<[System::String](../../../system/string/)\> | フォールバック用のフォント名または名前（カンマで区切り） |
## 備考



```cpp
//FontFallBackRule の新しいインスタンスを作成
auto newRule = MakeObject<FontFallBackRule>(0x3040, 0x309F, u"MS Mincho");
//ルールにさらに3つのフォントを追加
newRule->AddFallBackFonts(MakeArray<String>({u"MS Gothic", u"Tahoma, Times New Roman"}));
```


## 参照

* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [String](../../../system/string/)
* クラス [IFontFallBackRule](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)