---
title: operator=()
second_title: Aspose.Slides for C++ API Reference
description: 
type: docs
weight: 14
url: /system/delegate_tmpl_returntype_lbrace_argumenttypes_dots_rbrace__end_tmpl/operator_equal/
---
## Delegate< ReturnType(ArgumentTypes...)>::operator=(const Delegate\&) method




```cpp
Delegate & System::Delegate<ReturnType(ArgumentTypes...)>::operator=(const Delegate &)=default
```

## Delegate< ReturnType(ArgumentTypes...)>::operator=(Delegate\&&) method


Moving assignment operator. Takes the ownership of an entity pointed to by the specified delegate.

```cpp
Delegate & System::Delegate<ReturnType(ArgumentTypes...)>::operator=(Delegate &&o) noexcept
```


### Arguments

| Parameter | Type | Description |
| --- | --- | --- |
| o | [Delegate](../delegate/)\&& | The Delegate object to move the pointed to entity from |

### Return Value

A reference to the self

## See Also

* Method [Delegate](../delegate/)
* Class [Delegate< ReturnType(ArgumentTypes...)>](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)