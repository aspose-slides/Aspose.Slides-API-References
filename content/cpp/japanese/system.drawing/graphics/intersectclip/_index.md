---
title: IntersectClip()
second_title: Aspose.Slides for C++ API リファレンス
description: このオブジェクトのクリップ領域を、現在のクリップと指定されたクリップの交差に更新します。
type: docs
weight: 950
url: /ja/system.drawing/graphics/intersectclip/
---
## Graphics::IntersectClip(const System::SharedPtr\<Region\>\&) メソッド

このオブジェクトのクリップ領域を、現在のクリップと指定されたクリップの交差に更新します。

```cpp
void System::Drawing::Graphics::IntersectClip(const System::SharedPtr<Region> &region)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| region | const [System::SharedPtr](../../../system/sharedptr/)\<[Region](../../region/)\>\& | 交差させる領域 |

## Graphics::IntersectClip(System::Drawing::RectangleF) メソッド

このオブジェクトのクリップ領域を、現在のクリップと指定されたクリップの交差に更新します。

```cpp
void System::Drawing::Graphics::IntersectClip(System::Drawing::RectangleF rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | [System::Drawing::RectangleF](../../rectanglef/) | 交差させる矩形 |

## Graphics::IntersectClip(System::Drawing::Rectangle) メソッド

このオブジェクトのクリップ領域を、現在のクリップと指定されたクリップの交差に更新します。

```cpp
void System::Drawing::Graphics::IntersectClip(System::Drawing::Rectangle rect)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| rect | [System::Drawing::Rectangle](../../rectangle/) | 交差させる矩形 |

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Region](../../region/)
* クラス [Graphics](../)
* クラス [RectangleF](../../rectanglef/)
* クラス [Rectangle](../../rectangle/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)