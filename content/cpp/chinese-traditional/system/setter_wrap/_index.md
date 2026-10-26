---
title: setter_wrap()
second_title: Aspose.Slides for C++ API 參考
description: 使用類型轉換的靜態設定函式的重載。
type: docs
weight: 2822
url: /zh-hant/system/setter_wrap/
---
## System::setter_wrap(void(*)(T2), T) 函式

用於類型轉換的靜態設定函式的重載。

```cpp
template<typename T,typename T2> T System::setter_wrap(void(*pSetter)(T2), T value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 值類型。 |
| T2 | 設定函式所期望的類型。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pSetter | void(*)(T2) | 靜態設定函式參考。 |
| value | T | 要設定的值。 |

### 返回值

設定的值。

## System::setter_wrap(Host *const, void(HostSet::*)(T2), T) 函式

用於類型轉換的實例設定函式的重載。

```cpp
template<typename T,typename T2,typename Host,typename HostSet> std::enable_if<std::is_base_of<HostSet, Host>::value, T>::type System::setter_wrap(Host *const host, void(HostSet::*pSetter)(T2), T value)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 值類型。 |
| T2 | 設定函式所期望的類型。 |
| Host | 實例類型。 |
| HostSet | - Host 本身，或其基類，屬性設定函式定義於此。 |

### 引數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| host | Host *const | [Object](../object/) 用於呼叫設定函式。 |
| pSetter | void(HostSet::*)(T2) | 設定函式參考。 |
| value | T | 要設定的值。 |

### 返回值

設定的值。

## 另請參閱

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)