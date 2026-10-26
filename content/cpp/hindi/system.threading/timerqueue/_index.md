---
title: TimerQueue
second_title: Aspose.Slides for C++ API संदर्भ
description: क्यू जो Timer ऑब्जेक्ट्स को संभालता है। यह केवल एक कार्यान्वयन है। Timer ऑब्जेक्ट्स स्वयं वहाँ पंजीकरण करते हैं, उनका उपयोग करने के लिए आपको ऐसा करने की आवश्यकता नहीं है - इसके बजाय Timer क्लास API का उपयोग करें। यह एक सिंगलटन प्रकार है जहाँ मेमोरी प्रबंधन एक्सेस फ़ंक्शन(ओं) द्वारा किया जाता है। आपको इसे सीधे इंस्टैंस नहीं बनाना चाहिए।
type: docs
weight: 261
url: /hi/system.threading/timerqueue/
---
## TimerQueue क्लास

Queue जो [Timer](../timer/) ऑब्जेक्ट्स को संभालता है। यह केवल एक कार्यान्वयन है। [Timer](../timer/) ऑब्जेक्ट्स स्वयं वहाँ पंजीकृत होते हैं, उनका उपयोग करने के लिए आपको ऐसा करने की आवश्यकता नहीं है - इसके बजाय [Timer](../timer/) क्लास API का उपयोग करें। यह एक सिंगलटन प्रकार है जहाँ मेमोरी प्रबंधन एक्सेस फ़ंक्शन(ओं) द्वारा किया जाता है। आपको इसे सीधे इंस्टैंस नहीं बनाना चाहिए।

```cpp
class TimerQueue
```

## मेथड्स

| मेथड | विवरण |
| --- | --- |
| **bool** [Add](./add/)([Timer](../timer/) *) | क्यू में टाइमर पंजीकृत करता है। |
| **bool** [Delete](./delete/)([Timer](../timer/) *) | क्यू से टाइमर हटाता है। |
| static [TimerQueue](./)\& [GetInstance](./getinstance/)() | कार्यान्वयन सिंगलटन। |
| static void [JoinWorkerThread](./joinworkerthread/)() | वर्कर थ्रेड से जुड़ता है। यदि आवश्यक हो तो अनंत तक प्रतीक्षा करता है। |
| void [operator=](./operator_equal/)(const [TimerQueue](./)\&) | कोई प्रतिलिपि नहीं। |
|  [TimerQueue](./timerqueue/)(const [TimerQueue](./)\&) | कोई प्रतिलिपि नहीं। |
## देखें

* नेमस्पेस [System::Threading](../)
* लाइब्रेरी [Aspose.Slides](../../)