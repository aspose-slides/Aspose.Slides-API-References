---
title: IsInstanceOfType()
second_title: Aspose.Slides for C++ API 參考
description: 判斷指定的物件是否為目前類型的實例。
type: docs
weight: 131
url: /zh-hant/system/typeinfo/isinstanceoftype/
---
## TypeInfo::IsInstanceOfType(const SharedPtr\<Object\>\&) const 方法

判斷指定的物件是否為目前類型的實例。

```cpp
bool System::TypeInfo::IsInstanceOfType(const SharedPtr<Object> &obj) const
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | const [SharedPtr](../../sharedptr/)\<[Object](../../object/)\>\& | 要與目前類型比較的物件 |

### 返回值

true 若目前類型位於 obj 所代表之物件的繼承層級中，則為 true

## 參見

* Typedef [SharedPtr](../../sharedptr/)
* 類別 [Object](../../object/)
* 類別 [TypeInfo](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)