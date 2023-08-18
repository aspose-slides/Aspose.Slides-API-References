---
title: what()
second_title: Aspose.Slides for C++ API Reference
description: "Implements what() method which is called by ExceptionWrapper class. Despite of the fact that this class is not inherited from std::exception derived classes can use protected/private members to implement their logic. Moving this method implementation to the ExceptionWrapper may broke that logic."
type: docs
weight: 92
url: /system/details_exception/what/
---
## Details_Exception::what() const method


Implements [what()](./) method which is called by [ExceptionWrapper](../../exceptionwrapper/) class. Despite of the fact that this class is not inherited from std::exception derived classes can use protected/private members to implement their logic. Moving this method implementation to the [ExceptionWrapper](../../exceptionwrapper/) may broke that logic.

```cpp
virtual const char * System::Details_Exception::what() const noexcept
```


### Return Value

The description of the exception.

## See Also

* Class [Details_Exception](../)
* Namespace [System](../../)
* Library [Aspose.Slides](../../../)