---
title: TypeInfo()
second_title: Aspose.Slides for C++ API 參考文件
description: 預設建構函式（未設定類型）。
type: docs
weight: 40
url: /zh-hant/system/typeinfo/typeinfo/
---
## TypeInfo::TypeInfo() 建構函式


預設建構函式（未設定類型）。

```cpp
System::TypeInfo::TypeInfo()
```

## TypeInfo::TypeInfo(std::nullptr_t) 建構函式


空值物件建構函式（未設定類型）。

```cpp
System::TypeInfo::TypeInfo(std::nullptr_t)
```

## TypeInfo::TypeInfo(const char_t *) 建構函式


建構函式。

```cpp
System::TypeInfo::TypeInfo(const char_t *name)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | const char_t * | 類型名稱。 |

## TypeInfo::TypeInfo(const char_t *, uint32_t) 建構函式


建構函式。

```cpp
System::TypeInfo::TypeInfo(const char_t *name, uint32_t hash)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| name | const char_t * | 類型名稱。 |
| hash | **uint32_t** | 類型名稱雜湊。 |

## TypeInfo::TypeInfo(const std::type_info\&) 建構函式


建構函式。

```cpp
System::TypeInfo::TypeInfo(const std::type_info &info)
```


### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| info | const std::type_info\& | 關於類型的資訊。 |

## 參見

* 類別 [TypeInfo](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)