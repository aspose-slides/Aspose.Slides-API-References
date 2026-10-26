---
title: IndexOf()
second_title: Aspose.Slides for C++ API 參考文件
description: 傳回集合中指定形狀首次出現的零基索引。
type: docs
weight: 313
url: /zh-hant/aspose.slides/shapecollection/indexof/
---
## ShapeCollection::IndexOf(System::SharedPtr\<IShape\>) 方法

返回指定形狀在集合中首次出現的零基索引。

```cpp
int32_t Aspose::Slides::ShapeCollection::IndexOf(System::SharedPtr<IShape> shape) override
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| shape | [System::SharedPtr](../../../system/sharedptr/)\<[IShape](../../ishape/)\> | 要在集合中定位的形狀。 |

### 回傳值

如果找到形狀，回傳其在形狀集合中第一次出現的零基索引；如果未找到，則回傳 \\u20131。

## 另請參考

* Typedef [SharedPtr](../../../system/sharedptr/)
* 類別 [IShape](../../ishape/)
* 類別 [ShapeCollection](../)
* 命名空間 [Aspose::Slides](../../)
* 函式庫 [Aspose.Slides](../../../)