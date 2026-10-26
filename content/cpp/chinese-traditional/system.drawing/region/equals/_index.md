---
title: Equals()
second_title: Aspose.Slides for C++ API 參考文件
description: 判斷指定的區域是否與在指定繪圖表面上由當前物件所表示的區域相同。
type: docs
weight: 157
url: /zh-hant/system.drawing/region/equals/
---
## Region::Equals(const SharedPtr\<Region\>\&, const SharedPtr\<Graphics\>\&) 方法

判斷指定的區域是否與在指定繪圖表面上由當前物件所表示的區域相同。

```cpp
bool System::Drawing::Region::Equals(const SharedPtr<Region> &r, const SharedPtr<Graphics> &g)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| r | const [SharedPtr](../../../system/sharedptr/)\<[Region](../)\>\& | 要與本區域比較的區域 |
| g | const [SharedPtr](../../../system/sharedptr/)\<[Graphics](../../graphics/)\>\& | 繪圖表面 |

### 回傳值

若指定區域的內部與在套用 **g** 參數相關的變換後，由目前物件所代表的區域的內部相同，則傳回 true；否則傳回 false

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [Region](../)
* 類別 [Graphics](../../graphics/)
* 命名空間 [System::Drawing](../../)
* 函式庫 [Aspose.Slides](../../../)