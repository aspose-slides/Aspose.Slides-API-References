---
title: License()
second_title: Aspose.Slides for C++ API Reference
description: Initializes a new instance of this class.
type: docs
weight: 1
url: /cpp/aspose.slides/license/license/
---
## License::License() constructor


Initializes a new instance of this class.

```cpp
Aspose::Slides::License::License()
```

## Remarks


In this example, an attempt will be made to find a license file named MyLicense.lic in the folder that contains the component, in the folder that contains the calling assembly, in the folder of the entry assembly and then in the embedded resources of the calling assembly. 
```cpp
auto license = MakeObject<License>();
license->SetLicense(u"MyLicense.lic");
```

## See Also

* Class [License](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)
