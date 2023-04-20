---
title: ColorTranslator
second_title: Aspose.Slides for C++ API Reference
description: "Performs color translations. Objects of this class should only be allocated using System::MakeObject() function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into System::SmartPtr pointer and use this pointer to pass it to functions as argument."
type: docs
weight: 66
url: /cpp/system.drawing/colortranslator/
---
## ColorTranslator class


Performs color translations. Objects of this class should only be allocated using [System::MakeObject()](../../system/makeobject/) function. Never create instance of this type on stack or using operator new, as it will result in runtime errors and/or assertion faults. Always wrap this class into [System::SmartPtr](../../system/smartptr/) pointer and use this pointer to pass it to functions as argument.

```cpp
class ColorTranslator
```

## Methods

| Method | Description |
| --- | --- |
| static [Color](../color/) [FromHtml](./fromhtml/)(const [System::String](../../system/string/)\&) | Converts the specified HTML color representation to the equvivalent [Color](../color/) object. |
| static [Color](../color/) [FromWin32](./fromwin32/)(int) | Converts the specified [Windows](../../system.windows/) color to the equvivalent [Color](../color/) object. |
| static [String](../../system/string/) [ToHtml](./tohtml/)(const [Color](../color/)\&) | Converts the specified [Color](../color/) object to the string representation of equivalent HTML color. |
## See Also

* Namespace [System::Drawing](../)
* Library [Aspose.Slides](../../)