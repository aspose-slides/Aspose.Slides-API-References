---
title: SmartPtrInfo
second_title: Aspose.Slides for C++ API 參考文件
description: 服務類別，用於測試和更改 SmartPtr 的內容而無需知道最終類型。用於垃圾回收與循環參照檢測等。可將其視為「指向指標」的指標。我們無法使用 SmartPtr 的基底類型，因為它沒有；因此，我們使用此「info」類別。
type: docs
weight: 1249
url: /zh-hant/system/smartptrinfo/
---
## SmartPtrInfo class

服務類別，用於測試和更改 [SmartPtr](../smartptr/) 的內容而無需知道最終類型。用於垃圾回收與循環參照檢測等。可將其視為「指向指標」的指標。我們無法使用 [SmartPtr](../smartptr/) 的基底類型，因為它沒有；因此，我們使用此「info」類別。

```cpp
class SmartPtrInfo
```

## Methods

| Method | Description |
| --- | --- |
| const void * [getInternalPtr](./getinternalptr/)() const | 取得被參考指標指向的原始物件。 |
| [Object](../object/) * [getObject](./getobject/)() const | 取得被參考指標指向的物件。 |
| [Object](../object/) * [getOwned](./getowned/)() const | 取得擁有物件的指標。 |
|  [operator bool](./operator_bool/)() const | 檢查 info 物件是否指向非空指標。 |
| **bool** [operator!](./operator_not/)() const | 檢查 info 物件是否不指向非空指標。 |
| [Object](../object/) * [operator->](./operator_minus_greater/)() const | 允許呼叫參考指標所指向的 [Object](../object/) 方法。 |
| **bool** [operator<](./operator_less/)(const [SmartPtrInfo](./)\&) const | 比較兩個 info 物件所參考的指標值的大小。 |
|  [SmartPtrInfo](./smartptrinfo/)() | 建立空的 [SmartPtrInfo](./) 物件。 |
| explicit  [SmartPtrInfo](./smartptrinfo/)(const [SmartPtr](../smartptr/)\<T\>\&) | 建立包含特定智慧指標資訊的 [SmartPtrInfo](./) 物件。 |

## See Also

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)