---
title: GraphicsPath()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定された塗りつぶしモードでGraphicsPathクラスの新しいインスタンスを構築します。
type: docs
weight: 1
url: /ja/system.drawing.drawing2d/graphicspath/graphicspath/
---
## GraphicsPath::GraphicsPath(FillMode) コンストラクタ


[GraphicsPath](../) クラスの新しいインスタンスを、指定された塗りつぶしモードで構築します。

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(FillMode fillMode=FillMode::Alternate)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| fillMode | [FillMode](../../fillmode/) | 作成中のオブジェクトが表す閉じたパスの内部をどのように塗りつぶすかを指定します |

## GraphicsPath::GraphicsPath(const ArrayPtr\<Point\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) コンストラクタ


[GraphicsPath](../) オブジェクトの新しいインスタンスを、指定されたパスを表すように構築します。

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<Point> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[Point](../../../system.drawing/point/)\>\& | 作成中のオブジェクトが表すパスを指定する点を含む配列 |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | **pts** 配列中の対応する点のタイプを指定する値を含む配列 |
| fillMode | [FillMode](../../fillmode/) | 作成中のオブジェクトが表す閉じたパスの内部をどのように塗りつぶすかを指定します |

## GraphicsPath::GraphicsPath(const ArrayPtr\<PointF\>\&, const ArrayPtr\<uint8_t\>\&, FillMode) コンストラクタ


[GraphicsPath](../) オブジェクトの新しいインスタンスを、指定されたパスを表すように構築します。

```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const ArrayPtr<PointF> &pts, const ArrayPtr<uint8_t> &types, FillMode fillMode=FillMode::Alternate)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| pts | const [ArrayPtr](../../../system/arrayptr/)\<[PointF](../../../system.drawing/pointf/)\>\& | 作成中のオブジェクトが表すパスを指定する点を含む配列 |
| types | const [ArrayPtr](../../../system/arrayptr/)\<**uint8_t**\>\& | **pts** 配列中の対応する点のタイプを指定する値を含む配列 |
| fillMode | [FillMode](../../fillmode/) | 作成中のオブジェクトが表す閉じたパスの内部をどのように塗りつぶすかを指定します |

## GraphicsPath::GraphicsPath(const SkPath\&) コンストラクタ




```cpp
System::Drawing::Drawing2D::GraphicsPath::GraphicsPath(const SkPath &path)
```

## 参照

* 列挙体 [FillMode](../../fillmode/)
* タイプ定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [GraphicsPath](../)
* クラス [Point](../../../system.drawing/point/)
* クラス [PointF](../../../system.drawing/pointf/)
* 名前空間 [System::Drawing::Drawing2D](../../)
* ライブラリ [Aspose.Slides](../../../)