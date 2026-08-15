---
title: what()
second_title: Aspose.Slides for C++ API 參考文件
description: "實作 what() 方法，該方法由 ExceptionWrapper 類別呼叫。雖然此類別未繼承自 std::exception，但衍生類別仍可使用受保護/私有成員來實作其邏輯。將此方法的實作移至 ExceptionWrapper 可能會破壞該邏輯。"
type: docs
weight: 105
url: /zh-hant/system/details_exception/what/
---
## Details_Exception::what() const 方法

Implements [what()](./) 方法 which is called by [ExceptionWrapper](../../exceptionwrapper/) 類別. Despite of the fact that this 類別 is not inherited from std::exception derived classes can use protected/private 成員 to implement their logic. Moving this 方法 implementation to the [ExceptionWrapper](../../exceptionwrapper/) may broke that logic.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```

### 返回值

例外的描述。

## 參見

* 類別 [Details_Exception](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)