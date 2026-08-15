---
title: setter_post_increment_wrap()
second_title: Aspose.Slides for C++ API 參考手冊
description: 翻譯器將 C# 的後置遞增運算式（針對具有 setter 和 getter 定義的類別屬性）轉換為呼叫此函式。
type: docs
weight: 2848
url: /zh-hant/system/setter_post_increment_wrap/
---
## System::setter_post_increment_wrap(T(*)(), void(*)(T)) 函式


翻譯器將 C# 的後置遞增運算式（針對具有 setter 和 getter 定義的 class 屬性）轉換為呼叫此函式。

```cpp
template<typename T> T System::setter_post_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 屬性的型別 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| pGetter | T(*)() | 指向屬性 getter 自由函式的函式指標 |
| pSetter | void(*)(T) | 指向屬性 setter 自由函式的函式指標 |

### 返回值

屬性遞增前的值

## System::setter_post_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) 函式


翻譯器將 C# 的後置遞增運算式（針對具有 setter 和 getter 定義的 instance 屬性）轉換為呼叫此函式（非 const getter 的重載）。

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 屬性的型別。 |
| Host | - 要修改的實例的類別 |
| HostGet | - Host 本身，或其基礎類型，定義了屬性的 getter |
| HostSet | - Host 本身，或其基礎類型，定義了屬性的 setter |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| host | Host *const | 用於呼叫 getter 與 setter 的實例。 |
| pGetter | T(HostGet::*)() | 指向屬性 getter 函式的函式指標 |
| pSetter | void(HostSet::*)(T) | 指向屬性 setter 函式的函式指標 |

### 返回值

屬性遞增前的值

## System::setter_post_increment_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) 函式


翻譯器將 C# 的後置遞增運算式（針對具有 setter 和 getter 定義的 instance 屬性）轉換為呼叫此函式（const getter 的重載）。

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_post_increment_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 屬性的型別。 |
| Host | - 要修改的實例的類別 |
| HostConstGet | - Host 本身，或其基礎類型，定義了屬性的 getter |
| HostSet | - Host 本身，或其基礎類型，定義了屬性的 setter |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| host | Host *const | 用於呼叫 getter 與 setter 的實例。 |
| pGetter | T(HostConstGet::*)() const | 指向屬性 getter 函式的函式指標 |
| pSetter | void(HostSet::*)(T) | 指向屬性 setter 函式的函式指標 |

### 返回值

屬性遞增前的值

## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)