---
title: get_ActiveXControlBinary()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: जब सतत करने के लिए उपयोग की जाने वाली विधि PersistStream, PersistStreamInit या PersistStorage हो, तब ActiveX नियंत्रण की निरंतरता को निर्दिष्ट करता है।
type: docs
weight: 118
url: /hi/aspose.slides/control/get_activexcontrolbinary/
---
## Control::get_ActiveXControlBinary() विधि


जब सतत करने के लिए उपयोग की जाने वाली विधि PersistStream, PersistStreamInit या PersistStorage है, तब एक ActiveX control की निरंतरता को निर्दिष्ट करता है।

```cpp
System::ArrayPtr<uint8_t> Aspose::Slides::Control::get_ActiveXControlBinary() override
```

## टिप्पणियाँ


अगला उदाहरण ActiveXControlBinary प्रॉपर्टी का उपयोग करके ActiveX गुणों को बदलने को दर्शाता है: 
```cpp
if (control->get_Persistence() == PersistenceType::PersistPropertyBag)
{
    control->get_Properties()->idx_set(u"Value", value);
}
else
{
    // अपनी स्वयं की विधि का उपयोग करके ActiveX गुणों को उसकी बाइनरी फ़ाइल में संग्रहीत प्रबंधित करें
    YourMethodHere(control->get_ActiveXControlBinary());
}
```

## संबंधित देखें

* Typedef [ArrayPtr](../../../system/arrayptr/)
* क्लास [Control](../)
* नामस्थान [Aspose::Slides](../../)
* लाइब्रेरी [Aspose.Slides](../../../)