---
title: Equals()
second_title: Aspose.Slides C++ 用 API リファレンス
description: 指定された領域が、指定された描画サーフェス上の現在のオブジェクトが表す領域と同一であるかどうかを判断します。
type: docs
weight: 157
url: /ja/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) メソッド


指定された領域が、指定された描画サーフェス上の現在のオブジェクトが表す領域と同一であるかどうかを判断します。

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```


### 引数

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | この領域と比較する領域 |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 描画サーフェス |

### 戻り値

True if the interior of the specified region is identical to the interior of the region represented by the current objcet when the transformation associated with the **g** parameter is applied; otherwise - false

## 参照

* 型定義 [SharedPtr](../../../system/sharedptr/)
* クラス [Region](../)
* クラス [Graphics](../../graphics/)
* 名前空間 [System::Drawing](../../)
* ライブラリ [Aspose.Slides](../../../)