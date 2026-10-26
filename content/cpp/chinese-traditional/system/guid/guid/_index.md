---
title: Guid()
second_title: Aspose.Slides for C++ API 參考
description: 建構一個表示全部為零的 GUID 物件。
type: docs
weight: 1
url: /zh-hant/system/guid/guid/
---
## Guid::Guid() 建構函式


建構一個表示全部為零的 GUID 物件。

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) 建構函式


建構一個以 unsigned 8 位元整數陣列形式指定的 GUID 物件。

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 包含 GUID 各位元組的位元組陣列 |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) 建構函式


建構一個以 unsigned 8 位元整數陣列檢視形式指定的 GUID 物件。

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | 包含 GUID 各位元組的位元組陣列 |

## Guid::Guid(const String\&) 建構函式


建構一個以字串形式指定的 GUID 物件。

```cpp
System::Guid::Guid(const String &g)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| g | const [String](../../string/)\& | 要由建構之物件表示的 GUID 字串表示法 |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) 建構函式


根據指定的 GUID 元件建構 [Guid](../) 類別的實例。

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | **int32_t** | GUID 的第 0-31 位元 |
| b | **int16_t** | GUID 的第 32-47 位元 |
| c | **int16_t** | GUID 的第 48-63 位元 |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | 包含 GUID 第 64-127 位元的位元組陣列 |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) 建構函式


根據指定的 GUID 元件建構 [Guid](../) 類別的實例。

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | **int32_t** | GUID 的第 0-31 位元 |
| b | **int16_t** | GUID 的第 32-47 位元 |
| c | **int16_t** | GUID 的第 48-63 位元 |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | 包含 GUID 第 64-127 位元的位元組陣列檢視 |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) 建構函式


根據指定的 unsigned 整數與位元組建構 [Guid](../) 類別的實例。

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | **int32_t** | GUID 的第 0-31 位元 |
| b | **int16_t** | GUID 的第 32-47 位元 |
| c | **int16_t** | GUID 的第 48-63 位元 |
| d | **uint8_t** | GUID 的第 64-71 位元 |
| e | **uint8_t** | GUID 的第 72-79 位元 |
| f | **uint8_t** | GUID 的第 80-87 位元 |
| g | **uint8_t** | GUID 的第 88-95 位元 |
| h | **uint8_t** | GUID 的第 96-103 位元 |
| i | **uint8_t** | GUID 的第 104-111 位元 |
| j | **uint8_t** | GUID 的第 112-119 位元 |
| k | **uint8_t** | GUID 的第 120-127 位元 |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) 建構函式


根據指定的 unsigned 整數與位元組建構 [Guid](../) 類別的實例。

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| a | **uint32_t** | GUID 的第 0-31 位元 |
| b | **uint16_t** | GUID 的第 32-47 位元 |
| c | **uint16_t** | GUID 的第 48-63 位元 |
| d | **uint8_t** | GUID 的第 64-71 位元 |
| e | **uint8_t** | GUID 的第 72-79 位元 |
| f | **uint8_t** | GUID 的第 80-87 位元 |
| g | **uint8_t** | GUID 的第 88-95 位元 |
| h | **uint8_t** | GUID 的第 96-103 位元 |
| i | **uint8_t** | GUID 的第 104-111 位元 |
| j | **uint8_t** | GUID 的第 112-119 位元 |
| k | **uint8_t** | GUID 的第 120-127 位元 |

## Guid::Guid(const Guid\&) 建構函式


建構一個與指定物件表示相同 GUID 的物件。

```cpp
System::Guid::Guid(const Guid &guid)
```


### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| guid | const [Guid](../)\& | 用來複製 GUID 值的 [Guid](../) 物件 |

## 相關參考

* Typedef [ArrayPtr](../../arrayptr/)
* 類別 [Guid](../)
* 類別 [String](../../string/)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)