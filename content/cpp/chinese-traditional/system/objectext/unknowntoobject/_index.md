---
title: UnknownToObject()
second_title: Aspose.Slides for C++ API 參考文件
description: 將未知類型轉換為 Object，並處理智慧指標類型與值類型的情況。
type: docs
weight: 118
url: /zh-hant/system/objectext/unknowntoobject/
---
## ObjectExt::UnknownToObject(T) 方法

將未知類型轉換為 [Object](../../object/)，同時處理智慧指標類型和值類型的情況。

```cpp
template<typename T> static std::enable_if<IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(T obj)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 要轉換為 [Object](../../object/) 的類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | T | [Object](../../object/) 轉換。 |

### 傳回值

智慧指標指向 [Object](../../object/)，可能是已轉換的指標或封裝的值。

## ObjectExt::UnknownToObject(const T\&) 方法

將未知類型轉換為 [Object](../../object/)，同時處理智慧指標類型和值類型的情況。

```cpp
template<typename T> static std::enable_if<!IsSmartPtr<T>::value, System::SmartPtr<Object>>::type System::ObjectExt::UnknownToObject(const T &obj)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 要轉換為 [Object](../../object/) 的類型。 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| obj | const T\& | [Object](../../object/) 轉換。 |

### 傳回值

智慧指標指向 [Object](../../object/)，可能是已轉換的指標或封裝的值。

## 另見

* 類別 [SmartPtr](../../smartptr/)
* 類別 [Object](../../object/)
* 類別 [ObjectExt](../)
* 結構 [IsSmartPtr](../../issmartptr/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)