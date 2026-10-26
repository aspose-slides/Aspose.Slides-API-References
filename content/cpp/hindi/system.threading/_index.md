---
title: "System::Threading"
second_title: Aspose.Slides के लिए C++ API संदर्भ
description: 
type: docs
weight: 1002
url: /hi/system.threading/
---
## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [AutoResetEvent](./autoresetevent/) | स्वतः रीसेट होने वाला थ्रेड को सूचित करने के लिये इवेंट। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन फ़ॉल्ट्स का कारण बनेगा। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन के आर्ग्युमेंट के रूप में पास करें। |
| [CancellationToken](./cancellationtoken/) | ऑपरेशनों को रद्द करने के लिये संकेत प्रसारित करता है। यह क्लास थ्रेड्स के बीच सहयोगी कैंसलेशन के लिये एक तंत्र प्रदान करती है, जिससे एक थ्रेड अन्य थ्रेड्स को सूचित कर सके कि ऑपरेशन को रद्द किया जाना चाहिए। |
| [CancellationTokenRegistration](./cancellationtokenregistration/) | कैंसलेशन टोकन कॉलबैक के लिए रजिस्टरेशन को दर्शाता है। |
| [CancellationTokenSource](./cancellationtokensource/) | एक कैंसलेशन टोकन स्रोत जो कैंसलेशन सूचनाओं को ट्रिगर करने के लिये उपयोग किया जा सकता है। |
| [Details_SemaphoreFullException](./details_semaphorefullexception/) |  |
| [Details_SynchronizationLockException](./details_synchronizationlockexception/) |  |
| [Details_ThreadAbortException](./details_threadabortexception/) |  |
| [Details_ThreadInterruptedException](./details_threadinterruptedexception/) |  |
| [Details_ThreadStateException](./details_threadstateexception/) |  |
| [EventWaitHandle](./eventwaithandle/) | थ्रेड को सूचित करने के लिये इवेंट जो स्वतः रीसेट नहीं होता। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन फ़ॉल्ट्स का कारण बनेगा। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन के आर्ग्युमेंट के रूप में पास करें। |
| [Interlocked](./interlocked/) | थ्रेड-सेफ ऑपरेशनों के लिये API प्रदान करता है। यह एक स्टैटिक टाइप है जिसमें कोई इंस्टेंस सर्विस नहीं है। आपको इसे किसी भी माध्यम से इंस्टैंस नहीं बनाना चाहिए। |
| [ManualResetEvent](./manualresetevent/) | स्वतः रीसेट न होने वाला थ्रेड को सूचित करने के लिये इवेंट। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन फ़ॉल्ट्स का कारण बनेगा। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन के आर्ग्युमेंट के रूप में पास करें। |
| [Monitor](./monitor/) | क्लास [Monitor](./monitor/) एक तंत्र प्रदान करता है जो ऑब्जेक्ट्स तक पहुँच को समक्रमित करता है। |
| [Mutex](./mutex/) | [Mutex](./mutex/) कार्यान्वयन। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन फ़ॉल्ट्स का कारण बनेगा। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन के आर्ग्युमेंट के रूप में पास करें। |
| [Semaphore](./semaphore/) | [Semaphore](./semaphore/) कार्यान्वयन। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन फ़ॉल्ट्स का कारण बनेगा। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन के आर्ग्युमेंट के रूप में पास करें। |
| [SynchronizationContext](./synchronizationcontext/) | विभिन्न समक्रमण ऑपरेशनों में समक्रमण संदर्भ को प्रसारित करने के लिये मूल कार्यक्षमता प्रदान करता है। |
| [Thread](./thread/) | [Thread](./thread/) कार्यान्वयन। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन फ़ॉल्ट्स का कारण बनेगा। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन के आर्ग्युमेंट के रूप में पास करें। |
| [ThreadPool](./threadpool/) | [Thread](./thread/) पूल API जो जॉब को क्यू में पुश करने की अनुमति देता है जिससे वर्कर थ्रेड्स के पूल द्वारा पढ़ा जा सके। यह एक स्टैटिक टाइप है जिसमें कोई इंस्टेंस सर्विस नहीं है। आपको इसे किसी भी माध्यम से इंस्टैंस नहीं बनाना चाहिए। |
| [ThreadPoolImpl](./threadpoolimpl/) | [Thread](./thread/) पूल आंतरिक डेटा। यह एक सिंग्लटन टाइप है जिसमें मेमोरी प्रबंधन एक्सेस फ़ंक्शन(ओं) द्वारा किया जाता है। आपको इसे सीधे इंस्टैंस नहीं बनाना चाहिए। |
| [Timer](./timer/) | [Timer](./timer/) क्लास जो देरी के बाद जॉब आइटम को अलग थ्रेड में निष्पादित करता है। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन फ़ॉल्ट्स का कारण बनेगा। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन के आर्ग्युमेंट के रूप में पास करें। |
| [TimerQueue](./timerqueue/) | क्यू जो [Timer](./timer/) ऑब्जेक्ट्स को संभालती है। यह केवल एक कार्यान्वयन है। [Timer](./timer/) ऑब्जेक्ट्स स्वयं वहां रजिस्टर होते हैं, उनका उपयोग करने के लिये आपको ऐसा करने की आवश्यकता नहीं है – इसके बजाय [Timer](./timer/) क्लास API का उपयोग करें। यह एक सिंग्लटन टाइप है जिसमें मेमोरी प्रबंधन एक्सेस फ़ंक्शन(ओं) द्वारा किया जाता है। आपको इसे सीधे इंस्टैंस नहीं बनाना चाहिए। |
| [WaitHandle](./waithandle/) | वेटिंग प्रिमिटिव बेस क्लास। इस क्लास की ऑब्जेक्ट्स को केवल [System::MakeObject()](../system/makeobject/) फ़ंक्शन का उपयोग करके ही आवंटित किया जाना चाहिए। कभी भी इस प्रकार का इंस्टेंस स्टैक पर या operator new का उपयोग करके न बनाएँ, क्योंकि यह रनटाइम त्रुटियों और/या एसेर्शन फ़ॉल्ट्स का कारण बनेगा। हमेशा इस क्लास को [System::SmartPtr](../system/smartptr/) पॉइंटर में लपेटें और इस पॉइंटर का उपयोग करके इसे फ़ंक्शन के आर्ग्युमेंट के रूप में पास करें। |
## संरचनाएँ

