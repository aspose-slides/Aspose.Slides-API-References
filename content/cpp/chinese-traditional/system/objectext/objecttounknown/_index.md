---
title: ObjectToUnknown()
second_title: Aspose.Slides for C++ API 參考文件
description: 將 Object 轉換為未知類型，同時處理智能指標類型和已裝箱的值情況。
type: docs
weight: 131
url: /zh-hant/system/objectext/objecttounknown/
---
## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) 方法

將 [Object](../../object/) 轉換為未知類型，同時處理智能指標類型和已裝箱的值情況。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 要將 [Object](../../object/) 轉換為的類型。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) 要轉換。 |

### 返回值

未裝箱的值或已轉換的指標。

## ObjectExt::ObjectToUnknown(SmartPtr\<Object\>) 方法

將 [Object](../../object/) 轉換為未知類型，同時處理智能指標類型和已裝箱的值情況。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, T>::type System::ObjectExt::ObjectToUnknown(SmartPtr<Object> obj)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 要將 [Object](../../object/) 轉換為的類型。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| obj | [SmartPtr](../../smartptr/)\<[Object](../../object/)\> | [Object](../../object/) 要轉換。 |

### 返回值

未裝箱的值或已轉換的指標。

## 相關參考

* 類別 [SmartPtr](../../smartptr/)
* 類別 [Object](../../object/)
* 類別 [ObjectExt](../)
* 結構 [IsSmartPtr](../../issmartptr/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)