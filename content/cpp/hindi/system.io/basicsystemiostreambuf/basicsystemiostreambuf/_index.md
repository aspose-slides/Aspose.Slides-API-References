---
title: BasicSystemIOStreamBuf()
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: BasicSystemIOStreamBuf का नया उदाहरण बनाता है।
type: docs
weight: 14
url: /hi/system.io/basicsystemiostreambuf/basicsystemiostreambuf/
---
## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf() कन्स्ट्रक्टर

नया उदाहरण बनाता है [BasicSystemIOStreamBuf](../) का।

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf()
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const SharedPtr\<Stream\>\&, SystemIOStreamWrappingMode, const std::locale\&) कन्स्ट्रक्टर

नया उदाहरण बनाता है [BasicSystemIOStreamBuf](../) का।

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const SharedPtr<Stream> &str, SystemIOStreamWrappingMode mode=SystemIOStreamWrappingMode::Binary, const std::locale &locale=std::locale())
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| str | const [SharedPtr](../../../system/sharedptr/)\<[Stream](../../stream/)\>\& | स्ट्रीम के लिए स्मार्ट पॉइंटर |
| mode | [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/) | रैपिंग मोड |
| locale | const std::locale\& | [Stream](../../stream/) की लोकैल |

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf\&) कन्स्ट्रक्टर

कॉपी कन्स्ट्रक्टर। हटाया गया।

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(const BasicSystemIOStreamBuf &)=delete
```

## BasicSystemIOStreamBuf::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf\&&) कन्स्ट्रक्टर

मूव कन्स्ट्रक्टर।

```cpp
System::IO::BasicSystemIOStreamBuf<Elem, Traits>::BasicSystemIOStreamBuf(BasicSystemIOStreamBuf &&right) noexcept
```

### आर्ग्यूमेंट्स

| Parameter | Type | Description |
| --- | --- | --- |
| right | [BasicSystemIOStreamBuf](../)\&& | [Object](../../../system/object/) को मूव किया जाना है |

## संबंधित देखें

* Enum [SystemIOStreamWrappingMode](../../systemiostreamwrappingmode/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [BasicSystemIOStreamBuf](../)
* Class [Stream](../../stream/)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)