| स्ट्रक्ट | विवरण |
| --- | --- |
| [Timeout](./timeout/) | [Threading](./) टाइमआउट विशेष मान। यह एक स्टैटिक टाइप है जिसमें कोई इंस्टेंस सर्विस नहीं है। आपको इसे किसी भी माध्यम से इंस्टैंस नहीं बनाना चाहिए। |
## एनीम्स

| एनीम | विवरण |
| --- | --- |
| [ApartmentState](./apartmentstate/) | थ्रेड की अपार्टमेंट स्थिति सेट करता है। |
| [EventResetMode](./eventresetmode/) | इवेंट स्थिति के रीसेट होने का तरीका दर्शाता है। |
| [ThreadState](./threadstate/) | थ्रेड की स्थिति। |
## टाइपडिफ़्स

| टाइपडिफ | विवरण |
| --- | --- |
| [ThreadStateException](./threadstateexception/) |  |
| [SemaphoreFullException](./semaphorefullexception/) |  |
| [SynchronizationLockException](./synchronizationlockexception/) |  |
| [ThreadAbortException](./threadabortexception/) |  |
| [ThreadInterruptedException](./threadinterruptedexception/) |  |
| [SendOrPostCallback](./sendorpostcallback/) |  |
| [ParameterizedThreadStart](./parameterizedthreadstart/) | [Thread](./thread/) फ़ंक्शन एकल पैरामीटर के साथ। |
| [ThreadStart](./threadstart/) | [Thread](./thread/) फ़ंक्शन बिना पैरामीटर के। |
| [WaitCallback](./waitcallback/) | एक बार स्थान उपलब्ध होने पर निष्पादित होने वाला कॉलबैक आइटम। |
| [TimerCallback](./timercallback/) | टाइमर द्वारा कॉल किया जाने वाला कॉलबैक फ़ंक्शन। |
| [wait_handle_t](./wait_handle_t/) | हैंडल प्रकार। |