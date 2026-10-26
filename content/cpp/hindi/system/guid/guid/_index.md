---
title: Guid()
second_title: Aspose.Slides for C++ API संदर्भ
description: ऐसे सभी शून्य वाले GUID का प्रतिनिधित्व करने वाला ऑब्जेक्ट बनाता है।
type: docs
weight: 1
url: /hi/system/guid/guid/
---
## Guid::Guid() कंस्ट्रक्टर

एक ऑब्जेक्ट बनाता है जो सभी शून्य वाले GUID का प्रतिनिधित्व करता है।

```cpp
System::Guid::Guid()
```

## Guid::Guid(const ArrayPtr\<uint8_t\>\&) कंस्ट्रक्टर

एक ऑब्जेक्ट बनाता है जो अनसाइन्ड 8-बिट पूर्णांक मानों की एरे के रूप में निर्दिष्ट GUID का प्रतिनिधित्व करता है।

```cpp
System::Guid::Guid(const ArrayPtr<uint8_t> &b)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| b | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | GUID के अलग-अलग बाइट्स वाला बाइट-एरे |

## Guid::Guid(const System::Details::ArrayView\<uint8_t\>\&) कंस्ट्रक्टर

एक ऑब्जेक्ट बनाता है जो अनसाइन्ड 8-बिट पूर्णांक मानों के एरे व्यू के रूप में निर्दिष्ट GUID का प्रतिनिधित्व करता है।

```cpp
System::Guid::Guid(const System::Details::ArrayView<uint8_t> &b)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| b | const System::Details::ArrayView\<**uint8_t**\>\& | GUID के अलग-अलग बाइट्स वाला बाइट-एरे |

## Guid::Guid(const String\&) कंस्ट्रक्टर

एक ऑब्जेक्ट बनाता है जो स्ट्रिंग के रूप में निर्दिष्ट GUID का प्रतिनिधित्व करता है।

```cpp
System::Guid::Guid(const String &g)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| g | const [String](../../string/)\& | निर्मित ऑब्जेक्ट द्वारा प्रतिनिधित्व किए जाने वाले GUID का स्ट्रिंग प्रतिनिधित्व |

## Guid::Guid(int32_t, int16_t, int16_t, const ArrayPtr\<uint8_t\>\&) कंस्ट्रक्टर

निर्दिष्ट GUID घटकों से [Guid](../) क्लास का एक इंस्टेंस बनाता है।

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const ArrayPtr<uint8_t> &d)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| a | **int32_t** | GUID के बिट्स 0-31 |
| b | **int16_t** | GUID के बिट्स 32-47 |
| c | **int16_t** | GUID के बिट्स 48-63 |
| d | const [ArrayPtr](../../arrayptr/)\<**uint8_t**\>\& | GUID के बिट्स 64-127 वाला बाइट-एरे |

## Guid::Guid(int32_t, int16_t, int16_t, const System::Details::ArrayView\<uint8_t\>\&) कंस्ट्रक्टर

निर्दिष्ट GUID घटकों से [Guid](../) क्लास का एक इंस्टेंस बनाता है।

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, const System::Details::ArrayView<uint8_t> &d)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| a | **int32_t** | GUID के बिट्स 0-31 |
| b | **int16_t** | GUID के बिट्स 32-47 |
| c | **int16_t** | GUID के बिट्स 48-63 |
| d | const System::Details::ArrayView\<**uint8_t**\>\& | GUID के बिट्स 64-127 वाला बाइट-एरे व्यू |

## Guid::Guid(int32_t, int16_t, int16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) कंस्ट्रक्टर

निर्दिष्ट अनसाइन्ड इंटेजर और बाइट्स से [Guid](../) क्लास का एक इंस्टेंस बनाता है।

```cpp
System::Guid::Guid(int32_t a, int16_t b, int16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| a | **int32_t** | GUID के बिट्स 0-31 |
| b | **int16_t** | GUID के बिट्स 32-47 |
| c | **int16_t** | GUID के बिट्स 48-63 |
| d | **uint8_t** | GUID के बिट्स 64-71 |
| e | **uint8_t** | GUID के बिट्स 72-79 |
| f | **uint8_t** | GUID के बिट्स 80-87 |
| g | **uint8_t** | GUID के बिट्स 88-95 |
| h | **uint8_t** | GUID के बिट्स 96-103 |
| i | **uint8_t** | GUID के बिट्स 104-111 |
| j | **uint8_t** | GUID के बिट्स 112-119 |
| k | **uint8_t** | GUID के बिट्स 120-127 |

## Guid::Guid(uint32_t, uint16_t, uint16_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t, uint8_t) कंस्ट्रक्टर

निर्दिष्ट अनसाइन्ड इंटेजर और बाइट्स से [Guid](../) क्लास का एक इंस्टेंस बनाता है।

```cpp
System::Guid::Guid(uint32_t a, uint16_t b, uint16_t c, uint8_t d, uint8_t e, uint8_t f, uint8_t g, uint8_t h, uint8_t i, uint8_t j, uint8_t k)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| a | **uint32_t** | GUID के बिट्स 0-31 |
| b | **uint16_t** | GUID के बिट्स 32-47 |
| c | **uint16_t** | GUID के बिट्स 48-63 |
| d | **uint8_t** | GUID के बिट्स 64-71 |
| e | **uint8_t** | GUID के बिट्स 72-79 |
| f | **uint8_t** | GUID के बिट्स 80-87 |
| g | **uint8_t** | GUID के बिट्स 88-95 |
| h | **uint8_t** | GUID के बिट्स 96-103 |
| i | **uint8_t** | GUID के बिट्स 104-111 |
| j | **uint8_t** | GUID के बिट्स 112-119 |
| k | **uint8_t** | GUID के बिट्स 120-127 |

## Guid::Guid(const Guid\&) कंस्ट्रक्टर

एक ऑब्जेक्ट बनाता है जो निर्दिष्ट ऑब्जेक्ट के समान GUID का प्रतिनिधित्व करता है।

```cpp
System::Guid::Guid(const Guid &guid)
```

### आर्गुमेंट्स

| पैरामीटर | टाइप | विवरण |
| --- | --- | --- |
| guid | const [Guid](../)\& | GUID मान को कॉपी करने हेतु [Guid](../) ऑब्जेक्ट |

## संबंधित देखें

* Typedef [ArrayPtr](../../arrayptr/)
* क्लास [Guid](../)
* क्लास [String](../../string/)
* नेमस्पेस [System](../../)
* लाइब्रेरी [Aspose.Slides](../../../)