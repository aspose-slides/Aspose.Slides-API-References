---
title: MulticastDelegate()
second_title: مرجع API Aspose.Slides للغة C++
description: ينشئ مجموعة فارغة.
type: docs
weight: 1
url: /ar/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/multicastdelegate/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate() method

ينشئ مجموعة فارغة.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate()
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t) method

ما يعادل المنشئ الافتراضي.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::nullptr_t)
```

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate\&) method

يقوم بعمل نسخة سطحية من مجموعة المفوضين.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(const MulticastDelegate &o)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| o | const MulticastDelegate\& | نسخة من فئة MulticastDelegate لنسخ مجموعة المفوضين منها. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate\&&) method

منشئ النقل.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(MulticastDelegate &&o) noexcept
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| o | MulticastDelegate\&& | نسخة من فئة MulticastDelegate لنقل مجموعة المفوضين منها. |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback\&&) method

ينشئ مثيلاً ويضيف المفوض المحدد إلى مجموعة المفوضين.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(Callback &&initial)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| initial | [Callback](../callback/)\&& | مفوض للإضافة إلى مجموعة المفوضين |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(T) method

ينشئ مثيلاً ويضيف القيمة المحددة إلى مجموعة المفوضين.

```cpp
template<class T,typename> System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(T arg)
```

### Template parameters

| Parameter | Description |
| --- | --- |
| T | نوع القيمة التي تُضاف إلى مجموعة المفوضين في المثيل الذي تم إنشاؤه حديثًا؛ يجب أن يكون النوع قابلًا للتحويل إلى نوع Callback. |

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arg | T | قيمة تُضاف إلى مجموعة المفوضين |

## MulticastDelegate< ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function\<ReturnType(ArgumentTypes...)>) method

ينشئ مثيلاً ويضيف القيمة المحددة إلى مجموعة المفوضين.

```cpp
System::MulticastDelegate<ReturnType(ArgumentTypes...)>::MulticastDelegate(std::function<ReturnType(ArgumentTypes...)> arg)
```

### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| arg | std::function\<ReturnType(ArgumentTypes...)> | قيمة تُضيف إلى مجموعة المفوضين |

## See Also

* Typedef [Callback](../callback/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)