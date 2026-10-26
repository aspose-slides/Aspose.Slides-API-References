---
title: connect()
second_title: Aspose.Slides for C++ API 參考
description: 將指定的委託新增至集合中。
type: docs
weight: 144
url: /zh-hant/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/connect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(Callback) 方法

將指定的委託新增至集合中。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(Callback callback)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| callback | [Callback](../callback/) | 要新增至集合的委託 |

### 返回值

返回對自身的參考

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(std::function\<R(Args...)>) 方法

將指定的函式物件新增至委託集合中。函式物件在新增至集合之前會轉換為 Callback 委託類型。

```cpp
template<class R,class...> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(std::function<R(Args...)> f)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| R | 要新增至集合的函式物件的返回類型 |
| Args | 要新增至集合的函式物件的參數列表 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| f | std::function\<R(Args...)> | 要新增至集合的函式物件 |

### 返回值

返回對自身的參考

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MulticastDelegate\&) 方法

將指定的 MulticastDelegate 物件新增至委託集合中。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MulticastDelegate &other)
```

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | 要新增至委託集合的 MulticastDelegate 類別實例 |

### 返回值

返回對自身的參考

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, ClassType *) 方法

將指定物件的指定非靜態方法新增至委託集合中。

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, ClassType *obj)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| MemberType | 要新增至委託集合的非靜態方法的類型 |
| ClassType | 要新增至委託集合的物件類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| member | MemberType ClassType::* | 指定物件的非靜態方法指標 |
| obj | ClassType * | 要新增至委託集合的物件指標 |

### 返回值

返回對自身的參考

## MulticastDelegate< ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) 方法

將指定物件的指定非靜態方法新增至委託集合中。

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::connect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### 模板參數

| 參數 | 描述 |
| --- | --- |
| MemberType | 要新增至委託集合的非靜態方法的類型 |
| ClassType | 要新增至委託集合的物件類型 |

### 參數

| 參數 | 類型 | 描述 |
| --- | --- | --- |
| member | MemberType ClassType::* | 指定物件的非靜態方法指標 |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | 指向要新增至委託集合之物件的共享指標 |

### 返回值

返回對自身的參考

## 另請參閱

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* 方法 [MulticastDelegate](../multicastdelegate/)
* 類別 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 命名空間 [System](../../)
* 函式庫 [Aspose.Slides](../../../)