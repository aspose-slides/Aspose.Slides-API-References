---
title: BasicSTDIOStreamWrapper()
second_title: Aspose.Slides for C++ API संदर्भ
description: BasicSTDIOStreamWrapper का एक नया उदाहरण बनाता है।
type: docs
weight: 14
url: /hi/system.io/basicstdiostreamwrapper/basicstdiostreamwrapper/
---
## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(std::basic_iostream\<char_type, traits_type\>\&, STDIOStreamWrappingMode, STDIOStreamPositionPreference) कंस्ट्रक्टर

[BasicSTDIOStreamWrapper](../) का एक नया उदाहरण बनाता है।

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(std::basic_iostream<char_type, traits_type> &str, STDIOStreamWrappingMode mode=STDIOStreamWrappingMode::Binary, STDIOStreamPositionPreference pref_pos=STDIOStreamPositionPreference::Zero)
```

### आर्ग्युमेंट्स

| पैरामीटर | प्रकार | विवरण |
| --- | --- | --- |
| str | std::basic_iostream\<[char_type](../../stdiostreamwrapperbase/char_type/), [traits_type](../../stdiostreamwrapperbase/traits_type/)\>\& | स्ट्रीम के संदर्भ |
| mode | [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/) | रैपिंग मोड |
| pref_pos | [STDIOStreamPositionPreference](../../stdiostreampositionpreference/) | पढ़ने और लिखने की स्थिति के रूप में उपयोग की जाने वाली स्थिति, यदि वे अलग हों |

## BasicSTDIOStreamWrapper::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper\&) कंस्ट्रक्टर

कॉपी कंस्ट्रक्टर। हटाया गया।

```cpp
System::IO::BasicSTDIOStreamWrapper<T, typename>::BasicSTDIOStreamWrapper(const BasicSTDIOStreamWrapper &)=delete
```

## संबंधित देखें

* Enum [STDIOStreamWrappingMode](../../stdiostreamwrappingmode/)
* Enum [STDIOStreamPositionPreference](../../stdiostreampositionpreference/)
* Typedef [char_type](../../stdiostreamwrapperbase/char_type/)
* Typedef [traits_type](../../stdiostreamwrapperbase/traits_type/)
* Class [BasicSTDIOStreamWrapper](../)
* Namespace [System::IO](../../)
* Library [Aspose.Slides](../../../)