---
title: ContainsAnyExcept()
second_title: C++ के लिए Aspose.Slides API संदर्भ
description: जाँच करता है कि क्या एक read-only span में तीन निर्दिष्ट मानों को छोड़कर कोई तत्व मौजूद है।
type: docs
weight: 66
url: /hi/system.memoryextensions/containsanyexcept/
---
## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&, const T\&) function

जाँच करता है कि क्या एक read-only span में तीन निर्दिष्ट मानों को छोड़कर कोई तत्व मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1, const T &value2)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का тип |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जिस स्पैन में खोज करनी है |
| value0 | const T\& | पहला मान जो बाहर रखा जाना है |
| value1 | const T\& | दूसरा मान जो बाहर रखा जाना है |
| value2 | const T\& | तिसरा मान जो बाहर रखा जाना है |

### वापसी मान

true यदि कोई तत्व निर्दिष्ट मानों से अलग पाया जाता है, false अन्यथा

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&, const T\&) function

जाँच करता है कि क्या एक mutable span में तीन निर्दिष्ट मानों को छोड़कर कोई तत्व मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1, const T &value2)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | जिस mutable स्पैन में खोज करनी है |
| value0 | const T\& | पहला मान जो बाहर रखा जाना है |
| value1 | const T\& | दूसरा मान जो बाहर रखा जाना है |
| value2 | const T\& | तिसरा मान जो बाहर रखा जाना है |

### वापसी मान

true यदि कोई तत्व निर्दिष्ट मानों से अलग पाया जाता है, false अन्यथा

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&, const T\&) function

जाँच करता है कि क्या एक read-only span में दो निर्दिष्ट मानों को छोड़कर कोई तत्व मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value0, const T &value1)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जिस स्पैन में खोज करनी है |
| value0 | const T\& | पहला मान जो बाहर रखा जाना है |
| value1 | const T\& | दूसरा मान जो बाहर रखा जाना है |

### वापसी मान

true यदि कोई तत्व निर्दिष्ट मानों से अलग पाया जाता है, false अन्यथा

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&, const T\&) function

जाँच करता है कि क्या एक mutable span में दो निर्दिष्ट मानों को छोड़कर कोई तत्व मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value0, const T &value1)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | जिस mutable स्पैन में खोज करनी है |
| value0 | const T\& | पहला मान जो बाहर रखा जाना है |
| value1 | const T\& | दूसरा मान जो बाहर रखा जाना है |

### वापसी मान

true यदि कोई तत्व निर्दिष्ट मानों से अलग पाया जाता है, false अन्यथा

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const T\&) function

जाँच करता है कि क्या एक read-only span में निर्दिष्ट मान को छोड़कर कोई तत्व मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const T &value)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जिस स्पैन में खोज करनी है |
| value | const T\& | वह मान जो बाहर रखा जाना है |

### वापसी मान

true यदि कोई तत्व निर्दिष्ट मान से अलग पाया जाता है, false अन्यथा

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const T\&) function

जाँच करता है कि क्या एक mutable span में निर्दिष्ट मान को छोड़कर कोई तत्व मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const T &value)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | जिस mutable स्पैन में खोज करनी है |
| value | const T\& | वह मान जो बाहर रखा जाना है |

### वापसी मान

true यदि कोई तत्व निर्दिष्ट मान से अलग पाया जाता है, false अन्यथा

## System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan\<T\>\&, const ReadOnlySpan\<T\>\&) function

जाँच करता है कि क्या एक read-only span में दूसरे span के मानों को छोड़कर कोई तत्व मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const ReadOnlySpan<T> &span, const ReadOnlySpan<T> &values)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | जिस स्पैन में खोज करनी है |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | बाहर रखने के लिए मानों का स्पैन |

### वापसी मान

true यदि कोई तत्व values में नहीं है, तो पाया जाता है, false अन्यथा

## System::MemoryExtensions::ContainsAnyExcept(const Span\<T\>\&, const ReadOnlySpan\<T\>\&) function

जाँच करता है कि क्या एक mutable span में read-only span के मानों को छोड़कर कोई तत्व मौजूद है।

```cpp
template<typename T> bool System::MemoryExtensions::ContainsAnyExcept(const Span<T> &span, const ReadOnlySpan<T> &values)
```

### टेम्पलेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| T | स्पैन्स में तत्वों का प्रकार |

### आर्ग्यूमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| span | const [Span](../../system/span/)\<T\>\& | जिस mutable स्पैन में खोज करनी है |
| values | const [ReadOnlySpan](../../system/readonlyspan/)\<T\>\& | बाहर रखने के लिए read-only मानों का स्पैन |

### वापसी मान

true यदि कोई तत्व values में नहीं है, तो पाया जाता है, false अन्यथा

## संबंधित देखें

* क्लास [ReadOnlySpan](../../system/readonlyspan/)
* क्लास [Span](../../system/span/)
* नेमस्पेस [System::MemoryExtensions](../)
* लाइब्रेरी [Aspose.Slides](../../)