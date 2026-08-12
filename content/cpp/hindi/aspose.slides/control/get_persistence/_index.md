---
title: get_Persistence()
second_title: Aspose.Slides for C++ API संदर्भ
description: ActiveX नियंत्रण की प्रॉपर्टीज़ को संग्रहीत करने के लिए उपयोग की जाने वाली विधि को प्राप्त करता है। केवल पढ़ने योग्य PersistenceType.
type: docs
weight: 1
url: /hi/aspose.slides/control/get_persistence/
---
## Control::get_Persistence() विधि

ActiveX नियंत्रण की प्रॉपर्टीज़ को संग्रहीत करने के लिए उपयोग की जाने वाली विधि को प्राप्त करता है। केवल पढ़ने योग्य [PersistenceType](../../persistencetype/).

```cpp
PersistenceType Aspose::Slides::Control::get_Persistence() override
```

## टिप्पणियाँ

अगला उदाहरण Persistence प्रॉपर्टी का उपयोग दर्शाता है ताकि यह जांचा जा सके कि ActiveX ऑब्जेक्ट की प्रॉपर्टीज़ को XML आधारित ActiveX प्रॉपर्टीज़ के रूप में बदलना संभव है या नहीं: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // ActiveX प्रॉपर्टीज़ को उसकी बाइनरी फ़ाइल में संग्रहीत करने के लिए अपनी विधि का उपयोग करें
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## देखें

* Enum [PersistenceType](../../persistencetype/)
* क्लास [Control](../)
* नेमस्पेस [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)