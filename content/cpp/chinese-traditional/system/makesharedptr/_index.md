---
title: MakeSharedPtr()
second_title: Aspose.Slides for C++ API 參考
description: 將原始指標轉換為智慧指標。
type: docs
weight: 2900
url: /zh-hant/system/makesharedptr/
---
## System::MakeSharedPtr(X *) 函式

將原始指標轉換為智慧指標。

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(X *p)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| X | 指向的類型。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| p | X * | 指向物件的原始指標。 |

### 返回值

指向物件的共享智慧指標。

## System::MakeSharedPtr(const X *) 函式

將原始指標轉換為智慧指標。此為 const 指標的重載。當在 C# 方法中使用被翻譯為 const 的 'this' 變數時很有用。

```cpp
template<class X> SmartPtr<X> System::MakeSharedPtr(const X *p)
```

### 範本參數

| 參數 | 說明 |
| --- | --- |
| X | 指向的類型。 |

### 參數

| 參數 | 型別 | 說明 |
| --- | --- | --- |
| p | const X * | 指向物件的原始指標。 |

### 返回值

指向物件的共享智慧指標。

## 另請參閱

* 類別 [SmartPtr](../smartptr/)
* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)