---
title: setter_decrement_wrap()
second_title: Aspose.Slides for C++ API 參考
description: 翻譯器將 C# 的前置遞減表達式（目標是具有已定義 setter 和 getter 的類別屬性）轉換為對此函式的呼叫。
type: docs
weight: 2861
url: /zh-hant/system/setter_decrement_wrap/
---
## System::setter_decrement_wrap(T(*)(), void(*)(T)) 函式


翻譯器將 C# 的前置遞減表達式（目標是具有已定義 setter 和 getter 的類別屬性）轉換為對此函式的呼叫。

```cpp
template<typename T> T System::setter_decrement_wrap(T(*pGetter)(), void(*pSetter)(T))
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 屬性的型別 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| pGetter | T(*)() | 指向屬性 getter 自由函式的函式指標 |
| pSetter | void(*)(T) | 指向屬性 setter 自由函式的函式指標 |

### 返回值

屬性遞增前的值

## System::setter_decrement_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) 函式


翻譯器將 C# 的前置遞減表達式（目標是具有已定義 setter 和 getter 的實例屬性）轉換為對此函式的呼叫（非 const getter 的重載）。

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 屬性的型別。 |
| Host | - 要修改之實例的類別 |
| HostGet | - 定義屬性 getter 的 Host 本身或其基底類型 |
| HostSet | - 定義屬性 setter 的 Host 本身或其基底類型 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| host | Host *const | 要呼叫 getter 與 setter 的實例。 |
| pGetter | T(HostGet::*)() | 指向屬性 getter 函式的函式指標 |
| pSetter | void(HostSet::*)(T) | 指向屬性 setter 函式的函式指標 |

### 返回值

屬性遞增前的值

## System::setter_decrement_wrap(Host *const, T(HostConstGet::*)() const, void(HostSet::*)(T)) 函式


翻譯器將 C# 的前置遞減表達式（目標是具有已定義 setter 和 getter 的實例屬性）轉換為對此函式的呼叫（const getter 的重載）。

```cpp
template<typename T,typename Host,typename HostConstGet,typename HostSet> std::enable_if<std::is_base_of<HostConstGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_decrement_wrap(Host *const host, T(HostConstGet::*pGetter)() const, void(HostSet::*pSetter)(T))
```


### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 屬性的型別。 |
| Host | - 要修改之實例的類別 |
| HostConstGet | - 定義屬性 getter 的 Host 本身或其基底類型 |
| HostSet | - 定義屬性 setter 的 Host 本身或其基底類型 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| host | Host *const | 要呼叫 getter 與 setter 的實例。 |
| pGetter | T(HostConstGet::*)() const | 指向屬性 getter 函式的函式指標 |
| pSetter | void(HostSet::*)(T) | 指向屬性 setter 函式的函式指標 |

### 返回值

屬性遞增前的值

## 另請參閱

* Namespace [System](../)
* Library [Aspose.Slides](../../)