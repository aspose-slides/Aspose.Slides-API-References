---
title: AddBlurEffect()
second_title: Aspose.Slides C++ API 參考
description: 將新的模糊效果新增至集合的末端。
type: docs
weight: 157
url: /zh-hant/aspose.slides.effects/imagetransformoperationcollection/addblureffect/
---
## ImageTransformOperationCollection::AddBlurEffect(double, bool) 方法

將新的 [Blur](../../blur/) 效果新增至集合的末端。

```cpp
System::SharedPtr<IBlur> Aspose::Slides::Effects::ImageTransformOperationCollection::AddBlurEffect(double radius, bool grow) override
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| radius | **double** | 模糊的半徑。 |
| grow | **bool** | 指定在模糊操作後物件的邊界是否應該擴大。True 表示邊界會被擴大，而 false 表示不會。 |

### 傳回值

集合中新圖像效果的索引。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IBlur](../../iblur/)
* 類別 [ImageTransformOperationCollection](../)
* 命名空間 [Aspose::Slides::Effects](../../)
* 函式庫 [Aspose.Slides](../../../)