---
title: Is()
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 27
url: /hi/system.security.authentication/details_authenticationexception/is/
---
## विवरण_AuthenticationException::Is(const System::TypeInfo\&) const method




```cpp
bool System::Security::Authentication::Details_AuthenticationException::Is(const System::TypeInfo &target) const override
```


### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| target | const [System::TypeInfo](../../../system/typeinfo/)\& | [TypeInfo](../../../system/typeinfo/) स्ट्रक्चर जो उस टाइप का वर्णन करता है जिसके विरुद्ध वर्तमान ऑब्जेक्ट की जाँच की जानी है। |

### वापसी मान

True if object is of tagged type or its subclass, false otherwise.

## टिप्पणियाँ

Check if object represents an instance of type described by targetType. Analog of C# 'is' operator. 

## संबंधित देखें

* Class [TypeInfo](../../../system/typeinfo/)
* Class [Details_AuthenticationException](../)
* Namespace [System::Security::Authentication](../../)
* Library [Aspose.Slides](../../../)