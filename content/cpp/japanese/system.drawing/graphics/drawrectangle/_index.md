---
title: DrawRectangle()
second_title: Aspose.Slides for C++ API リファレンス
description: 現在のオブジェクトが表すサーフェス上に、指定されたペンを使用して指定された長方形を描画します。
type: docs
weight: 287
url: /ja/system.drawing/graphics/drawrectangle/
---
## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, int, int, int, int) メソッド

現在のオブジェクトが表すサーフェス上に、指定されたペンを使用して指定された長方形を描画します。

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, int x, int y, int width, int height)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 長方形を描画する際に使用するペンです |
| x | int | 描画する長方形の左上隅の X 座標 |
| y | int | 描画する長方形の左上隅の Y 座標 |
| width | int | 描画する長方形の幅 |
| height | int | 描画する長方形の高さ |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, float, float, float, float) メソッド

現在のオブジェクトが表すサーフェス上に、指定されたペンを使用して指定された長方形を描画します。

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, float x, float y, float width, float height)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 長方形を描画する際に使用するペンです |
| x | **float** | 描画する長方形の左上隅の X 座標 |
| y | **float** | 描画する長方形の左上隅の Y 座標 |
| width | **float** | 描画する長方形の幅 |
| height | **float** | 描画する長方形の高さ |

## Graphics::DrawRectangle(const SharedPtr\<Pen\>\&, Rectangle) メソッド

現在のオブジェクトが表すサーフェス上に、指定されたペンを使用して指定された長方形を描画します。

```cpp
void System::Drawing::Graphics::DrawRectangle(const SharedPtr<Pen> &pen, Rectangle rect)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| pen | const [SharedPtr](../../../system/sharedptr/)\<[Pen](../../pen/)\>\& | 長方形を描画する際に使用するペンです |
| rect | [Rectangle](../../rectangle/) | 描画する長方形の位置とサイズを指定する [Rectangle](../../rectangle/) オブジェクト |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Pen](../../pen/)
* Class [Graphics](../)
* Class [Rectangle](../../rectangle/)
* Namespace [System::Drawing](../../)
* Library [Aspose.Slides](../../../)