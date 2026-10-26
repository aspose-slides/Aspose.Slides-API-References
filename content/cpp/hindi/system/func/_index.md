---
title: Func
second_title: Aspose.Slides C++ के लिए API रेफरेंस
description: "फ़ंक्शन प्रतिनिधि। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी System::SmartPtr क्लास का उपयोग न करें।"
type: docs
weight: 859
url: /hi/system/func/
---
## Func क्लास

फ़ंक्शन प्रतिनिधि। यह प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान या संदर्भ द्वारा पास किया जाना चाहिए। कभी भी [System::SmartPtr](../smartptr/) क्लास का प्रयोग इस प्रकार की वस्तुओं को प्रबंधित करने के लिए न करें।

```cpp
template<typename...>class Func : public System::MulticastDelegate<::System::Detail::FuncArgsReorderer<void(), Args...>::type>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | विवरण |
| --- | --- |
| Args | Call arguments, then mandatory return type. |

## विधियाँ

| मेथड | विवरण |
| --- | --- |
|  [Func](./func/)() | डिफ़ॉल्ट कंस्ट्रक्टर जो null-Func बनाता है। |
|  [Func](./func/)(T\&&) | कंस्ट्रक्टर जो [Func](./) ऑब्जेक्ट बनाता है और उसे मान (या तो वास्तविक कॉलबैक या nullptr) असाइन करता है। |
|  [Func](./func/)(const [Func](./)\&) | कॉपी कंस्ट्रक्टर। |
|  [Func](./func/)([Func](./)\&&) | मूव कंस्ट्रक्टर। |
| [Func](./)\& [operator=](./operator_equal/)(const [Func](./)\&) | कॉपी असाइनमेंट। |
| [Func](./)\& [operator=](./operator_equal/)([Func](./)\&&) | मूव असाइनमेंट। |
|  [~Func](./~func/)() | डीस्ट्रक्टर। |

## टिप्पणियाँ

```cpp
#include "system/func.h"
#include <iostream"

// यह फ़ंक्शन System::Func प्रतिनिधि का एक इंस्टेंस पैरामीटर के रूप में स्वीकार करता है।
void Print(int x, const System::Func<int, int> &func)
{
  std::cout << func(x) << std::endl;
}

int main()
{
  // System::Func प्रतिनिधि का एक इंस्टेंस बनाएँ।
  auto func = static_cast<System::Func<int, int>>([](int x) -> int
  {
    return x * x;
  });

  // बनाए गए इंस्टेंस को फ़ंक्शन आर्ग्युमेंट के रूप में पास करें।
  Print(1, func);
  Print(2, func);
  Print(3, func);

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
1
4
9
*/
```

## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)