---
title: CustomLineCap()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたプロパティを持つユーザー定義のラインキャップを表す CustomLineCap クラスの新しいインスタンスを作成します。
type: docs
weight: 1
url: /ja/system.drawing.drawing2d/customlinecap/customlinecap/
---
## CustomLineCap::CustomLineCap(const SharedPtr\<GraphicsPath\>\&, const SharedPtr\<GraphicsPath\>\&, LineCap, float) コンストラクタ

[CustomLineCap](../) クラスの新しいインスタンスを作成します。このクラスは、指定されたプロパティを持つユーザー定義のラインキャップを表します。

```cpp
System::Drawing::Drawing2D::CustomLineCap::CustomLineCap(const SharedPtr<GraphicsPath> &fillPath, const SharedPtr<GraphicsPath> &strokePath, LineCap baseCap=LineCap::Flat, float baseInset=0)
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fillPath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | カスタムキャップの塗りを指定します |
| strokePath | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../../graphicspath/)\>\& | カスタムキャップの輪郭を指定します |
| baseCap | [LineCap](../../linecap/) | カスタムキャップが作成されるベースのラインキャップ |
| baseInset | **float** | ラインとキャップ間の距離を指定します |

## 参照

* 列挙体 [LineCap](../../linecap/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [GraphicsPath](../../graphicspath/)
* クラス [CustomLineCap](../)
* 名前空間 [System::Drawing::Drawing2D](../../)
* ライブラリ [Aspose.Slides](../../../)