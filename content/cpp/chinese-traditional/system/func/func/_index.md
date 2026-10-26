---
title: Func()
second_title: Aspose.Slides for C++ API 參考文件
description: 預設建構函式，用於建立 null-Func。
type: docs
weight: 1
url: /zh-hant/system/func/func/
---
## Func::Func() 建構函式

預設建構函式，建立 null-Func。

```cpp
System::Func<Args>::Func()
```

## Func::Func(T\&&) 建構函式

建構子會建立 [Func](../) 物件並將值（實際回呼或 nullptr）指派給它。

```cpp
template<typename T> System::Func<Args>::Func(T &&arg)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| T | 參數類型。 |

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| arg | T\&& | 參數。 |

## Func::Func(const Func\&) 建構函式

複製建構函式。

```cpp
System::Func<Args>::Func(const Func &func)
```

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| func | const [Func](../)\& | [Object](../../object/) 以複製資料。 |

## Func::Func(Func\&&) 建構函式

移動建構函式。

```cpp
System::Func<Args>::Func(Func &&func) noexcept
```

### 引數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| func | [Func](../)\&& | [Object](../../object/) 以移動資料。 |

## 參見

* 類別 [Func](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)