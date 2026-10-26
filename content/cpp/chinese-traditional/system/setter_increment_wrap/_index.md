---
title: setter_increment_wrap()
second_title: Aspose.Slides for C++ API 參考
description: 翻譯器將針對已定義 setter 與 getter 的類別屬性的 C# 增量運算式轉換為呼叫此函式。
type: docs
weight: 2835
url: /zh-hant/system/setter_increment_wrap/
---
## System::setter_increment_wrap(T(*)(), void(*)(T)) 函式

翻譯器會將針對已定義 setter 與 getter 的類別屬性的 C# 遞增運算式，轉換為呼叫此函式。

```cpp
template<typename T> T System::setter_increment_wrap(T(*pGetter)(), void(*pSetter)(T))
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 屬性的類型 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| pGetter | T(*)() | 指向屬性 getter 自由函式的函式指標 |
| pSetter | void(*)(T) | 指向屬性 setter 自由函式的函式指標 |

### 返回值

屬性遞增後的值

## System::setter_increment_wrap(Host *const, T(HostGet::*)(), void(HostSet::*)(T)) 函式

翻譯器會將針對已定義 setter 與 getter 的類別屬性的 C# 遞增運算式，轉換為呼叫此函式。

```cpp
template<typename T,typename Host,typename HostGet,typename HostSet> std::enable_if<std::is_base_of<HostGet, Host>::value &&std::is_base_of<HostSet, Host>::value, T>::type System::setter_increment_wrap(Host *const host, T(HostGet::*pGetter)(), void(HostSet::*pSetter)(T))
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| T | 屬性的類型 |
| Host | - 要修改之實例的類別 |
| HostGet | - Host 本身，或其基底類型，屬性的 getter 定義於此 |
| HostSet | - Host 本身，或其基底類型，屬性的 setter 定義於此 |

### 參數

| 參數 | 型別 | 描述 |
| --- | --- | --- |
| host | Host *const | 指向其屬性將被遞增之物件的指標 |
| pGetter | T(HostGet::*)() | 指向屬性 getter 方法的函式指標 |
| pSetter | void(HostSet::*)(T) | 指向屬性 setter 方法的函式指標 |

### 返回值

屬性遞增後的值

## 另見

* 命名空間 [System](../)
* 函式庫 [Aspose.Slides](../../)