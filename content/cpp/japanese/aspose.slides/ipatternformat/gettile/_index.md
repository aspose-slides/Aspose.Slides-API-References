---
title: GetTile()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された色でパターン塗りつぶし用のタイル画像を作成します。
type: docs
weight: 53
url: /ja/aspose.slides/ipatternformat/gettile/
---
## IPatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) メソッド

指定された色でパターン塗りつぶし用のタイル画像を作成します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | パターンの背景 [System::Drawing::Color](../../../system.drawing/color/)。 |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | パターンの前景 [System::Drawing::Color](../../../system.drawing/color/)。 |

### 戻り値

タイル [System::Drawing::Bitmap](../../../system.drawing/bitmap/)。

## IPatternFormat::GetTile(System::Drawing::Color) メソッド

パターン塗りつぶし用のタイル画像を作成します。

```cpp
virtual System::SharedPtr<IImage> Aspose::Slides::IPatternFormat::GetTile(System::Drawing::Color styleColor)=0
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | ShapeEx の StyleEx オブジェクトで定義されたデフォルト [System::Drawing::Color](../../../system.drawing/color/)。塗りつぶしの色はこれに依存する可能性があります。 |

### 戻り値

タイル [System::Drawing::Bitmap](../../../system.drawing/bitmap/)。

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [IImage](../../iimage/)
* クラス [Color](../../../system.drawing/color/)
* クラス [IPatternFormat](../)
* 名前空間 [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)