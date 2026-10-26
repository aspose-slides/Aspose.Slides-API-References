---
title: SafeInvoke()
second_title: Aspose.Slides لمرجع API C++
description: تنفيذ ترجمة العامل '?.'.
type: docs
weight: 2653
url: /ar/system/safeinvoke/
---
## System::SafeInvoke(T0\&&, T1\&&) function

تنفيذ ترجمة العامل '?.'.

```cpp
template<typename T0,typename T1> static auto System::SafeInvoke(T0 &&expr, T1 &&func)
```

### معلمات القالب

| Parameter | Description |
| --- | --- |
| T0 | نوع التعبير. |
| T1 | نوع لامدا التي تغلف تعبير 'WhenTrue'. |

### وسائط

| Parameter | Type | Description |
| --- | --- | --- |
| expr | T0\&& | قيمة التعبير. |
| func | T1\&& | تعبير 'WhenTrue' المرتبط بـ functor. |

### قيمة الإرجاع

إذا كانت قيمة expr ليست null، تُرجع func المستدعاه بقيمتها كوسيط أول، وإلا تُرجع null.

## انظر أيضًا

* Namespace [System](../)
* Library [Aspose.Slides](../../)