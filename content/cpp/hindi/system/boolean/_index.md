---
title: Boolean
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: System.Boolean .Net प्रकार के स्थैतिक सदस्यों को रखने वाली क्लास।
type: docs
weight: 79
url: /hi/system/boolean/
---
## Boolean वर्ग


क्लास जो [System.Boolean](./) .[Net](../../system.net/) प्रकार के स्थैतिक सदस्य रखती है।

```cpp
class Boolean
```

## विधियाँ

| विधि | विवरण |
| --- | --- |
| static **bool** [Parse](./parse/)(const [String](../string/)\&) | निर्दिष्ट स्ट्रिंग को bool प्रकार के मान में परिवर्तित करता है। |
| static **bool** [TryParse](./tryparse/)(const [String](../string/)\&, **bool**\&) | निर्दिष्ट स्ट्रिंग को bool प्रकार के मान में परिवर्तित करता है। |
## फ़ील्ड्स

| फ़ील्ड | विवरण |
| --- | --- |
| static [FalseString](./falsestring/) | [String](../string/) का 'false' बूलियन मान का प्रतिनिधित्व। |
| static [TrueString](./truestring/) | [String](../string/) का 'true' बूलियन मान का प्रतिनिधित्व। |
## टिप्पणियाँ



```cpp
#include <system/boolean.h>

using namespace System;

int main()
{
  // बूलियन वेरिएबल बनाएं।
  bool isWeekend = false;

  // इनपुट स्ट्रिंग को पार्स करें और परिणाम प्रिंट करें।
  if (Boolean::TryParse(u"True", isWeekend))
  {
    std::cout << "Is weekend: " << (isWeekend ? "Yes" : "No");
  }
  else
  {
    std::cerr << "Something went wrong" << std::endl;
  }

  return 0;
}
/*
यह कोड उदाहरण निम्नलिखित आउटपुट उत्पन्न करता है:
Is weekend: Yes
*/
```

## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)