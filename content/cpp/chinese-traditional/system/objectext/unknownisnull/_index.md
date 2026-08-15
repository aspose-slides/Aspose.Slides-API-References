---
title: UnknownIsNull()
second_title: Aspose.Slides for C++ API 參考文件
description: 檢查未知類型物件是否為 nullptr。非標量類型的重載。
type: docs
weight: 144
url: /zh-hant/system/objectext/unknownisnull/
---
## ObjectExt::UnknownIsNull(T) 方法


檢查未知類型物件是否為 nullptr。非標量類型的重載。

```cpp
template<typename T> static std::enable_if<!std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../object/) 類型。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | T | [Object](../../object/) 用於檢查。 |

### 返回值

若 'obj == nullptr' 為真，則返回 True；否則返回 false。

## ObjectExt::UnknownIsNull(T) 方法


檢查未知類型物件是否為 nullptr。標量類型的重載。

```cpp
template<typename T> static std::enable_if<std::is_scalar<T>::value, bool>::type System::ObjectExt::UnknownIsNull(T obj)
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | [Object](../../object/) 類型。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| obj | T | [Object](../../object/) 用於檢查。 |

### 返回值

始終返回 false。

## 參見

* 類別 [ObjectExt](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)