---
title: Insert()
second_title: Aspose.Slides for C++ API リファレンス
description: パスに新しいコマンドを挿入します
type: docs
weight: 27
url: /ja/aspose.slides.animation/imotionpath/insert/
---
## IMotionPath::Insert(int32_t, MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) メソッド

パスに新しいコマンドを挿入します

```cpp
virtual void Aspose::Slides::Animation::IMotionPath::Insert(int32_t index, MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### 引数

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| index | **int32_t** | コマンド挿入用インデックス **int32_t** |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | アニメーションの動作効果のコマンドの種類 [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | ポイント配列 [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | アニメーションの動きパスにおけるポイントの種類 [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | 相対座標を使用するかどうかを示します **bool** |

## 参照

* 列挙体 [MotionCommandPathType](../../motioncommandpathtype/)
* 列挙体 [MotionPathPointsType](../../motionpathpointstype/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [PointF](../../../system.drawing/pointf/)
* クラス [IMotionPath](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)