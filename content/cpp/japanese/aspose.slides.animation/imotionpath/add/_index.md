---
title: Add()
second_title: Aspose.Slides for C++ API リファレンス
description: パスに新しいコマンドを追加します
type: docs
weight: 14
url: /ja/aspose.slides.animation/imotionpath/add/
---
## IMotionPath::Add(MotionCommandPathType, System::ArrayPtr\<System::Drawing::PointF\>, MotionPathPointsType, bool) method

パスに新しいコマンドを追加します

```cpp
virtual System::SharedPtr<IMotionCmdPath> Aspose::Slides::Animation::IMotionPath::Add(MotionCommandPathType type, System::ArrayPtr<System::Drawing::PointF> pts, MotionPathPointsType ptsType, bool bRelativeCoord)=0
```

### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| type | [MotionCommandPathType](../../motioncommandpathtype/) | アニメーションのモーションエフェクト動作のコマンドのタイプ [MotionCommandPathType](../../motioncommandpathtype/) |
| pts | [System::ArrayPtr](../../../system/arrayptr/)\<[System::Drawing::PointF](../../../system.drawing/pointf/)\> | ポイント配列 [System::Drawing::PointF](../../../system.drawing/pointf/)[] |
| ptsType | [MotionPathPointsType](../../motionpathpointstype/) | アニメーションモーションパス内のポイントのタイプ [MotionPathPointsType](../../motionpathpointstype/) |
| bRelativeCoord | **bool** | 相対座標を使用するかどうかを示します **bool** |

### 戻り値

パスのコマンド [IMotionCmdPath](../../imotioncmdpath/)

## 参照

* 列挙体 [MotionCommandPathType](../../motioncommandpathtype/)
* 列挙体 [MotionPathPointsType](../../motionpathpointstype/)
* 型定義 [SharedPtr](../../../system/sharedptr/)
* 型定義 [ArrayPtr](../../../system/arrayptr/)
* クラス [IMotionCmdPath](../../imotioncmdpath/)
* クラス [PointF](../../../system.drawing/pointf/)
* クラス [IMotionPath](../)
* 名前空間 [Aspose::Slides::Animation](../../)
* ライブラリ [Aspose.Slides](../../../)