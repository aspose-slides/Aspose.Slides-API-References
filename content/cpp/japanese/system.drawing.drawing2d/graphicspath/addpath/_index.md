---
title: AddPath()
second_title: Aspose.Slides for C++ API リファレンス
description: 指定されたパスを、現在のオブジェクトが表すパスに追加します。
type: docs
weight: 222
url: /ja/system.drawing.drawing2d/graphicspath/addpath/
---
## GraphicsPath::AddPath(const SharedPtr\<GraphicsPath\>\&, bool) method

指定されたパスを、現在のオブジェクトが表すパスに追加します。

```cpp
void System::Drawing::Drawing2D::GraphicsPath::AddPath(const SharedPtr<GraphicsPath> &path, bool connect)
```

### 引数

| Parameter | Type | Description |
| --- | --- | --- |
| path | const [SharedPtr](../../../system/sharedptr/)\<[GraphicsPath](../)\>\& | 追加するパス |
| connect | **bool** | **True** は、**path** の最後の最初の図形が現在のオブジェクトが表すパスの最後の図形の一部であることを指定します。**false** は、**path** の最初の図形と現在のオブジェクトが表すパスの最後の図形が別々の図形であることを指定します |

## 参照

* Typedef [SharedPtr](../../../system/sharedptr/)
* クラス [GraphicsPath](../)
* 名前空間 [System::Drawing::Drawing2D](../../)
* ライブラリ [Aspose.Slides](../../../)