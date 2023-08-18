---
title: operator()()
second_title: Aspose.Slides for C++ API Reference
description: Invokes all delegates currently present in the delegates collection. Delegates are invoked in the same order as they were added to the collection. The operator blocks while the delegates are executed.
type: docs
weight: 222
url: /system/multicastdelegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_call/
---
## MulticastDelegate< ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes...) const method


Invokes all delegates currently present in the delegates collection. Delegates are invoked in the same order as they were added to the collection. The operator blocks while the delegates are executed.

```cpp
ReturnType System::MulticastDelegate<ReturnType(ArgumentTypes...)>::operator()(ArgumentTypes... args) const
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| args | ArgumentTypes... | Arguments to pass to the delegates to be invoked |

### Return Value

Return value of the last invoked delegate

## See Also

* Class [MulticastDelegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)