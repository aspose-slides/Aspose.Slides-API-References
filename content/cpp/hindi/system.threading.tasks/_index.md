---
title: "System::Threading::Tasks"
second_title: Aspose.Slides for C++ API संदर्भ
description: 
type: docs
weight: 1015
url: /hi/system.threading.tasks/
---
## क्लासेस

| क्लास | विवरण |
| --- | --- |
| [Parallel](./parallel/) | समांतर लूप और क्षेत्रों के लिए समर्थन प्रदान करता है। |
| [ParallelLoopResult](./parallelloopresult/) | एक [Parallel](./parallel/) लूप की पूर्णता स्थिति प्रदान करता है। |
| [ParallelOptions](./paralleloptions/) | [Parallel](./parallel/) क्लास पर विधियों के संचालन को कॉन्फ़िगर करने वाले विकल्प संग्रहीत करता है। |
| [ResultTask](./resulttask/) | पूरा होने पर परिणाम मान लौटाने वाली [Task](./task/) विशेषीकरण। |
| [ResultValueTask](./resultvaluetask/) | एक हाइब्रिड task-जैसे प्रकार को दर्शाता है जो सीधे परिणाम मान या ResultTask<T> में से किसी को भी लपेट सकता है। |
| [Task](./task/) | एक असिंक्रोनस ऑपरेशन को दर्शाता है जिसे awaited किया जा सकता है और अन्य टास्कों के साथ संयोजित किया जा सकता है। |
| [TaskScheduler](./taskscheduler/) | एक ऑब्जेक्ट को दर्शाता है जो थ्रेड्स पर टास्क को क्व्यू करने का लो-लेवल कार्य संभालता है। |
| [ValueTask](./valuetask/) | एक असिंक्रोनस ऑपरेशन का awaitable परिणाम प्रदान करता है। |

## फ़ंक्शन

| फ़ंक्शन | विवरण |
| --- | --- |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**) | एक टास्क बनाता है जो समय विलंब के बाद पूरा होता है। |
| [TaskPtr](../system/taskptr/) [Delay](./delay/)(**int32_t**, const [CancellationToken](../system.threading/cancellationtoken/)\&) | एक टास्क बनाता है जो समय विलंब के बाद पूरा होता है और रद्द किया जा सकता है। |
| [TaskPtr](../system/taskptr/) [FromCanceled](./fromcanceled/)(const [CancellationToken](../system.threading/cancellationtoken/)\&) | निर्दिष्ट टोकन के साथ रद्दीकरण के कारण पूर्ण हुआ टास्क बनाता है। |
| [TaskPtr](../system/taskptr/) [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | निर्दिष्ट अपवाद के साथ पूर्ण हुआ टास्क बनाता है। |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromException](./fromexception/)(const [Exception](../system/exception/)\&) | निर्दिष्ट अपवाद और परिणाम प्रकार के साथ पूर्ण हुआ टास्क बनाता है। |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [FromResult](./fromresult/)(TResult) | निर्दिष्ट परिणाम के साथ सफलतापूर्वक पूर्ण हुआ टास्क बनाता है। |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&) | निर्दिष्ट कार्य को थ्रेड पूल पर चलाने के लिए क्यू करता है और उस कार्य के लिए एक [Task](./task/) हैंडल लौटाता है। |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Action](../system/action/)<>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | निर्दिष्ट कार्य को थ्रेड पूल पर चलाने के लिए क्यू करता है और उस कार्य के लिए एक [Task](./task/) हैंडल लौटाता है। |
| [TaskPtr](../system/taskptr/) [Run](./run/)(const [Func](../system/func/)\<[TaskPtr](../system/taskptr/)\>\&) | निर्दिष्ट कार्य को थ्रेड पूल पर चलाने के लिए क्यू करता है और फ़ंक्शन द्वारा लौटाए गए [Task](./task/) के लिए एक प्रॉक्सी लौटाता है। |
| [RTaskPtr](../system/rtaskptr/)\<TResult\> [Run](./run/)(const [Func](../system/func/)\<TResult\>\&) | निर्दिष्ट कार्य को थ्रेड पूल पर चलाने के लिए क्यू करता है और उस कार्य के लिए एक Task<TResult> हैंडल लौटाता है। |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | सभी प्रदान किए गए [Task](./task/) ऑब्जेक्ट्स के निष्पादन पूर्ण होने का इंतजार करता है। |
| void [WaitAll](./waitall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | सभी प्रदान किए गए [Task](./task/) ऑब्जेक्ट्स के निष्पादन पूर्ण होने का इंतजार करता है। |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&, const [CancellationToken](../system.threading/cancellationtoken/)\&) | प्रदान किए गए किसी भी [Task](./task/) ऑब्जेक्ट के निष्पादन पूर्ण होने का इंतजार करता है। |
| **int32_t** [WaitAny](./waitany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | प्रदान किए गए किसी भी [Task](./task/) ऑब्जेक्ट के निष्पादन पूर्ण होने का इंतजार करता है। |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | सभी प्रदान किए गए टास्क के पूर्ण होने पर समाप्त होने वाला टास्क बनाता है। |
| [TaskPtr](../system/taskptr/) [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | सभी प्रदान किए गए टास्क के पूर्ण होने पर समाप्त होने वाला टास्क बनाता है। |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | सभी प्रदान किए गए टास्क के पूर्ण होने पर समाप्त होने वाला टास्क बनाता है। |
| [RTaskPtr](../system/rtaskptr/)\<[ArrayPtr](../system/arrayptr/)\<TResult\>\> [WhenAll](./whenall/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | सभी प्रदान किए गए टास्क के पूर्ण होने पर समाप्त होने वाला टास्क बनाता है। |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[TaskPtr](../system/taskptr/)\>\>\&) | प्रदान किए गए किसी भी टास्क के पूर्ण होने पर समाप्त होने वाला टास्क बनाता है। |
| [RTaskPtr](../system/rtaskptr/)\<[TaskPtr](../system/taskptr/)\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[TaskPtr](../system/taskptr/)\>\&) | प्रदान किए गए किसी भी टास्क के पूर्ण होने पर समाप्त होने वाला टास्क बनाता है। |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [ArrayPtr](../system/arrayptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\&) | प्रदान किए गए किसी भी टास्क के पूर्ण होने पर समाप्त होने वाला टास्क बनाता है। |
| [RTaskPtr](../system/rtaskptr/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\> [WhenAny](./whenany/)(const [SharedPtr](../system/sharedptr/)\<[Collections::Generic::IEnumerable](../system.collections.generic/ienumerable/)\<[RTaskPtr](../system/rtaskptr/)\<TResult\>\>\>\&) | प्रदान किए गए किसी भी टास्क के पूर्ण होने पर समाप्त होने वाला टास्क बनाता है। |
| [Runtime::CompilerServices::YieldAwaitable](../system.runtime.compilerservices/yieldawaitable/) [Yield](./yield/)() | एक awaitable टास्क बनाता है जो await करने पर असिंक्रोनस रूप से वर्तमान संदर्भ में लौटता है। |

## एनम

| एनम | विवरण |
| --- | --- |
| [TaskStatus](./taskstatus/) |  |