---
title: BeginContainer()
second_title: Aspose.Slides for C++ APIリファレンス
description: このオブジェクトの現在の状態を保持したコンテナを保存し、新しいコンテナを開いて使用し、保存したコンテナを返します。
type: docs
weight: 976
url: /ja/system.drawing/graphics/begincontainer/
---
## Graphics::BeginContainer() メソッド

現在のオブジェクトの状態を保持したコンテナを保存し、新しいコンテナを開いて使用し、保存したコンテナを返します。

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer()
```

## Graphics::BeginContainer(Rectangle, Rectangle, GraphicsUnit) メソッド

現在のオブジェクトの状態を保持したコンテナを保存し、新しいコンテナを開いて使用し、保存したコンテナを返します。

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(Rectangle dstrect, Rectangle srcrect, GraphicsUnit unit)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dstrect | [Rectangle](../../rectangle/) | 新しいコンテナのスケール変換を指定する矩形です。**srcrect** と一緒に使用します |
| srcrect | [Rectangle](../../rectangle/) | 新しいコンテナのスケール変換を指定する矩形です。**dstrect** と一緒に使用します |
| unit | [GraphicsUnit](../../graphicsunit/) | 新しいコンテナの測定単位を指定する値です |

## Graphics::BeginContainer(RectangleF, RectangleF, GraphicsUnit) メソッド

現在のオブジェクトの状態を保持したコンテナを保存し、新しいコンテナを開いて使用し、保存したコンテナを返します。

```cpp
SharedPtr<Drawing2D::GraphicsContainer> System::Drawing::Graphics::BeginContainer(RectangleF dstrect, RectangleF srcrect, GraphicsUnit unit)
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| dstrect | [RectangleF](../../rectanglef/) | 新しいコンテナのスケール変換を指定する矩形です。**srcrect** と一緒に使用します |
| srcrect | [RectangleF](../../rectanglef/) | 新しいコンテナのスケール変換を指定する矩形です。**dstrect** と一緒に使用します |
| unit | [GraphicsUnit](../../graphicsunit/) | 新しいコンテナの測定単位を指定する値です |

## 参考

* 列挙体 [GraphicsUnit](../../graphicsunit/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [GraphicsContainer](../../../system.drawing.drawing2d/graphicscontainer/)
* クラス [Graphics](../)
* クラス [Rectangle](../../rectangle/)
* クラス [RectangleF](../../rectanglef/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)