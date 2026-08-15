---
title: GetHashCode()
second_title: Aspose.Slides for C++ API 參考文件
description: "取得任意類型的雜湊碼。呼叫 Object::GetHashCode() 以執行此操作。"
type: docs
weight: 1
url: /zh-hant/system.runtime.compilerservices/runtimehelpers/gethashcode/
---
## RuntimeHelpers::GetHashCode(SmartPtr\<T\> const\&) 方法

取得任意類型的雜湊碼。呼叫 [Object::GetHashCode()](../../../system/object/gethashcode/) 以執行此操作。

```cpp
template<typename T> static int System::Runtime::CompilerServices::RuntimeHelpers::GetHashCode(SmartPtr<T> const &obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 要取得雜湊碼的型別。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | [SmartPtr](../../../system/smartptr/)\<T\> const\& | [Object](../../../system/object/) 以取得資訊。 |

### 回傳值

雜湊碼值，由目標實作計算。

## 另請參閱

* 類別 [SmartPtr](../../../system/smartptr/)
* 類別 [RuntimeHelpers](../)
* 命名空間 [System::Runtime::CompilerServices](../../)
* 函式庫 [Aspose.Slides](../../../)