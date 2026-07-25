---
title: AddControl()
second_title: Aspose.Slides の C++ API リファレンス
description: コレクションに新しいコントロールを作成して追加します。
type: docs
weight: 40
url: /ja/aspose.slides/controlcollection/addcontrol/
---
## ControlCollection::AddControl(ControlType, float, float, float, float) メソッド

新しいコントロールを作成し、コレクションに追加します。

```cpp
System::SharedPtr<IControl> Aspose::Slides::ControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height) override
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | 追加するコントロールのタイプ。 |
| x | **float** | シェイプのフレームの左側の X 座標。 |
| y | **float** | シェイプのフレームの上側の Y 座標。 |
| width | **float** | シェイプのフレームの幅。 |
| height | **float** | シェイプのフレームの高さ。 |

### 戻り値

作成されたコントロール。

## 参照

* 列挙型 [ControlType](../../controltype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IControl](../../icontrol/)
* クラス [ControlCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)