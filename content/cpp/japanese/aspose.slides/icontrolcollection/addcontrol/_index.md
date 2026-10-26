---
title: AddControl()
second_title: Aspose.Slides for C++ API リファレンス
description: 新しいコントロールを作成し、コレクションに追加します。
type: docs
weight: 53
url: /ja/aspose.slides/icontrolcollection/addcontrol/
---
## IControlCollection::AddControl(ControlType, float, float, float, float) メソッド

新しいコントロールを作成し、コレクションに追加します。

```cpp
virtual System::SharedPtr<IControl> Aspose::Slides::IControlCollection::AddControl(ControlType controlType, float x, float y, float width, float height)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| controlType | [ControlType](../../controltype/) | 追加するコントロールのタイプ。 |
| x | **float** | シェイプのフレーム左側の X 座標。 |
| y | **float** | シェイプのフレーム上側の Y 座標。 |
| width | **float** | シェイプのフレームの幅。 |
| height | **float** | シェイプのフレームの高さ。 |

### 戻り値

作成されたコントロール [IControl](../../icontrol/)。

## 参照

* 列挙型 [ControlType](../../controltype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [IControl](../../icontrol/)
* クラス [IControlCollection](../)
* 名前空間 [Aspose::Slides](../../)
* ライブラリ [Aspose.Slides](../../../)