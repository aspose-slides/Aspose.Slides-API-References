---
title: WrapSTDIOStream()
second_title: Aspose.Slides for C++ API संदर्भ
description: "std::basic_istream- जैसा स्ट्रीम के लिए रैपर फ़ंक्शन।"
type: docs
weight: 469
url: /hi/system.io/wrapstdiostream/
---
## System::IO::WrapSTDIOStream(std::basic_istream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) फ़ंक्शन

std::basic_istream- जैसा स्ट्रीम के लिए रैपर फ़ंक्शन।

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_istream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| stream | std::basic_istream\<char_type, traits_type\>\& | std::basic_istream- जैसा स्ट्रीम |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | रैपिंग मोड |

### रिटर्न वैल्यू

[BasicSTDIStreamWrapper](../basicstdistreamwrapper/) रैपर

## System::IO::WrapSTDIOStream(std::basic_ostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode) फ़ंक्शन

std::basic_ostream- जैसा स्ट्रीम के लिए रैपर फ़ंक्शन।

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_ostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| stream | std::basic_ostream\<char_type, traits_type\>\& | std::basic_ostream- जैसा स्ट्रीम |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | रैपिंग मोड |

### रिटर्न वैल्यू

[BasicSTDOStreamWrapper](../basicstdostreamwrapper/) रैपर

## System::IO::WrapSTDIOStream(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) फ़ंक्शन

std::basic_iostream- जैसा स्ट्रीम के लिए रैपर फ़ंक्शन।

```cpp
template<typename char_type,typename traits_type> SharedPtr<Stream> System::IO::WrapSTDIOStream(std::basic_iostream<char_type, traits_type> &stream, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | वर्णन |
| --- | --- | --- |
| stream | std::basic_iostream\<char_type, traits_type\>\& | std::basic_iostream- जैसा स्ट्रीम |
| mode | [STDIOStreamWrappingMode](../stdiostreamwrappingmode/) | रैपिंग मोड |
| pref_pos | [STDIOStreamPositionPreference](../stdiostreampositionpreference/) | पढ़ने और लिखने की स्थिति के रूप में प्राधान्य दिया जाने वाला पोजीशन, यदि वे अलग हों |

### रिटर्न वैल्यू

[BasicSTDIOStreamWrapper](../basicstdiostreamwrapper/) रैपर

## देखें

* Enum [STDIOStreamWrappingMode](../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../stdiostreampositionpreference/)
* Typedef [SharedPtr](../../system/sharedptr/)
* Class [Stream](../stream/)
* Namespace [System::IO](../)
* Library [Aspose.Slides](../../)