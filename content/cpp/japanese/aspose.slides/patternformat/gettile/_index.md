---
title: GetTile()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された色でパターン塗りつぶし用のタイル画像を作成します。
type: docs
weight: 53
url: /ja/aspose.slides/patternformat/gettile/
---
## PatternFormat::GetTile(System::Drawing::Color, System::Drawing::Color) method

指定された色でパターン塗りつぶし用のタイル画像を作成します。

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color background, System::Drawing::Color foreground) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| background | [System::Drawing::Color](../../../system.drawing/color/) | パターンの背景 [System::Drawing::Color](../../../system.drawing/color/) |
| foreground | [System::Drawing::Color](../../../system.drawing/color/) | パターンの前景 [System::Drawing::Color](../../../system.drawing/color/) |

### 戻り値

タイル [IImage](../../iimage/)。

## PatternFormat::GetTile(System::Drawing::Color) method

パターン塗りつぶし用のタイル画像を作成します。

```cpp
System::SharedPtr<IImage> Aspose::Slides::PatternFormat::GetTile(System::Drawing::Color styleColor) override
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| styleColor | [System::Drawing::Color](../../../system.drawing/color/) | デフォルトの [System::Drawing::Color](../../../system.drawing/color/) |

### 戻り値

タイル [IImage](../../iimage/)。

## 関連項目

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IImage](../../iimage/)
* クラス [Color](../../../system.drawing/color/)
* クラス [PatternFormat](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)