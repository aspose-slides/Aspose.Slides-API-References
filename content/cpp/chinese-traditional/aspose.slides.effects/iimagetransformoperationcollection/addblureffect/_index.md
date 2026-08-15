---
title: AddBlurEffect()
second_title: Aspose.Slides for C++ API 參考文件
description: 將新的模糊效果新增至集合的末端。
type: docs
weight: 131
url: /zh-hant/aspose.slides.effects/iimagetransformoperationcollection/addblureffect/
---
## IImageTransformOperationCollection::AddBlurEffect(double, bool) 方法

將新的 [Blur](../../blur/) 效果新增至集合的末端。

```cpp
virtual System::SharedPtr<IBlur> Aspose::Slides::Effects::IImageTransformOperationCollection::AddBlurEffect(double radius, bool grow)=0
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| radius | **double** | 模糊的半徑。 |
| grow | **bool** | 指定在模糊處理後物件的邊界是否應該擴大。True 表示邊界會被擴大，false 表示不會。 |

### 傳回值

集合中新增影像效果的索引。

## 另請參閱

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IBlur](../../iblur/)
* 類別 [IImageTransformOperationCollection](../)
* 命名空間 [Aspose::Slides::Effects](../../)
* Library [Aspose.Slides](../../../)