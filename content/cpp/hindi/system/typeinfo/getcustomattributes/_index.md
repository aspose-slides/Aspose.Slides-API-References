---
title: GetCustomAttributes()
second_title: Aspose.Slides के लिए C++ API रेफ़रेंस
description: टाइप पर लागू सभी कस्टम एट्रिब्यूट्स को दर्शाने वाले ऑब्जेक्ट्स सहित एक एरे लौटाता है।
type: docs
weight: 586
url: /hi/system/typeinfo/getcustomattributes/
---
## TypeInfo::GetCustomAttributes() const मेथड

टाइप पर लागू सभी कस्टम एट्रिब्यूट्स को दर्शाने वाले ऑब्जेक्ट्स सहित एक एरे लौटाता है।

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes() const
```

## TypeInfo::GetCustomAttributes(const TypeInfo\&, bool) const मेथड

टाइप पर लागू विशिष्ट एट्रिब्यूट्स को दर्शाने वाले ऑब्जेक्ट्स सहित एक एरे लौटाता है।

```cpp
ArrayPtr<ObjectPtr> System::TypeInfo::GetCustomAttributes(const TypeInfo &attributeType, bool inherit) const
```

### Arguments

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| attributeType | const [TypeInfo](../)\& | खोजे जाने वाले एट्रिब्यूट का प्रकार। |
| inherit | **bool** | क्या विरासत में मिले एट्रिब्यूट्स को भी देखना है। |

## संबंधित देखें

* Typedef [ArrayPtr](../../arrayptr/)
* क्लास [SmartPtr](../../smartptr/)
* क्लास [TypeInfo](../)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)