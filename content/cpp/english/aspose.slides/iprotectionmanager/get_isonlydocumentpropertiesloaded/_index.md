---
title: get_IsOnlyDocumentPropertiesLoaded()
second_title: Aspose.Slides for C++ API Reference
description: This property makes sense, if presentation file is password protected and document properties of this file are public. Value of true means that only document properties are loaded from an encrypted presentation file without use of password. Value of false means that entire encrypted presentation is loaded with use of right password, not only document properties are loaded. If presentation isn't encrypted then property value is always false. If document properties of an encrypted file aren't public then property value is always false. If PresentationEx.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded property value is always false. Read-only bool.
type: docs
weight: 40
url: /aspose.slides/iprotectionmanager/get_isonlydocumentpropertiesloaded/
---
## IProtectionManager::get_IsOnlyDocumentPropertiesLoaded() method


This property makes sense, if presentation file is password protected and document properties of this file are public. Value of true means that only document properties are loaded from an encrypted presentation file without use of password. Value of false means that entire encrypted presentation is loaded with use of right password, not only document properties are loaded. If presentation isn't encrypted then property value is always false. If document properties of an encrypted file aren't public then property value is always false. If PresentationEx.EncryptDocumentProperties is true than IsOnlyDocumentPropertiesLoaded property value is always false. Read-only **bool**.

```cpp
virtual bool Aspose::Slides::IProtectionManager::get_IsOnlyDocumentPropertiesLoaded()=0
```

## See Also

* Class [IProtectionManager](../)
* Namespace [Aspose::Slides](../../)
* Library [Aspose.Slides](../../../)