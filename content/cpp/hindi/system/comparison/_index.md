---
title: Comparison
second_title: Aspose.Slides C++ के लिए API रेफ़रेंस
description: "एक पॉइंटर का प्रतिनिधित्व करता है जो उसी प्रकार की दो वस्तुओं की तुलना करने वाले मेथड की ओर इशारा करता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शनों को मान द्वारा या रेफ़रेंस द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं का प्रबंधन करने के लिए कभी भी System::SmartPtr क्लास का उपयोग न करें।"
type: docs
weight: 183
url: /hi/system/comparison/
---
## तुलना क्लास

एक पॉइंटर को दर्शाता है जो उसी प्रकार की दो वस्तुओं की तुलना करने वाले मेथड की ओर इशारा करता है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और फ़ंक्शन को मान द्वारा या संदर्भ द्वारा पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी [System::SmartPtr](../smartptr/) क्लास का उपयोग न करें।

```cpp
template<typename T>class Comparison : public System::MulticastDelegate<int(T, T)>
```

### टेम्प्लेट पैरामीटर

| पैरामीटर | वर्णन |
| --- | --- |
| T | मेथड द्वारा तुलना की जाने वाली वस्तुओं का प्रकार |

## मेथड्स

| मेथड | वर्णन |
| --- | --- |
| **bool** [operator()](./operator_call/)(T, T) | वर्तमान वस्तु द्वारा इंगित किए गए इनवोकेबल ऑब्जेक्ट को बुलाता है। |

## टिप्पणियाँ

```cpp
#include "system/comparison.h"
#include "system/console.h"
#include "system/exceptions.h"
#include "system/string.h"
#include <algorithm>
#include <initializer_list>
#include <vector>

using namespace System;

// डायनमिक एरे को दर्शाने वाला टेम्प्लेट क्लास।
template <typename T>
class MyArray
{
  // एरे डेटा को संग्रहित करने के लिए उपयोग किया जाता है।
  std::vector<T> m_data;

public:
  // हमारे डायनमिक एरे का नया इंस्टेंस बनाता है।
  MyArray(const std::initializer_list<T>& source) : m_data(source) {};

  // एरे डेटा को सॉर्ट करने के लिए उपयोग किया जाता है।
  // 'System::Comparison' टेम्प्लेट क्लास।
  void Sort(Comparison<T> comparison)
  {
    if (comparison.IsNull())
    {
      throw ArgumentNullException(u"comparison");
    }
    std::sort(m_data.begin(), m_data.end(), comparison);
  }

  // हमारे डायनमिक एरे में संग्रहीत तत्वों की संख्या लौटाता है।
  size_t get_Size()
  {
    return m_data.size();
  }

  // निर्दिष्ट इंडेक्स पर तत्व प्राप्त करने के लिए उपयोग किया जाता है।
  T& operator[](int index)
  {
    if (index < 0 || index >= m_data.size())
    {
      throw IndexOutOfRangeException(u"index");
    }
    return m_data[index];
  }
};

int main() {
  // निर्दिष्ट तत्वों के साथ MyArray क्लास का एक इंस्टेंस बनाएं।
  MyArray<String> arr = {u"a", u"e", u"c", u"b", u"d"};

  // डायनमिक एरे के तत्वों को आरोही क्रम में सॉर्ट करें।
  arr.Sort([](const String &a, const String &b) -> int
  {
    return String::Compare(a, b);
  });

  // डायनमिक एरे के तत्वों को प्रिंट करें।
  for (auto i = 0; i < arr.get_Size(); ++i)
  {
    Console::WriteLine(arr[i]);
  }

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
a
b
c
d
e
*/
```

## देखें

* नामस्थान [System](../)
* Library [Aspose.Slides](../../)