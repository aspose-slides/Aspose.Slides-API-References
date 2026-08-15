---
title: MulticastDelegate()
second_title: Aspose.Slides for C++ API 參考
description: 建構一個空的集合。
type: docs
weight: 1
url: /zh-hant/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() 方法

建構一個空的集合。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) 方法

等同於預設建構函式。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) 方法

執行委派集合的淺層複製。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| o | const MulticastDelegate\& | MulticastDelegate class 的實例，用於複製委派集合。 |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) 方法

移動建構函式。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| o | MulticastDelegate\&& | MulticastDelegate class 的實例，用於移動委派集合。 |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) 方法

建構一個實例並將指定的委派加入委派集合。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | 要加入委派集合的委派 |

## MulticastDelegate< ReturnType(ArgumentTypes…)>::MulticastDelegate(T) 方法

建構一個實例並將指定的值加入委派集合。

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### 模板參數

| 參數 | 說明 |
| --- | --- |
| T | 新建實例的委派集合中要加入之值的類型；該類型必須可轉換為 Callback 類型。 |

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arg | T | 要加入委派集合的值 |

## MulticastDelegate< ReturnType(ArgumentTypes…)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes…)>) 方法

建構一個實例並將指定的值加入委派集合。

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### 參數

| 參數 | 類型 | 說明 |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes…)> | 要加入委派集合的值 |

## 參見

* 型別別名 [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)