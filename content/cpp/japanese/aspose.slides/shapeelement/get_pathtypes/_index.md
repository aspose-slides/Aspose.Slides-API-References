---
title: get_PathTypes()
second_title: Aspose.Slides for C++ API リファレンス
description: 要素のパス内の各ポイントのタイプを指定するバイト値の配列を取得します。
type: docs
weight: 27
url: /ja/aspose.slides/shapeelement/get_pathtypes/
---
## ShapeElement::get_PathTypes() メソッド

要素のパス内の各ポイントのタイプを指定する byte 値の配列を取得します。

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::ShapeElement::get_PathTypes()
```

## 備考

**0** ポイントが図形の開始点であることを示します。

**1** ポイントが直線の2つの端点のうちの1つであることを示します。

**3** ポイントが三次ベジエスプラインの端点または制御点であることを示します。

**7** 3ビットの低位ビットを除くすべてのビットをマスクします。低位ビットはポイントのタイプを示します。

**16** 対応するセグメントが破線であることを指定します。

**32** ポイントがマーカーであることを指定します。

**128** ポイントが閉じたサブパス（図形）の最後のポイントであることを指定します。

**129** ラインセグメントの端点であり、かつ閉じたサブパスの最後のポイントでもあるデータポイントであることを示します。

## 参照

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ShapeElement](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)