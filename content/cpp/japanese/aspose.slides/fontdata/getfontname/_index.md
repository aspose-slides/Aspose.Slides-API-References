---
title: GetFontName()
second_title: Aspose.Slides for C++ API リファレンス
description: テーマ参照を実際に使用されているフォントに置き換えて、フォント名を返します。
type: docs
weight: 27
url: /ja/aspose.slides/fontdata/getfontname/
---
## FontData::GetFontName(System::SharedPtr\<Theme::IThemeEffectiveData\>) メソッド

テーマ参照を実際に使用されているフォントに置き換えて、フォント名を返します。

```cpp
System::String Aspose::Slides::FontData::GetFontName(System::SharedPtr<Theme::IThemeEffectiveData> theme) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| theme | [System::SharedPtr](../../../system/sharedptr/)\<[Theme::IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)\> | [Theme](../../../aspose.slides.theme/) からテーマ化されたフォント名を取得します。呼び出し元が正しい値を提供する必要があります。[IThemeable::CreateThemeEffective()](../../../aspose.slides.theme/ithemeable/createthemeeffective/) を参照してください。 |

### 戻り値

フォント名。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [String](../../../system/string/)
* クラス [IThemeEffectiveData](../../../aspose.slides.theme/ithemeeffectivedata/)
* クラス [FontData](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)