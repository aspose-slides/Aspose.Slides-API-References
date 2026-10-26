---
title: AddBiLevelEffect()
second_title: Aspose.Slides for C++ API 參考
description: 將新的雙階層（黑/白）效果新增至集合的末端。
type: docs
weight: 118
url: /zh-hant/aspose.slides.effects/iimagetransformoperationcollection/addbileveleffect/
---
## IImageTransformOperationCollection::AddBiLevelEffect(float) 方法

將新的雙階層（黑/白）效果新增至集合的末端。

```cpp
virtual System::SharedPtr<IBiLevel> Aspose::Slides::Effects::IImageTransformOperationCollection::AddBiLevelEffect(float threshold)=0
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| threshold | **float** | Bi-Level 效果的亮度門檻。大於或等於門檻的值會被設為白色。小於門檻的值會被設為黑色。 |

### 返回值

新圖像效果在集合中的索引。

## 另請參閱

* 型別定義 [SharedPtr](../../../system/sharedptr/)
* 類別 [IBiLevel](../../ibilevel/)
* 類別 [IImageTransformOperationCollection](../)
* 命名空間 [Aspose::Slides::Effects](../../)
* 函式庫 [Aspose.Slides](../../../)