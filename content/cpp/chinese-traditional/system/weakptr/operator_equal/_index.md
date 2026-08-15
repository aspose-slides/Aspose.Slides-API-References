---
title: operator=()
second_title: Aspose.Slides for C++ API 參考
description: 將值指派給弱指標。呼叫 SmartPtr_ 的特定指派運算子。
type: docs
weight: 14
url: /zh-hant/system/weakptr/operator_equal/
---
## WeakPtr::operator=(Q\&&) 方法

將值指派給弱指標。呼叫 SmartPtr_ 的特定指派運算子。

```cpp
template<typename Q> WeakPtr & System::WeakPtr<T>::operator=(Q &&value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| Q | 由 [System::SmartPtr](../../smartptr/) 指派運算子支援的參數類型。 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| value | Q\&& | 要從其複製被指向值的指標。 |

## 參見

* 類別 [WeakPtr](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)