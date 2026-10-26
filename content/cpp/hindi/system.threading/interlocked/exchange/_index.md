---
title: Exchange()
second_title: Aspose.Slides for C++ API संदर्भ
description: "चर पर मान का विनिमय करता है: नया मान संग्रहीत करता है और संग्रहीत करने से तुरंत पहले चर के पास मौजूद मान लौटाता है।"
type: docs
weight: 66
url: /hi/system.threading/interlocked/exchange/
---
## Interlocked::Exchange(T\&, T) विधि

चर पर मान का विनिमय करता है: नया मान संग्रहीत करता है और संग्रहीत करने से तुरंत पहले चर के पास मौजूद मान लौटाता है।

```cpp
template<typename T> static std::enable_if<IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T | चर प्रकार। |

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | T\& | परिवर्तित करने के लिए चर संदर्भ। |
| value | T | संग्रहीत करने के लिए मान। |

### वापसी मान

चर का वह मान जो बदलने से ठीक पहले था।

## Interlocked::Exchange(T\&, T) विधि

चर पर मान का विनिमय करता है: नया मान संग्रहीत करता है और संग्रहीत करने से तुरंत पहले चर के पास मौजूद मान लौटाता है। अभी लागू नहीं है।

```cpp
template<typename T> static std::enable_if<!IsSupportedInt<T>, T>::type System::Threading::Interlocked::Exchange(T &location1, T value)
```

### टेम्प्लेट पैरामीटर

| Parameter | Description |
| --- | --- |
| T | चर प्रकार। |

### आर्ग्युमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| location1 | T\& | परिवर्तित करने के लिए चर संदर्भ। |
| value | T | संग्रहीत करने के लिए मान। |

### वापसी मान

चर का वह मान जो बदलने से ठीक पहले था।

## संबंधित देखें

* क्लास [Interlocked](../)
* नामस्थान [System::Threading](../../)
* लाइब्रेरी [Aspose.Slides](../../../)