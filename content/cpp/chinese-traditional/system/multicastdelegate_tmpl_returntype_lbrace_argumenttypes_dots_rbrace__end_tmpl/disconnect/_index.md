---
title: disconnect()
second_title: Aspose.Slides for C++ API 參考
description: 從委派集合中移除指定的 delegate。
type: docs
weight: 170
url: /zh-hant/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) method

從委派集合中移除指定的 delegate。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| callback | [Callback](../callback/) | 要從集合中移除的 delegate |

### Return Value

對自身的參照

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) method

從委派集合中移除指定物件的指定非靜態方法。

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| MemberType | 要從委派集合中移除的非靜態方法的類型 |
| ClassType | 要從委派集合中移除之物件方法的類型 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | 指向指定物件之非靜態方法的指標 |
| obj | ClassType * | 指向要從委派集合中移除之物件成員方法的指標 |

### Return Value

對自身的參照

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) method

從委派集合中移除指定物件的指定非靜態方法。

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| MemberType | 要從委派集合中移除的非靜態方法的類型 |
| ClassType | 要從委派集合中移除之物件方法的類型 |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| member | MemberType ClassType::* | 指向指定物件之非靜態方法的指標 |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | 指向要從委派集合中移除之物件成員方法的共享指標 |

### Return Value

對自身的參照

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) method

從委派集合中移除指定的 MulticastDelegate 物件。

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | 要從委派集合中移除的 MulticastDelegate 類別之實例 |

### Return Value

對自身的參照

## See Also

* 型別定義 [Callback](../callback/)
* 型別定義 [SharedPtr](../../sharedptr/)
* 方法 [MulticastDelegate](../multicastdelegate/)
* 類別 [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* 命名空間 [System](../../)
* 程式庫 [Aspose.Slides](../../../)