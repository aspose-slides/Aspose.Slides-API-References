---
title: EventHandler
second_title: Aspose.Slides for C++ API संदर्भ
description: "एक विधि को दर्शाता है जो एक घटना पर प्रतिक्रिया देती है और उसे प्रक्रिया करती है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और मान या संदर्भ द्वारा फ़ंक्शनों को पास किया जाना चाहिए। इस प्रकार की वस्तुओं को प्रबंधित करने के लिए कभी भी System::SmartPtr क्लास का उपयोग न करें।"
type: docs
weight: 3706
url: /hi/system/eventhandler/
---
## EventHandler typedef

एक विधि को दर्शाता है जो एक घटना पर प्रतिक्रिया देती है और उसे प्रक्रिया करती है। इस प्रकार को स्टैक पर आवंटित किया जाना चाहिए और मान या संदर्भ द्वारा फ़ंक्शनों को पास किया जाना चाहिए। कभी भी [System::SmartPtr](../smartptr/) क्लास का उपयोग इस प्रकार की वस्तुओं को प्रबंधित करने के लिए न करें।

```cpp
using System::EventHandler = typedef MulticastDelegate<void(System::SharedPtr<Object>, TEventArgs)>
```

## संबंधित देखें

* नामस्थान [System](../)
* लाइब्रेरी [Aspose.Slides](../../)