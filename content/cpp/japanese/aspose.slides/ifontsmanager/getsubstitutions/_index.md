---
title: GetSubstitutions()
second_title: Aspose.Slides for C++ API リファレンス
description: プレゼンテーションのレンダリング時に置き換えられるフォントに関する情報を取得します。
type: docs
weight: 66
url: /ja/aspose.slides/ifontsmanager/getsubstitutions/
---
## IFontsManager::GetSubstitutions() メソッド

プレゼンテーションのレンダリング時に置き換えられるフォントに関する情報を取得します。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions()=0
```


### 戻り値

すべてのフォント置換のコレクション [FontSubstitutionInfo](../../fontsubstitutioninfo/)。

## 備考

```cpp
auto pres = System::MakeObject<Presentation>(u"pres.pptx");

for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions())
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```


## IFontsManager::GetSubstitutions(System::ArrayPtr\<int32_t\>) メソッド

指定されたスライドのレンダリング中に置き換えられるフォントに関する情報を取得します。

```cpp
virtual System::SharedPtr<System::Collections::Generic::IEnumerable<System::SharedPtr<FontSubstitutionInfo>>> Aspose::Slides::IFontsManager::GetSubstitutions(System::ArrayPtr<int32_t> slides)=0
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| slides | [System::ArrayPtr](../../../system/arrayptr/)\<**int32_t**\> | フォント置換情報を取得する対象スライドのインデックス配列（1 から開始）です。 |

### 戻り値

指定されたスライドのすべてのフォント置換のコレクション ([FontSubstitutionInfo](../../fontsubstitutioninfo/))。

## 備考

```cpp
System::SharedPtr<Presentation> pres = System::MakeObject<Presentation>(u"pres.pptx");
System::ArrayPtr<int32_t> targetSlides = System::MakeArray<int32_t>({1, 2, 5});
for (auto&& fontSubstitution : pres->get_FontsManager()->GetSubstitutions(targetSlides))
{
    System::Console::WriteLine(u"{0} -> {1}", fontSubstitution->get_OriginalFontName(), fontSubstitution->get_SubstitutedFontName());
}
```

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [IEnumerable](../../../system.collections.generic/ienumerable/)
* クラス [FontSubstitutionInfo](../../fontsubstitutioninfo/)
* クラス [IFontsManager](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)