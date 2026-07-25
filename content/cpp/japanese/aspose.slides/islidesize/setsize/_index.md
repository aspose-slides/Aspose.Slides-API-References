---
title: SetSize()
second_title: Aspose.Slides for C++ API リファレンス
description: "タイプでスライドサイズを設定し、既存のコンテンツを拡大縮小します。SlideSizeType::Custom 以外の任意の値を設定すると、選択されたタイプに基づいて ISlideSize::get_Size が調整され、ISlideSize::get_Orientation が保持されます。"
type: docs
weight: 53
url: /ja/aspose.slides/islidesize/setsize/
---
## ISlideSize::SetSize(SlideSizeType, SlideSizeScaleType) メソッド

スライドのサイズをタイプで設定し、既存のコンテンツを拡大縮小します。[SlideSizeType::Custom](../../slidesizetype/) 以外の任意の値を設定すると、選択されたタイプに基づいて [ISlideSize::get_Size](../get_size/) が調整され、[ISlideSize::get_Orientation](../get_orientation/) が保持されます。

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(SlideSizeType type, SlideSizeScaleType scaleType)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [SlideSizeType](../../slidesizetype/) | 適用する事前定義済みスライドサイズ。 |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 使用するコンテンツの拡大縮小モード。 |

## 備考

[SlideSizeType::Custom](../../slidesizetype/) 以外の任意の値を設定すると、選択されたタイプに基づいて [System::Drawing::Size](../../../system.drawing/size/) が調整され、[Orientation](../../orientation/) が保持されます。

## ISlideSize::SetSize(float, float, SlideSizeScaleType) メソッド

スライドの寸法を明示的に設定し、既存のコンテンツを拡大縮小します。この操作により、[ISlideSize::get_Type](../get_type/) の値が [SlideSizeType::Custom](../../slidesizetype/) にリセットされ、[ISlideSize::get_Orientation](../get_orientation/) が設定されます。

```cpp
virtual void Aspose::Slides::ISlideSize::SetSize(float width, float height, SlideSizeScaleType scaleType)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| width | **float** | ポイント単位の新しいスライド幅。 |
| height | **float** | ポイント単位の新しいスライド高さ。 |
| scaleType | [SlideSizeScaleType](../../slidesizescaletype/) | 使用するコンテンツの拡大縮小モード。 |

## 備考

この操作により、[ISlideSize::get_Type](../get_type/) プロパティが [SlideSizeType::Custom](../../slidesizetype/) にリセットされ、[Orientation](../../orientation/) が設定されます。

## 参照

* 列挙体 [SlideSizeType](../../slidesizetype/)
* 列挙体 [SlideSizeScaleType](../../slidesizescaletype/)
* クラス [ISlideSize](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)