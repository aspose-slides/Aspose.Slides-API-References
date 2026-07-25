---
title: SetSize()
second_title: Aspose.Slides の C++ API リファレンス
description: スライドのサイズをタイプで設定し、既存のコンテンツをスケーリングします。
type: docs
weight: 53
url: /ja/aspose.slides/slidesize/setsize/
---
## SlideSize::SetSize(SlideSizeType, SlideSizeScaleType) メソッド


スライドサイズをタイプで設定し、既存のコンテンツをスケーリングします。

```cpp
void Aspose::Slides::SlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | 適用する事前定義済みスライドサイズ。 |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 使用するコンテンツのスケーリングモード。 |
## 備考


[SlideSizeType::Custom](../../slidesizetype/) 以外の任意の値を割り当てると、選択されたタイプに基づいて [SlideSize::get_Size](../get_size/) が調整され、[SlideSize::get_Orientation](../get_orientation/) が保持されます。 

## SlideSize::SetSize(float, float, SlideSizeScaleType) メソッド


スライドの寸法を明示的に設定し、既存のコンテンツをスケーリングします。

```cpp
void Aspose::Slides::SlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType) override
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| width | **float** | ポイント単位の新しいスライド幅。 |
| height | **float** | ポイント単位の新しいスライド高さ。 |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 使用するコンテンツのスケーリングモード。 |
## 備考


これにより、[SlideSize::get_Type](../get_type/) プロパティが [SlideSizeType::Custom](../../slidesizetype/) にリセットされ、[Orientation](../../orientation/) が設定されます。 

## 参照

* 列挙体 [SlideSizeType](../../slidesizetype/)
* 列挙体 [SlideSizeScaleType](../../slidesizescaletype/)
* クラス [SlideSize](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)