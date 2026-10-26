---
title: disconnect()
second_title: Aspose.Slides برای C++ مرجع API
description: نمایندهٔ مشخص‌شده را از مجموعهٔ نمایندگان حذف می‌کند.
type: docs
weight: 170
url: /fa/system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/disconnect/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(Callback) متد

نمایندهٔ مشخص‌شده را از مجموعهٔ نمایندگان حذف می‌کند.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(Callback callback)
```

### پارامترها
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| callback | [Callback](../callback/) | نماینده‌ای که باید از مجموعه حذف شود |

### مقدار بازگشت
مرجعی به خود

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, ClassType *) متد

متد غیر ایستاتیک مشخص‌شدهٔ شیء مشخص‌شده را از مجموعهٔ نمایندگان حذف می‌کند.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, ClassType *obj)
```

### پارامترهای قالب
| پارامتر | توضیح |
| --- | --- |
| MemberType | نوع متد غیر ایستاتیک که باید از مجموعهٔ نمایندگان حذف شود |
| ClassType | نوع شیء‌ای که متد آن باید از مجموعهٔ نمایندگان حذف شود |

### پارامترها
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| member | MemberType ClassType::* | یک اشاره‌گر به متد غیر ایستاتیک شیء مشخص‌شده |
| obj | ClassType * | یک اشاره‌گر به متد عضو شیء‌ای که باید از مجموعهٔ نمایندگان حذف شود |

### مقدار بازگشت
مرجعی به خود

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*, const SharedPtr\<ClassType\>\&) متد

متد غیر ایستاتیک مشخص‌شدهٔ شیء مشخص‌شده را از مجموعهٔ نمایندگان حذف می‌کند.

```cpp
template<class MemberType,class ClassType> MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MemberType ClassType::*member, const SharedPtr<ClassType> &obj)
```

### پارامترهای قالب
| پارامتر | توضیح |
| --- | --- |
| MemberType | نوع متد غیر ایستاتیک که باید از مجموعهٔ نمایندگان حذف شود |
| ClassType | نوع شیء‌ای که متد آن باید از مجموعهٔ نمایندگان حذف شود |

### پارامترها
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| member | MemberType ClassType::* | یک اشاره‌گر به متد غیر ایستاتیک شیء مشخص‌شده |
| obj | const [SharedPtr](../../sharedptr/)\<ClassType\>\& | یک shared pointer به متد عضو شیء‌ای که باید از مجموعهٔ نمایندگان حذف شود |

### مقدار بازگشت
مرجعی به خود

## MulticastDelegate< ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate\&) متد

شیء MulticastDelegate مشخص‌شده را از مجموعهٔ نمایندگان حذف می‌کند.

```cpp
MulticastDelegate & System::MulticastDelegate<ReturnType(ArgumentTypes...)>::disconnect(MulticastDelegate &other)
```

### پارامترها
| پارامتر | نوع | توضیح |
| --- | --- | --- |
| other | [MulticastDelegate](../multicastdelegate/)\& | نمونه‌ای از کلاس MulticastDelegate برای حذف از مجموعهٔ نمایندگان |

### مقدار بازگشت
مرجعی به خود

## موارد مرتبط

* Typedef [Callback](../callback/)
* Typedef [SharedPtr](../../sharedptr/)
* Method [MulticastDelegate](../multicastdelegate/)
* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)